#### 参考vscode源码配置

- vscode 处理崩溃的位置主要在 app.ts中'uncaughtException'捕获和 window.ts 中的
'unresponsive'中捕获

#### electron 失效
有些场景，比如在与其它软件交互过程中，接受到某些讯息，需要将Electron窗口显示在最前面，普通的moveTop并不生效，可以以使用以下方法：

// 设置总是在最前面，后设为false
win.setAlwaysOnTop(true);
setTimeout(() => {
  win.setAlwaysOnTop(false);
}, 100);