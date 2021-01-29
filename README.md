# Write Web Icons
[Write Web Icons](https://95jm9.csb.app/)

主要
It's a repository for [Figma Icon Automation Plugin](https://github.com/leadream/figma-icon-automation).


## 使用 / use


### in react 

```JSX
import { IAdd } from "write-web-icons";

<IAdd size="16" />
```
[demo](http://gitlab.inner.yuewen.local/webnovel/mobile-webnovel-js/-/tree/master/libs/icon)

## 开始 / start

Open [Figma](https://www.figma.com/file/vOnQcggQIyNzzA4SdSU00c/%E2%9D%96%E4%BD%9C%E5%AE%B6%E7%BA%BF-Design-Asset-%2F-Icons?node-id=910%3A0&viewport=1037%2C329%2C1.1874465942382812)

> you need have the acccess to view this figma url

## 安装 Figma 插件 / Install figma plugin

- [figma-icon-automation](https://www.figma.com/community/plugin/739395588962138807/figma-icon-automation)

点击链接下载插件。

## 配置 / settings 

![填写token](./imgs/plugin-settings.png)

- **GitHub Repo Url**: `https://github.com/yued-fe/write-web-icons`
- **GitHub token**：联系 [ShineaSYR](https://github.com/ShineaSYR) 获取

1. 打开 Figma 并呼起 `figma-icon-automation` 插件。
2. 填写 GitHub Repo Url 也就是当前 Github 地址。
3. 填写 GitHub Token.

## 发布 / Publish

![发布](./imgs/plugin-publish.png)

1. 点击 Update 按钮，跳转到 Publish 页卡。
2. 一定要等到出现黑色加粗文字 `The current version is *.*.*`。
3. 然后填写想要发布的新的版本号，和修改信息，并点击 `push to Github`。

## 合并分支 / Pull requests

![Pull requests](./imgs/plugin-published-successfully.png)

![Pr](./imgs/merge-pr.png)

1. 点击 `here` 
2. 再点击 `Squash and merge`。


## 查看效果 / Preview

![preview](./imgs/preview.png)

- [codesandbox](https://codesandbox.io/s/write-web-icons-95jm9)

然后点击以上链接，并在 Dependencies 中升级 [write-web-icons](https://www.npmjs.com/package/write-web-icons) 到刚刚 Figma 中发布的版本，即可看到效果。
