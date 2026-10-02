# 命令速查

在聊天输入框输入。`<玩家名>`、`<世界名>` 要换成实际名称，尖括号不用输入。

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
| `/yes` | 接受收到的请求 |
| `/no` | 拒绝收到的请求 |
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

