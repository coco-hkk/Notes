# 笔记

## 访问 WEB

1. 登录 [Read the Docs](https://app.readthedocs.org/) 关联 Github
2. 在主页点击 `+ Add project`
3. 查找 github 仓库 `Notes`
4. 添加名称 `coco-hkk`
5. 访问网页 `https://coco-hkk.readthedocs.io`

## 本地编译

```powershell
# 清空 build 目录
make clean
# 编译项目，生成的网页在 build 目录中
make html
# 点击 build/html/index.html 访问
```
