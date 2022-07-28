<!--
 * @Author: TerryMin
 * @Date: 2022-07-26 17:54:40
 * @LastEditors: TerryMin
 * @LastEditTime: 2022-07-27 15:04:25
 * @Description: file not
-->
# submodule-project

[git submodule使用](https://blog.csdn.net/weixin_44901565/article/details/123086226)

[git子仓库深入浅出](https://juejin.cn/post/6844904034722119694#heading-4)

[npm link基本用法及实例](https://blog.csdn.net/u014291497/article/details/75194456)
npm link用来在本地项目和本地npm模块之间建立连接，可以在本地进行模块测试
在B包里：
npm link // 相当于npm install B -g
在A包里：
npm link B // 代码无需修改，package.json中引用B的包会自动指向本地B的打包文件
A包发布测试环境测试

```
 npm版本号前的字符含义
说几个不太容易记得
~version：大概某个版本 ~1.2.1就是>=1.2.1 && <1.3.0
^version：向后兼容 ^1.2.1就是>=1.2.1 && <2.0.0

版本号格式：主版本号.次版本号.修补版本号

主版本号：新增功能，兼容老版本
次版本号：修复bug，兼容老版本
修补版本号：新的架构调整，不兼容老版本

```
