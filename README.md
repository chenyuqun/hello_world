# hello_world
-Github is fun!
-A new start
------
## 助力活动契约
------
### 0. 通用接口

所有接口都需要微信授权后获得的access_token 还需要一些微信的基本信息 头像 昵称 手机等

### 1. 飞行排行榜 

查看目前进行过助力游戏的排名 对结果进行缓存 每一小时刷新一次

### 2. 进行游接口/好友助力游戏页

根据微信用户id 获取里程 抽象成获取一个随机数  每玩一次就记录一条数据 方便对每天一次这个要求进行控制
如果是通过分享链接进入的 则多一个助力人的open_id参数 并且显示被助力人的相关信息

### 3. 登陆注册接口

复用现有m站的流程

### 4. 领奖页面接口

检查用户该微信open_id是否注册过芒果网用户，没有的话跳转到登陆注册页面
如果已经是芒果网用户，展示能兑奖的列表和历史

### 5. 领奖接口

微信open_id和要领的产品 系统校验是否能够领取

### 6. 分享页面

根据微信oepnid获取里程 头像 昵称 

### 7. 好友助力排行榜

根据微信openid获得公里数 今天是否还可以再玩一次 已经好友帮助自己助力的相关信息

### 8 好友助力结果页

根据微信openid获得已经助力过的人的列表信息和总里程
