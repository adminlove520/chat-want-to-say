#### 1. How To Use

```bash
cd chat-want-to-say
yarn dev
# see http://localhost:3000/
```

#### 2. 编译打包

```bash
sh bin/build.sh
cd dist
# 将 dist 目录的内容部署到静态服务器，通过 anywhere 可以预览效果
yarn global add anywhere
anywhere
```

### 3. 部署至静态服务器

```bash
scp -r chat-want-to-say/dist/** root@domain:/nginx-html/
```
One and Only For 蓉蓉
By Anymore520
