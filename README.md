# hexo-cli

自用的hexo命令扩展

如果你没有用过@jiangtj的npm包，需要先添加@jiangtj指向GitHub
```bash
echo @jiangtj:registry=https://npm.pkg.github.com/ >> .npmrc
```

配置
```yml
jiang:
  post_base_dir:
```

## Debug
```bash
yarn link
hexo init example
cd example
yarn link @jiangtj/hexo-cli
yarn add @jiangtj/hexo-cli
```
