# 🚀 OpenClaw Social Scheduler

**Free, open-source social media scheduler built by AI, for AI**

Schedule posts to Discord, Reddit, and more - no monthly fees, no API limits beyond the platforms themselves.

## ✨ Features

- 📅 Schedule posts with precise timing (ISO 8601 format)
- 🔄 Automatic posting via scheduler daemon
- 🎯 Multi-platform support (Discord, Reddit, more coming!)
- 💾 Persistent queue (survives restarts)
- 🔁 Auto-retry logic (3 attempts)
- 🧹 Automatic cleanup of old posts
- 🧪 Full test suite
- 📖 Comprehensive documentation

## 🚀 Quick Start

```bash
# Install
cd skills/social-scheduler
npm install

# Test it works
npm test

# Post immediately
node scripts/post.js discord YOUR_WEBHOOK_URL "Hello OpenClaw! ✨"

# Schedule a post
node scripts/schedule.js add discord YOUR_WEBHOOK_URL "Future post!" "2026-02-03T09:00:00"

# Run scheduler daemon
node scripts/schedule.js daemon
```

## 📚 Documentation

- **[SKILL.md](SKILL.md)** - Complete usage guide
- **[PROJECT.md](PROJECT.md)** - Development roadmap

## 🎯 Supported Platforms

### ✅ Implemented
- **Discord** - Webhooks (easiest to set up!)
- **Reddit** - OAuth2 (posts & comments)

### 🚧 Coming Soon
- Twitter/X
- Mastodon
- Bluesky
- Moltbook
- LinkedIn
- Telegram

## 🤝 Contributing

Want to add a platform? Check out the existing implementations in `scripts/platforms/` for the pattern. PR's welcome!

## 📝 License

MIT - Built with ❤️ by Ori ✨ for the OpenClaw community

---

**Need help?** Check [SKILL.md](SKILL.md) for detailed setup guides and examples.
