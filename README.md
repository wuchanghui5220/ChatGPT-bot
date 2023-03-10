# ChatGPT-bot

# 前提 
安装Node.js。可以从Node.js官网 https://nodejs.org/en/download/ 下载适合您系统的安装程序。

打开CMD终端，验证node.js是否安装成功。

验证node

    C:\Users\wucha>node -v
    v18.14.2
验证npm

    C:\Users\wucha>npm -v
    9.6.0
    
# 安装ChatGPT-bot
如果你的系统没有 git 命令，请到 Git官网 https://git-scm.com/downloads 下载适合您系统的安装程序。

    git clone https://github.com/wuchanghui5220/ChatGPT-bot.git
    cd ChatGPT-bot
    npm install
    
出现以下报错可以忽略：

    C:\Users\wucha\ChatGPT-bot>npm install
    npm WARN deprecated urix@0.1.0: Please see https://github.com/lydell/urix#deprecated
    npm WARN deprecated source-map-url@0.4.1: See https://github.com/lydell/source-map-url#deprecated
    npm WARN deprecated source-map-resolve@0.5.3: See https://github.com/lydell/source-map-resolve#deprecated
    npm WARN deprecated resolve-url@0.2.1: https://github.com/lydell/resolve-url#deprecated
    npm WARN deprecated chokidar@2.1.8: Chokidar 2 does not receive security updates since 2019. Upgrade to chokidar 3 with 15x fewer dependencies

    added 371 packages, and audited 372 packages in 19s

    36 packages are looking for funding
      run `npm fund` for details

    4 high severity vulnerabilities

    To address all issues (including breaking changes), run:
      npm audit fix --force

    Run `npm audit` for details.

# 替换 openai api_key
进入到 src 目录，使用文本编辑软件，比如  记事本，打开config.js ,替换api_key，保存文件。
![image](https://user-images.githubusercontent.com/33740652/224201314-3bb47e42-9dd9-4078-8fe1-3abbea058b10.png)
到openai 官网api页面，https://platform.openai.com/account/api-keys 生成并复制你的api_key，替换为你的api_key
![image](https://user-images.githubusercontent.com/33740652/224201494-ad04a146-535c-4b2b-acc8-7ba756d44acb.png)


# 运行
双击运行 run.bat 文件启动服务。
运行时，会一直占用此终端窗口，可以按键盘 q 或者 Ctrl + C 取消运行。
![image](https://user-images.githubusercontent.com/33740652/224207705-4ed912b6-a5be-476c-8bd3-e35b6685a18e.png)


![image](https://user-images.githubusercontent.com/33740652/224197733-c2586a74-708c-445e-a91c-27004f8194e9.png)

# 访问
在浏览器输入 http://localhost:5173
![image](https://user-images.githubusercontent.com/33740652/224202980-5e4329e6-f1eb-4124-8cbe-388876fea698.png)


# 可能出现的情况

安装react
    
    npm install react react-dom
如果出现报错，同样可以忽略。
