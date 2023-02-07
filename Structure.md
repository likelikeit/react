### 目录结构
fixtures 为开发者准备的小型react测试项目
packages 所有react相关的包存放于此
scripts 各种工具链脚本 git jest eslint

  -- packages
    -- renderer类相关包
      -- react-dom 浏览器渲染 ssr渲染
      -- react-art 对接canvas svg
      -- react-noop-renderer debug fiber
    -- 实验性功能
      -- react-reconciler fiber reconciler
    -- 辅助功能
      -- react-fetch 数据请求
      -- react-is 测试组件类型
      -- react-refresh 在运行调试时候 使用热更新保证react component 不会丢失状态
      -- react 
          包含全局api的所有核心模块
        1.React.createElement
        2.React.Component
        3.React.Children
      -- scheduler 调度器实现
      -- shared 源码中其他模块公用方法和全局变量


