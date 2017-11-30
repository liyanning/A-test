问题一：如何改变泡泡糖的皮肤？
答：可以，具体步骤为：
 2-1. 场景定位：
2-1.1. 定位到src/res/layout文件夹下的main_layout.fxml布局文件。
2-1.2. 找到文件中id为mainPane的AnchorPane标签。
 2-2. 修改样式
        2-2.1. 将mainPane的stylesheets属性，从“@../css/skin2.css”修改为“@../css/skin1.css”
2-3. 运行项目工程，选择cn.campsg.practical.bubble.MainClass类作为启动类
问题二：如何获得奖励分数？
答：首先你得大于关卡分数，然后剩下的泡泡糖（消到不能消了为止）的个数小于10个，就可以获得额外奖励分数。
问题三：游戏版本会提升吗？
答：会的，游戏版本会不断地提升，力求为用户带来更好的游戏体验
