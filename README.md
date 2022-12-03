# tModLoader 注释汉化
这个项目是一个对于 tModLoader 注释文档(xml)的汉化，其内容会在使用 IDE 编辑模组代码时显示。将其汉化有助于新手快速上手tML内容

由于文本量实在庞大，单我一人仅靠人工汉化无法完成，所以汉化采用**机翻+润色**以靠近人工汉化，保证能够正确表意，不会发生诸如将Player翻译成播放器，将Vanilla翻译成香草的尴尬情况

## 效果截图
![image](https://user-images.githubusercontent.com/35227653/205429026-a48b272a-1ff2-436a-bfe8-4eaeadda6477.png)

## 使用方法
你当然可以直接覆盖原 `tModLoader.xml` 文件，但这在 tML 每次更新后就会被覆盖，以下是一个更好的方式:

### Step 1
转到 tML 的安装根目录，你可以在 Steam 中选择“浏览本地文件”来打开，如图:  
![image](https://user-images.githubusercontent.com/35227653/205428227-f1cf6d44-7d73-4b33-9df7-68f4760e1671.png)

### Step 2
在根目录下新建文件夹，将其命名为 `zh-hans`，如图:  
![image](https://user-images.githubusercontent.com/35227653/205428268-37ad8729-36ce-4a36-a041-b4d07cfa9cdf.png)

### Step 3
下载[该仓库的zip文件](https://github.com/Cyrillya/tModLoader-Document-Chinese/archive/refs/heads/chinese.zip)并解压，将 `tModLoader.xml` 文件放入你刚创建的 `zh-hans` 文件夹中:  
![image](https://user-images.githubusercontent.com/35227653/205428790-08ce2f63-e13e-47c4-8548-3f1c32ea2ccf.png)

如果你的网络不好，没法使用上面的链接下载，可以[试试这个链接](https://ghproxy.com/?q=https%3A%2F%2Fgithub.com%2FCyrillya%2FtModLoader-Document-Chinese%2Farchive%2Frefs%2Fheads%2Fchinese.zip)

### Step 4
打开 IDE 并将 IDE 语言设置为简体中文 (一般来说，在默认情况下 IDE 语言跟随系统语言) 即可看到翻译后文本。如果你的 IDE 先前已经在运行，重启即可
