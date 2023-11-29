<h1 align="center" style="margin: 30px 0 30px; font-weight: bold;">pb_hone v1.0.0</h1>

<h4 align="center">基于SpringBoot+Vue3前后端分离的Java快速开发框架</h4>
<p align="center">
</p>

## ⚡ 平台简介 ⚡

- 本仓库是 Agilboot 快速开发脚手架的配套前端项目。前端是基于优秀的开源项目[Pure-Admin](https://github.com/pure-admin/vue-pure-admin)开发而成。在此感谢 Pure-Admin 作者。
- 本仓库前端技术栈 [Vue3](https://v3.cn.vuejs.org) + [Element Plus](https://element-plus.org/zh-CN) + [Vite](https://cn.vitejs.dev) 版本。
- 配套后端代码仓库地址[pb_home](https://github.com/lfqs/pb_home) 版本。

## ✨ 使用 ✨

### 开发环境

node 版本应不小于 16 ，pnpm 版本应不小于 6  
版本请勿过新，有先选择 node=16, pnpm=7.30.5  
如果您还没安装 pnpm，请执行下面命令进行安装（mac 用户遇到安装报错请在命令前加上 sudo） 如果是 windows 用户 用使用管理员 power shell 来执行

```
npm install -g pnpm
```

安装依赖

```
pnpm install
```

启动平台

```
pnpm dev
```
打包

```
pnpm build
```

换源地址

npm config set registry https://registry.npmmirror.com
上面的命令是将本地的源换成国内源 npmmirror
(opens new window)，经过几轮测试，发现它的下载速度快且同步率高，同步频率 10 分钟一次，如果您之前的源是这个 http://registry.npm.taobao.org ，那您必须换成 npmmirror 啦，因为原淘宝 npm 域名即将停止解析

## 🙊 系统内置功能 🙊

🙂 大部分功能，均有通过 **单元测试** **集成测试** 保证质量。

|     | 功能       | 描述                                                          |
| --- | ---------- | ------------------------------------------------------------- |
|     | 用户管理   | 用户是系统操作者，该功能主要完成系统用户配置                  |
| ⭐  | 部门管理   | 配置系统组织机构（公司、部门、小组），树结构展现支持数据权限  |
| ⭐  | 岗位管理   | 配置系统用户所属担任职务                                      |
|     | 菜单管理   | 配置系统菜单、操作权限、按钮权限标识等，本地缓存提供性能      |
| ⭐  | 角色管理   | 角色菜单权限分配、设置角色按机构进行数据范围权限划分          |
|     | 参数管理   | 对系统动态配置常用参数                                        |
|     | 通知公告   | 系统通知公告信息发布维护                                      |
| 🚀  | 操作日志   | 系统正常操作日志记录和查询；系统异常信息日志记录和查询        |
|     | 登录日志   | 系统登录日志记录查询包含登录异常                              |
|     | 在线用户   | 当前系统中活跃用户状态监控                                    |
|     | 系统接口   | 根据业务代码自动生成相关的 api 接口文档                       |
|     | 服务监控   | 监视当前系统 CPU、内存、磁盘、堆栈等相关信息                  |
|     | 缓存监控   | 对系统的缓存信息查询，命令统计等                              |
|     | 连接池监视 | 监视当前系统数据库连接池状态，可进行分析 SQL 找出系统性能瓶颈 |

### 许可证

原则上不收取任何费用及版权，可商用，不过如需二次开源（比如用此平台二次开发并开源，要求前端代码必须开源免费）请联系作者获取许可！（免费，走个记录而已）
