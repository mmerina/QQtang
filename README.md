# JS-game

# 简介
用js结合Jquery和underscore两个库完成的简单小游戏：炸弹人（QQ堂精简版），利用了面向对象的思想和中介者模式，全部动态效果使用全局定时器实现。大概是某次没有网的自娱自乐？？

# 玩法说明
1、空格放炸弹、炸掉附近元素；
2、角色能推动可移动元素；
3、有三种道具可以拾取，可增加角色相应的属性；
4、每个地图有一定数目的怪物数量，怪物可拾取道具，拾取了道具的怪物被炸死后道具会被炸出来；
5、 被炸死为失败，完成任务即可过关；
6、四种角色、四种炸弹和四种地图可选

# 项目文件夹：
该项目的文件夹结构如下所示：<br>
```javascript
    ┠ audio 音频文件
    ┠ css 样式文件
    ┠ images 图片文件
	  ┠ js 	开发文件
    ┃  ┠ json 数据文件
			  ┃ ┠	bomb_json 炸弹数据
			  ┃ ┠	map_json 地图数据
			  ┃ ┠	role_json   角色数据
		┃  ┠	Bomb 炸弹类
    ┃  ┠	BoomElement 被炸元素类
    ┃  ┠	Creature 怪物类
    ┃  ┠	Game 游戏类
    ┃  ┠	Map 地图类
    ┃  ┠	MoveElement 可移动元素类
    ┃  ┠	NoMove 不可移动元素类
    ┃  ┠	Role 角色类
    ┃  ┠	Prop 道具类
    ┠	index 主页
		
```
# 项目启动
直接打开index就能玩

为了让画面看上去有2.5D的感觉，所有元素都是DOM节点动态生成z-index值来实现遮挡orz
