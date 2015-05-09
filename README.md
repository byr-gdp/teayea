# 关于

这是根据不知名茶效果图相应png文件来重构的部分成果

# 登陆注册

### 需要注意事项

1. 缩放水平border出现错位
2. input输入框光标具体显示位置
3. 每行元素布局如何进一步优化，在缩放过程中等比例变化以至于不会变形
4. 由于手头只有设计图的PNG文件，所以只是用绘图工具简单的做了遮挡处理


## 登录注册1

### 1.进一步完善所需信息

1. 第一个input垂直位置所占百分比：目前50%
2. 两个input高度差：目前36px
1. input
	1. width：目前225px
	2. border-radius：目前10px
2. 手机号
	1. 到border-left距离：目前25px
	2. font-size：目前14px
	3. font-family:"SimHei""Microsoft YaHei";
3. 进入不知名茶世界
	1. font-size: default
	2. font-family: default


### 2.效果图

![](http://i.imgur.com/DYNKF4x.jpg)

## 登录注册2

### 1.进一步完善所需信息

1. 第一个input垂直位置所占百分比：目前42%
2. 水平高度差 自上而下 依次为: 12px 40px 16px 36px
3. span
	1. 宽度： 目前128px
	2. font-family:"SimHei""Microsoft YaHei"
	3. font-size: 14px
4. input
	1. 宽度：128px 285px
	2. font-family:"SimHei""Microsoft YaHei"
	3. font-size: 14px
	4. 密码、重复密码 到 border-left 距离：6个&nbsp

### 2.存在的问题

1. 验证码**placeholder**设置样式
  
### 3.效果图

![](http://i.imgur.com/Nuqoiug.jpg)

## 登录注册3

### 1.进一步完善所需信息
1. 第一个input垂直位置所占百分比：目前50%
2. 水平高度差：目前36px
3. input
	1. 宽度：285px
	2. font-family:"SimHei""Microsoft YaHei"
	3. font-size: 14px
	4. 密码 到 border-left 距离：5个&nbsp


### 2.效果图

![](http://i.imgur.com/MPtJZmw.jpg)

# 3-1——3-3



### 需要注意事项

1. 下拉菜单为了实现透明采用ul+li来实现
2. 水平方向若干个 div 若高度不等，会向下对齐。理想状态时向上
3. 最下方“取消”和“确认”具体位置（精确到像素）

## 3-1

### 1.进一步完善所需信息（待完善）

### 2.效果图

![](http://i.imgur.com/vDS1ak2.jpg)

## 3-2

### 1.进一步完善所需信息（待完善）

### 2.效果图

![](http://i.imgur.com/RTfSMIl.jpg)

## 3-3

### 1.进一步完善所需信息（待完善）

### 2.效果图

![](http://i.imgur.com/6SlBNre.jpg)