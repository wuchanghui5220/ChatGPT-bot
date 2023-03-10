# ChatGPT-bot

# 前提 
安装Node.js。可以从Node.js官网 https://nodejs.org/en/download/ 下载适合您系统的安装程序。在运行安装程序时，需要跟随安装向导的指导完成安装。

打开CMD终端，验证node.j是否安装成功。

验证node

    C:\Users\wucha>node -v
    v18.14.2
验证npm

    C:\Users\wucha>npm -v
    9.6.0
 
# 安装ChatGPT-bot
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



![image](https://user-images.githubusercontent.com/33740652/224197733-c2586a74-708c-445e-a91c-27004f8194e9.png)

# 运行
    C:\Users\wucha\ChatGPT-bot>npm run dev

    > app@0.0.0 dev
    > vite


      VITE v4.1.4  ready in 929 ms

      ➜  Local:   http://localhost:5173/
      ➜  Network: use --host to expose
      ➜  press h to show help
