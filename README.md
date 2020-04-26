# frontend-tools
### nvm

```bash
nvm --help				# 查看帮助说明
nvm list				# 列出所有node版本
nvm install v11.14.0    # 安装node版本
nvm use 10.15.1		# 使用10.15.1版本的node
```

### npm

```bash
# 设置淘宝源
npm config set registry https://registry.npm.taobao.org
# 设置公司的源
npm config set registry http://127.0.0.1:4873
# 查看源，可以看到设置过的所有的源
npm config get registry

npm install -g cnpm --registry=https://registry.npm.taobao.org     # 安装cnpm
npm install -g @vue/cli
npm install -g @vue/cli-service-global@3.9.2
npm install -g @vue/cli@3.9.2
```

### yarn

```bash
yarn --help
yarn -v
yarn config get registry    # 默认的源 https://registry.yarnpkg.com
yarn config set registry 'https://registry.npm.taobao.org/'
yarn global add @vue/cli
```

