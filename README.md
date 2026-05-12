# TempMail Telegram Bot on Vercel

This bot gives you a disposable email address directly inside Telegram.  
It uses [Guerrillamail](https://www.guerrillamail.com/) as backend and stores user sessions in Upstash Redis.

## Deployment

### 1. Prerequisites
- [Vercel CLI](https://vercel.com/cli) (optional) or GitHub integration
- A Telegram bot token from [@BotFather](https://t.me/BotFather)
- An Upstash Redis database (free tier) – get URL from [upstash.com](https://upstash.com)

### 2. Environment Variables
Set these in Vercel project settings:
- `TELEGRAM_BOT_TOKEN` – your bot token
- `REDIS_URL` – example: `redis://default:abc123@redis-12345.upstash.io:6379`

### 3. Deploy to Vercel
```bash
vercel