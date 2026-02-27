# FoodBuddies-page 发布到 GitHub Pages

这个文件夹只包含支持页，可单独推到一个**公开**仓库并开启 Pages，主仓库 FoodBuddies 可保持私有。

## 1. 在 GitHub 上新建公开仓库

1. 打开 https://github.com/new
2. **Repository name** 填：`FoodBuddies-page`
3. 选 **Public**
4. **不要**勾选 "Add a README file"（保持空仓库）
5. 点 **Create repository**

## 2. 在本机推送这个文件夹

在终端执行（把 `Wally123666` 换成你的 GitHub 用户名）：

```bash
cd /Users/jiakun/Dev/Projects/FoodBuddy-main/FoodBuddies-page

git init
git add index.html README.md
git commit -m "FoodBuddies support page"
git branch -M main
git remote add origin https://github.com/Wally123666/FoodBuddies-page.git
git push -u origin main
```

（若已建好仓库且名字/用户名不同，改最后两行的仓库地址即可。）

## 3. 开启 GitHub Pages

1. 打开 https://github.com/Wally123666/FoodBuddies-page
2. **Settings** → 左侧 **Pages**
3. **Source** 选 **Deploy from a branch**
4. **Branch** 选 **main**，**Folder** 选 **/ (root)**，点 **Save**

## 4. 访问地址

等 1～2 分钟后访问：

**https://wally123666.github.io/FoodBuddies-page/**

把此链接填到 App Store Connect / Google Play 的「支持 URL」即可。
