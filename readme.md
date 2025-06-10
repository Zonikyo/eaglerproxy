# Eaglerproxy for Railway (SSL enabled)

Connects browser-based Eaglercraft clients (`wss://`) to your Minecraft server at smp.zonikyo.com:25565.

## Setup

1. Clone or fork this repo.
2. Place `eaglerproxy.jar` in the repo root.
3. Create a `certs/` folder with:
   - `privkey.pem`
   - `fullchain.pem`
4. Deploy on Railway or any Linux server:
   - Ensure `PORT=8080`
   - Run `./start.sh`
5. Point your Eaglercraft client to `wss://<YOUR_RAILWAY_URL>`

Enjoy! 🚀
