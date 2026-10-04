# 命令速查

在聊天输入框输入。`<玩家名>`、`<世界名>`、`<传送点名称>` 要换成实际名称，尖括号不用输入。

> [!NOTE]
> 当前线上版本为 **1.5.1**；以下标注的 **1.5.2** 改善尚待部署，启用时间以服主公告为准。

## 面板与日常

| 指令 | 用途 |
| --- | --- |
| `/menu` | 服务器面板 |
| `/tasks` | 今日任务 |
| `/checkin` | 每日签到 |
| `/coins` | 金币余额 |
| `/store` | 普通服务器商店 |
| `/bag` | 服务器背包 |

## Home 与传送

| 指令 | 用途 |
| --- | --- |
| `/sethome` | 保存当前世界的 Home |
| `/home` | 回当前世界的 Home |
| `/home <世界名>` | 回指定世界的 Home |
| `/check home <世界名>` | 查看指定世界的 Home 坐标 |
| `/tpn <玩家名>` | 申请传送到对方身边 |
| `/yes` | 接受传送请求或确认删除 Warp |
| `/no` | 拒绝传送请求或取消删除 Warp |
| `/warp list [世界]` | 公共传送点分类、列表与收藏 |
| `/warp warp <传送点名称>` | 直接前往指定名称的公共传送点（1.5.2 待部署） |
| `/warp set <传送点名称>` | 在允许世界分享当前位置 |
| `/warp delete [世界]` | 删除自己的传送点；20 秒内确认 |
| `/spawn` | 回大厅，由独立 NekoSpawn 提供 |

常用的两个写法：

```text
/home world
/home world_new
```

---

## 同名指令冲突

NekoCore 指令可以加插件前缀：

```text
/nekocore:tasks
/nekocore:home world_new
/nekocore:store
/nekocore:bag
```

加前缀不会绕过权限。NekoCore 没有公开 `/levelshop`、`/afk`、`/cancel` 玩家命令；头衔和挂机池请从大厅入口或菜单进入。

[返回目录](../README.md)

