### Hans-MD WhatsApp bot

A fun WhatsApp bot.

<h4 align="center"> ✔️ No Heroku Ban! ✔️</h4>
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&random=false&width=435&lines=The+five+boxing+wizards+jump+quickly" alt="Typing SVG" /></a>

<p align="center">
  <a href="https://telegra.ph/file/eb96c716a327862d66078.jpg">
    <img alt="Fance MD" height="400" src="https://telegra.ph/file/eb96c716a327862d66078.jpg">
  </a>
</p>
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=7000&pause=1000&color=7AF700&random=false&width=435&lines=%F0%9D%99%83%F0%9D%99%96%F0%9D%99%A3%F0%9D%99%A8-%F0%9D%99%88%F0%9D%99%99+%F0%9D%99%88%F0%9D%99%90%F0%9D%99%87%F0%9D%99%8F%F0%9D%99%84%F0%9D%99%81%F0%9D%99%90%F0%9D%99%89%F0%9D%98%BE%F0%9D%99%8F%F0%9D%99%84%F0%9D%99%8A%F0%9D%99%89%F0%9D%98%BC%F0%9D%99%87+%F0%9D%98%BD%F0%9D%99%8A%F0%9D%99%8F;Hans+Md+MULTIFUNCTIONAL+Bot+MD" alt="Typing SVG" /></a>
## Setup

1. Deploy on Heroku
   - Click [SCAN](https://qr-hazel-alpha.vercel.app/md) and scan the QR code through the "WhatsApp Linked Devices" option in your WhatsApp app.
   - You will get a session ID in WhatsApp, copy the ID only.
   - If you don't have an account on [Heroku](https://signup.heroku.com/), [create an account now](https://signup.heroku.com/).
   - If you don't have a GitHub account, [sign up](https://github.com/join) now.
   - [FORK](https://github.com/lyfe00011/whatsapp-bot-md/fork) this repository.
   - Now [DEPLOY](https://qr-hazel-alpha.vercel.app/heroku).

2. Deploy on Koyeb
   - Create an account on [Koyeb](https://app.koyeb.com/auth/signup). [Sign up now](https://app.koyeb.com/auth/signup).
   - Get [DATABASE_URL](https://github.com/lyfe00011/whatsapp-bot-md/wiki/DATABASE_URL). You'll need this while deploying.
   - Get [SESSION_ID](https://qr-hazel-alpha.vercel.app/md). Open Linked Devices in WhatsApp and [SCAN](https://qr-hazel-alpha.vercel.app/md) now.
   - Get the Koyeb API key. [Let's Go](https://app.koyeb.com/account/api).
   - [DEPLOY](https://qr-hazel-alpha.vercel.app/koyeb) now.
   - Enter [Environment Variables](https://github.com/lyfe00011/whatsapp-bot-md/wiki/Environment_Variables). [Read More](https://github.com/lyfe00011/whatsapp-bot-md/wiki/Environment_Variables).
   - Enter a name and click "Create Service."

3. Deploy on VPS or PC (Example here as in Ubuntu)

   - Install with script

         wget -N -O levanter.sh http://bit.ly/43JqREw && chmod +x levanter.sh && ./levanter.sh

   - Install without a script
       - Install git, ffmpeg, and curl:

             sudo apt -y update && sudo apt -y upgrade
             sudo apt -y install git ffmpeg curl

       - Install nodejs:

             sudo apt -y remove nodejs
             curl -fsSl https://deb.nodesource.com/setup_lts.x | sudo bash - && sudo apt -y install nodejs

       - Install yarn:

             npm install -g yarn

       - Install pm2:

             sudo yarn global add pm2

       - Clone the repository and install packages:

             git clone https://github.com/lyfe00011/whatsapp-bot-md botName
              cd botName
               yarn install --network-concurrency 1

       - Enter Environment Variables: Copy-paste the lines below (remove SESSION_ID if not needed):

             echo "SESSION_ID = Session_Id_you_Got_After_Scan_Dont_Add_This_Line_If_You_Can_Scan_From_Terminal_Itself
             PREFIX = .
             STICKER_PACKNAME = LyFE
             ALWAYS_ONLINE = false
             RMBG_KEY = null
             LANGUAG = en
             WARN_LIMIT = 3
             FORCE_LOGOUT = false
             BRAINSHOP = 159501,6pq8dPiYt7PdqHz3
             MAX_UPLOAD = 200
             REJECT_CALL = false
             SUDO = 989876543210
             TZ = Asia/Kolkata
             VPS = true
             AUTO_STATUS_VIEW = true
             SEND_READ = true
             AJOIN = true
             DISABLE_START_MESSAGE = false
             PERSONAL_MESSAGE = null" > config.env

    - [Read More](https://github.com/lyfe00011/whatsapp-bot-md/wiki/Environment_Variables)

    - Edit the `config.env` using nano if needed. To save, press `Ctrl + O`, then press `Enter`, and to exit, press `Ctrl + X`.

    - Start and stop the bot:
        - To start the bot: `pm2 start . --name botName --attach --time`
        - To stop the bot: `pm2 stop botName`

### By Harold Mth 

- [GITHUB](HTTPS://GITHUB.COM/HAROLDMTH)
- [WHATSAPP](HTTPS://Wa.me/237696900612?text=Hi+Harold) 
