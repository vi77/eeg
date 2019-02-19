# Bmob 增删查改
[进入编辑界面 > 鼠标右键 > 开始 ](https://eeg-admin.bmob.cn/#/editor/eeg)
![节点图](https://raw.githubusercontent.com/vi77/eeg/master/images/node/bmob.png)


Bmob数据库的相关操作，现只包含`增`、`删`、`查`、`改`四个节点

- *[Bmob是什么?](https://bmob.cn/cloud)*

- *[注册Bmob](https://bmob.cn/login)*

- *[Bmob官网](https://bmob.cn/)*

## 配置

- 需要[注册Bmob账号](https://bmob.cn/login)
- 创建应用，然后在设置中找到`Appid`、`RestKey`
- 在[脑图管理后台-设置-节点参数](https://eeg-admin.bmob.cn/#/setting/nodeparams)内，填入Bmob相关的Key


## 数据
### Bmob新增
- 新增节点中的表名一定要和Bmob后台建立的应用表名保持一致，否则可能出现数据为空的状态。

- 数据内容可建立参数进行动态输入（参数中的别名对应为Bmob表中的列名）

![节点图](https://raw.githubusercontent.com/vi77/eeg/master/images/node/new1.png)

### Bmob删除
用法参考Bmob新增

### Bmob查询
- 查询可按照表名或者ID进行
- 与增删改不同的是，查询可以添加规则，如count=1

### Bmob修改

- 用法参考Bmob新增
- 在Bmob修改节点中输入所要修改数据的id，在对应的参数节点别名中输入要修改的列，保存后运行即可！
- ![节点图](https://raw.githubusercontent.com/vi77/eeg/master/images/node/revise.png)

## 示例

![节点图](https://raw.githubusercontent.com/vi77/eeg/master/images/node/ZSCG-sample1.png)
![节点图](https://raw.githubusercontent.com/vi77/eeg/master/images/node/ZSCG-sample2.png)
![节点图](https://raw.githubusercontent.com/vi77/eeg/master/images/node/ZSCG-sample3.png)