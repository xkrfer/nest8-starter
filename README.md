## cloudbase-template of nestjs 8.x

参照 [nest-starter](https://github.com/TencentCloudBase/cloudbase-templates/tree/master/nest-starter) 修改而成

## 开发一个nestjs 8.x 项目

### 步骤一. 准备工作

具体步骤请参照 [准备云开发环境和 CloudBase CLI 命令工具](https://github.com/TencentCloudBase/cloudbase-framework/blob/master/CLI_GUIDE.md)

### 步骤二. 克隆本仓库到本地

在命令行执行以下命令

```bash
git clone https://github.com/xkrfer/nest8-starter
```

### 步骤三. 将 cloudbaserc.json 中 envId 设置为云开发环境的环境ID

### 步骤四. 一键部署

进入到项目目录，在命令行执行

```
npm run deploy
```

## 开发命令及配置

### 本地开发

```
npm run start:dev
```

### 上线部署

```
npm run deploy
```

### Lint

```
npm run lint
```

### CloudBase Framework 相关开发配置

查看 [CloudBase Framework 配置](https://github.com/TencentCloudBase/cloudbase-framework).

### Nest 开发文档

查看 [starter](https://docs.nestjs.com/).
