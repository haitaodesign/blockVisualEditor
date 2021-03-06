# blockVisualEditor

## 区块可视化代码编辑器
1. 选择项目模板，自动生成项目框架（router\store\api\page...）
2. 进入一个页面，先进行布局拆分
3. 拖拽相应的区块组件放到已拆分好的布局中
4. 点击区块进行区块化代码编辑（代码交互逻辑在这里完成）
5. 返回到项目列表并启动该项目，进行预览 (npm run serve)

## 不需要关心
1. 项目工程结构 app
2. 路由文件 router
3. 页面文件 page
4. 公共数据文件 store
5. 数据接口文件 api
6. 项目模板 appTemplate

## 目的
1. 针对中后台开发系统
2. 项目紧急
3. 针对前后端开发人员使用
4. 提高开发效果
5. 统一规范代码结构，可维护性提高
6. 提升开发流程规范
7. mockapi文档、项目模板文档、区块模板文档、一键上传git仓库、环境部署等等

## 界面展示

#### 创建项目、项目列表
![image](https://raw.githubusercontent.com/sww1230/blockVisualEditor/master/pic/a.png)

#### 选择项目模板
![image](https://raw.githubusercontent.com/sww1230/blockVisualEditor/master/pic/b.png)

#### 页面布局拆分、拖拽区块
![image](https://raw.githubusercontent.com/sww1230/blockVisualEditor/master/pic/c.png)

#### 编辑区块代码
![image](https://raw.githubusercontent.com/sww1230/blockVisualEditor/master/pic/d.png)

#### apiMock接口文档、页面的公共数据
![image](https://raw.githubusercontent.com/sww1230/blockVisualEditor/master/pic/e.png)

## 安装依赖
```
yarn install
```

### 运行
```
yarn run electron
```

> 启动起来是黑屏，cmd命令执行完毕后，记的刷新下IDE哦...
