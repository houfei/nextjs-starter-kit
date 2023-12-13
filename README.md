<h1 align="center">{项目名称}</h1>
<p align="center">
  <a href="https://nextjs.org/"><img src="https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js"></a>
  <a href="https://react.dev/"><img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React.js"></a>
    <a href="https://nodejs.org/"><img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"></a>
  <a href="https://www.npmjs.com/"><img src="https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white" alt="NPM"></a>
  <a href="https://bun.sh/"><img src="https://img.shields.io/badge/Bun-%23000000.svg?style=for-the-badge&logo=bun&logoColor=white" alt="Bun"></a>
  <a href="https://github.com/"><img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="https://code.visualstudio.com/"><img src="https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="Visual Studio Code"></a>
</p>

## ⚙️ 项目初始化

```text
[~/Code/nextjs]$ npx create-next-app@latest {项目名称}
Need to install the following packages:
create-next-app@14.0.4
Ok to proceed? (y) y
✔ Would you like to use TypeScript? … No
✔ Would you like to use ESLint? … Yes
✔ Would you like to use Tailwind CSS? … Yes
✔ Would you like to use `src/` directory? … No
✔ Would you like to use App Router? (recommended) … Yes
✔ Would you like to customize the default import alias (@/*)? … No
Creating a new Next.js app in /Code/nextjs/{项目名称}.

next dev
bun dev 
npm run dev
```

```mysql
CREATE DATABASE `{项目名称}` DEFAULT CHARACTER SET `utf8mb4` COLLATE `utf8mb4_general_ci`;
```

## 📝 项目约定和代码规范

### 服务器和版本控制分支

* 开发环境代码库分支：`develop` => `http://localhost:3000`
* 测试环境代码库分支：`released` => `https://dev.{项目名称}.com`
* 生产环境代码库分支：`master` => `https://{项目名称}.com`

### Env & Postman 环境配置

* 开发环境接口 host：`http://localhost:3000`
* 测试环境接口 host：`https://dev.{项目名称}.com`
* 生产环境接口 host：`https://{项目名称}.com`

### Git 约定式提交规范

#### 提交类型

```text
feat:     新功能
fix:      修复
docs:     文档变更
style:    代码格式(不影响代码运行的变动)
refactor: 重构(既不是增加feature，也不是修复bug)
perf:     性能优化
test:     增加测试
chore:    构建过程或辅助工具的变动
revert:   回退
build:    打包
```

#### 提交格式

```text
<类型>[功能模块(可选)]: <提交概要描述>

[提交正文(可选)]

[脚注(可选)]

-------- 示例 --------

docs(README): 创建项目规范

* 创建项目代码提交约定
* 创建代码格式化规范

issue 666
```