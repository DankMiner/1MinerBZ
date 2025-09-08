# BZMiner Warthog Wrapper for 1Miner.net

A professional Windows GUI wrapper for BZMiner, specifically designed for mining Warthog (WART) cryptocurrency on 1Miner.net pools. Features a modern interface with multi-language support and real-time monitoring.

![License](https://img.shields.io/badge/license-Proprietary-red.svg)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)
![Language](https://img.shields.io/badge/languages-9-blue.svg)

## 🚀 Features

- **Integrated BZMiner** - Comes with BZMiner built-in, no separate downloads needed
- **Multi-Language Support** - Available in 9 languages: English, Spanish, Chinese, Korean, Russian, Arabic, French, German, Portuguese
- **Real-Time Monitoring** - Live hashrate, temperature, power consumption, and efficiency statistics
- **Dual Mining Modes** - Support for both PPLNS and SOLO mining
- **Global Server Network** - 10 server locations worldwide
- **SSL Encryption** - Optional secure connections for all pools
- **Dark/Light Theme** - Comfortable viewing in any lighting condition
- **Compact Interface** - Everything fits on one screen for easy monitoring
- **Configuration Persistence** - Save and load your mining configurations

## 📋 System Requirements

- **OS**: Windows 10/11 (64-bit)
- **GPU**: NVIDIA or AMD GPU with Warthog mining support
- **RAM**: 4GB minimum
- **Storage**: 100MB free space
- **Network**: Stable internet connection
- **Wallet**: Valid Warthog (WART) wallet address

## 💾 Installation

1. Download `BZMiner-Warthog-Wrapper-v1.0.0.zip` from [Releases](https://github.com/yourusername/bzminer-wrapper/releases)
2. Extract the ZIP file to your desired location (e.g., `C:\BZMiner-Wrapper\`)
3. Run `BZMiner Wrapper Setup 1.0.0`
4. Configure your wallet address and preferred settings
5. Click "START" to begin mining

**Note**: Windows may show a security warning on first run. Click "More info" → "Run anyway" to proceed.

## ⚙️ Quick Start Guide

### Step 1: Enter Your Wallet
- Paste your Warthog wallet address in the "Wallet Address" field
- Set a worker name (default: rig1)

### Step 2: Choose Mining Mode
- **PPLNS**: Recommended for steady, predictable rewards
- **SOLO**: Try your luck at finding full blocks (higher risk/reward)

### Step 3: Select Pool Server
- Choose the server closest to your location for best latency
- Enable SSL for encrypted connection (optional)

### Step 4: Start Mining
- Click the green "START" button
- Monitor your stats in real-time
- Console shows detailed miner output

## 🌍 Available Mining Pools

### PPLNS Pools
- 🇺🇸 USA Central (Missouri)
- 🇺🇸 USA East (New York)
- 🇺🇸 USA West (Washington)
- 🇺🇸 USA South (Texas)
- 🇸🇬 Asia (Singapore)
- 🇨🇳 China (Hong Kong)
- 🇯🇵 Japan (Tokyo)
- 🇦🇺 Australia (Sydney)
- 🇫🇷 Europe (France)
- 🇬🇧 Europe (UK)

### SOLO Pools
Same locations available for SOLO mining

## 🌐 Language Support

Change language from the dropdown in the top-right corner:

- 🇺🇸 English
- 🇪🇸 Español
- 🇨🇳 中文
- 🇰🇷 한국어
- 🇷🇺 Русский
- 🇸🇦 عربي
- 🇫🇷 Français
- 🇩🇪 Deutsch
- 🇧🇷 Português

## 📊 Understanding the Statistics

| Stat | Description |
|------|-------------|
| **Hashrate** | Your current mining speed (H/s, KH/s, MH/s) |
| **Accepted** | Successfully submitted shares |
| **Rejected** | Failed shares (should be < 1%) |
| **Temp** | GPU temperature in Celsius |
| **Power** | Current power consumption in watts |
| **Efficiency** | Hashrate per watt ratio |
| **Mode** | Current mining mode (PPLNS/SOLO) |
| **Uptime** | How long you've been mining |

## 🔧 Advanced Settings

Click "Advanced ▼" to access:

- **GPU Selection**: Specify GPUs (e.g., "0,1,2" or leave empty for all)
- **Intensity**: Mining intensity (1-100, higher = more power)
- **Temp Limit**: Auto-throttle if GPU exceeds this temperature
- **Power Limit**: Maximum power consumption per GPU
- **Extra Params**: Additional BZMiner command-line parameters

## 💡 Tips for Best Performance

1. **Update GPU Drivers**: Always use the latest drivers from NVIDIA/AMD
2. **Monitor Temperature**: Keep GPUs below 75°C for longevity
3. **Start Conservative**: Begin with lower intensity and increase gradually
4. **Use Closest Server**: Select the pool server with lowest ping
5. **Enable SSL**: Use encrypted connections when on public networks
6. **Save Configuration**: Save working configs for quick switching

## ⚠️ Troubleshooting

### Wrapper won't start
- Check antivirus/Windows Defender isn't blocking it
- Run as Administrator
- Ensure .NET Framework is installed

### No hashrate showing
- Verify wallet address is correct
- Check GPU is recognized (update drivers)
- Try different pool server
- Disable Windows GPU scheduling

### High rejection rate
- Select closer server location
- Check internet stability
- Reduce overclock settings
- Update mining software

### Low hashrate
- Close other GPU-intensive programs
- Check power settings (set to High Performance)
- Ensure adequate cooling
- Verify GPU isn't thermal throttling

## 🔐 Security Notes

- **Never share** your wallet's private keys/seed phrase
- **Only enter** your public wallet address
- **Verify** pool addresses match those listed above
- **Use SSL** when mining on public/shared networks
- **Monitor** for unusual activity or hashrate drops

## 📊 Pool Information

- **Pool Fee**: 0.9% (PPLNS) / 1% (SOLO)
- **Minimum Payout**: 0.1 WART
- **Payment Schedule**: Every 2 hours
- **Block Time**: ~15 seconds
- **Network**: Warthog mainnet

## ❓ Frequently Asked Questions

**Q: Is this safe to use?**
A: Yes, the wrapper only controls BZMiner and doesn't access your wallet keys.

**Q: Why is my antivirus flagging it?**
A: Mining software is often falsely flagged. Add an exception for the folder.

**Q: Can I mine other coins?**
A: This wrapper is specifically optimized for Warthog only.

**Q: Does it work with integrated graphics?**
A: No, a dedicated GPU is required for mining.

**Q: Can I run multiple instances?**
A: Yes, but ensure each uses different GPUs and worker names.

## 📞 Support

- **Discord**: [Join our community](https://discord.gg/ZyG3YKDCQQ)
- **Pool Website**: [1Miner.net](https://1miner.net)
- **Issues**: Create an issue on this GitHub repository

## ⚖️ Legal Disclaimer

This software is provided "as is", without warranty of any kind, express or implied. The authors assume no responsibility for damages or losses incurred from using this software. Users are responsible for complying with local laws and regulations regarding cryptocurrency mining.

## 🏆 Credits

- **BZMiner**: The underlying mining engine
- **1Miner.net**: Pool infrastructure
- **Warthog Network**: The cryptocurrency we're mining
- **Community**: For testing and feedback

---

**Version**: 1.0.0  
**Released**: 2025  
**Copyright**: © 2025 1Miner.Net. All rights reserved.
