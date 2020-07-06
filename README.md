## 运行
```
git clone https://github.com/lin-xin/calculator.git
npm install
npm start
```
就会运行起来了。

## 构建
```
windows npm run build:win
linux npm run build:linux
```
则会在项目中生成个 /计算器-win32-x64 文件夹，打开里面的 计算器.exe 即可打开计算器。

或者
```
npm run dist
```
则会生成 dist/ 文件夹，里面有应用的安装包，就可以双击安装了。安装过程中可能会有360卫士等提示危险，不用管继续安装就可以。