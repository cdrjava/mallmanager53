##  Vue项目重点

###  day-07-重点

#### 01-项目准备-项目
1. src/
2. build/ webpack相关代码导入
3. config/ 本地服务器配置
4. .eslintignore estic排除文件
5. .eslinttrc eslint配置文件
#### 02-项目-准备-代码规范-自定义指令-lintfix
1. 结尾没有
2. 必须用全等
3. 不允许出现未使用的变量
4. 不允许一个以上的空行
5. 关键字后面必须加空格
6. 函数名后必须加空格
>在package.json中自定义指令：指令很长
>npm run 自定义指令名
>npm run lintfix(自动按照规范修正代码全部(但是，多余的变量这个error不会修正)的js代码)
>自动打开浏览器 dev:"xxxxxx --open"

>关闭eslint build/webpack.base.conf.js注释43代码

#### 03-项目-准备-element-ui-文档分析
-element-ui 是饿了么开发团队
-适用于vue 项目-pc-端项目
-在main.js 引入

#### 04-项目-准备-element-ui-安装-引入
>npm i element-ui -s
>在main.js import
>Vue.use(ElementUI)

### 05-项目-准备-项目模板-调整
>删除模板中我们用不到的文件
#### 06-项目-准备-git 版本控制
>git/svn
1.git init ->.git
2.git status
3.git add .
4.git commit -m "注释"
5.git commit -m ""
