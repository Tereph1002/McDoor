# McDoorとは?
McDoorは、MinecraftサーバーのBackdoorプラグインです。<br>
Op権限の操作や、サーバー機の操作等ができます。
# バージョン
## 対応バージョン
- 1.18.2
- 1.18.1
## Javaバージョン
- Java17
#機能
## OpGuard検知
McDoorは、OpGuardを検知することが出来ます。<br>
Op権限を操作した瞬間、Banされたりすることが在りません。
## LuckPerms検知
McDoorは、LuckPermsを検知することが出来ます。<br>
これにより、LuckPermsが入っていることにいち早く気づけます。
## Commandリスト
- `#.help` - Helpコマンド
- `#.op <MCID / "me">` - 特定のプレイヤーまたは自分にOp権限を付与
- `#.deop <MCID / "me">` - 特定のプレイヤーまたは自分からOp権限をはく奪
- `#.gm <GM Number>` - 自分のゲームモードを変更
- `#.give <ItemID> <Count>` - 自分にアイテムを付与
- `#.kick <MCID>` - 特定のプレイヤーをKick
- `#.timeout <MCID>` - 特定のプレイヤーをタイムアウトとしてKick
- `#.ban <MCID>` - 特定のプレイヤーをBan
- `#.plugins` - プラグインのリストを取得
- `#.displ <PLName>` - 特定のプラグインを無効化
- `#.enapl <PLName>` - 特定のプラグインを有効化
- `#.opguard <Request> <Operation>` - OpGuardを操作
- `#.luckperms <Request> <Operation>` - LuckPermsを操作
- `#.explorer <Path> <Operation>` - サーバー機のファイルを操作
- `#.server <Operation>` - サーバーの情報を取得
- `#.ip` - サーバーの直IPを取得
- `#.stop` - サーバーを停止
- `#.restart` - サーバーを再起動
- `#.disoff` - Offlineモードを無効にする
- `#.enaoff` - Offlineモードを有効にする
