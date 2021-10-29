# README

## CR-THEMW
for wangcr 

## 开发指南
命令
```
#启动项目
cd themes
code .

# 打包
npm install -g vsce
vsce package

# 注意事项
1. 在package.json中添加
"publisher": "wangcr",
2. 在package.json中添加
 "repository": {
        "url": "https://github.com/Hicr/CRthemeVscode.git"
    }
```

3. themes.json文件类型为TypeScrip，开发调试类型为VSCODE

4. 安装本地插件
 在VSCode中点击扩展，三个。。。，选择从vsix处安装进行安装
