# HeyAuth 更新日志

## V0.5.0 Alpha 6

### 2025-04-10

-   优化 大量代码，加快Windows环境的启动速度
-   优化 pkg 组件的类结构

## V0.5.0 Alpha 5

### 2025-03-14

-   修复 颜色切换刷新即失效

### 2025-03-13

-   修复 管理员B端额度无法显示

### 2025-03-12

-   新增 初步支持插件

### 2025-03-10

-   修复 状态码非200的显示问题

### 2025-03-08

-   优化 配置文件的读取

### 2025-03-07

-   优化 中间件代码逻辑
-   修复 未登录访问者也可登录管理员界面

### 2025-03-04

-   适配 NiceGUI 2.12.1 无需定制版依赖即可享受连接丢失时的多语言支持
-   恢复 B端产品的后台显示
-   修复 没有B端授权时管理员后台加载失败

### 2025-03-03

-   新增 首页新增产品详情布局
-   新增 从身份证中读取信息
-   新增 腾讯二要素/三要素实名认证
-   修复 若干Bug

### 2025-02-28

-   新增 B端产品选择Dialog
-   修复 用户选择Dialog选中后无法取消

### 2025-02-27

-   新增 清理工具新增 `安全删除`、 `更多清理选项`、 `虚拟环境清理`、 `模拟运行` 等功能
-   新增 用户选择Dialog
-   优化 进一步优化数据库的性能
-   优化 清理工具的错误处理

## V0.5.0 Alpha 4

### 2025-02-24

-   修复 管理员面板用户编辑用户不自动填充

### 2025-02-23

-   优化 添加用户
-   优化 管理员面板用户的显示

-   修复 管理员面板用户仪表盘

### 2025-02-22

-   优化 数据库中间件

-   修复 后台面板的仪表盘

### 2025-02-21

-   新增 其他数据库操作器

-   优化 用户前端面板


## V0.5.0 Alpha 3

### 2025-02-10

-   优化 首页的响应式渲染

### 2025-02-08

-   新增 用户与设置操作方法
-   新增 连接丢失时的多语言支持（需要定制版依赖，已向官方提交Pr）

-   修复 未登录用户也能进入管理员后台
-   修复 登录屡次密码错误

## V0.5.0 Alpha 2

### 2025-01-26

-   修复 SQLModel创建表，现在可以创建任何表了

### 2025-01-25

-   新增 SQLModel支持创建表（只能创建B端授权、产品、额度和系统日志四张表，待修复）

-   优化 内置API文档的显示
-   优化 登录接口的安全性（没完成）

-   修复 日志记录器的异常
-   修复 自动文档的summary与description显示信息

### 2025-01-24

-   新增 VSCode 快速启动
-   新增 HeyAuth 快速清理

-   优化 分页加载管理员后台，显著提高加载速度，降低占用

-   修复 用户管理面板标题栏显示异常