
# 🚀 **NiceHash Miner** – Maximize Your Crypto Mining Profitability

![GitHub release](https://img.shields.io/badge/release-v1.2.3-green?style=flat-square) ![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square) ![Platform](https://img.shields.io/badge/platform-Windows-blue?style=flat-square)

---

## 🔥 **Introduction**

NiceHash Miner represents seamless cryptocurrency mining, automatically selecting and running the most profitable algorithms.

![NiceHash Miner Interface](Resources/NHM_screenshot.PNG)

## 💡 **Key Benefits**
- 🚀 Automatic optimization
- 💻 One-click CPU/GPU setup
- ⚙️ Algorithm auto-switching
- 🔐 Full LHR unlock
- 📊 Real-time stats

## ✨ **Core Features**
- One-click mining
- Auto-benchmarking
- Crash protection
- Real-time analytics
- Automatic updates
- Intuitive UI

## 📋 **Requirements**
- Windows 10/11 (64-bit)
- CPU with AES support
- NVIDIA GPU (SM 5.3+) / AMD GPU (OpenCL)
- 60% paging file size of GPU VRAM
- Updated GPU drivers
- Stable internet connection

## 🛠️ **Installation & Setup**
- Download latest installer or zip.
- Run `NiceHashMiner.exe` or installer.
- Input your Bitcoin wallet.

**Note:** Requires `.NET Framework 6.0` and `Visual C++ Redistributable 2015`.

## 💰 **Profitability Explained**
Earn by selling your hardware hashing power through the NiceHash marketplace, supporting decentralized networks.

## 🔥 **Mine Only When Profitable**
Configure minimum profitability to optimize resource use and minimize costs.

## ⚙️ **Additional Options (configs\General.json)**
- **AutoStartMining**: auto-start at boot
- **MinimumProfit**: stop mining if below threshold
- **StartMiningWhenIdle**: mine when idle
- **DisplayCurrency**: preferred currency display
- **EnableSSLMining**: secured SSL mining
- **DebugConsole**, **LogToFile**, **AutoUpdateNiceHashMiner** and more

## 📌 **Benchmark settings (per device)**
Fine-tune mining algorithms:

```json
{
  "Name": "NBMiner",
  "PluginUUID": "03f80500-94ec-11ea-a64d-17be303ea466",
  "PluginVersion": "11.0",
  "AlgorithmIDs": "KAWPOW",
  "Speeds": [8841376.5],
  "ExtraLaunchParameters": "",
  "Enabled": true,
  "PowerUsage": 113.81
}
```

## 🛠️ **Troubleshooting**
- **GPU not detected**: Update NVIDIA/AMD drivers, verify GPU compatibility.
- **AMD driver issues**: Use Display Driver Uninstaller (DDU) for clean reinstalls.
- **Chrome blocking downloads**: Use Firefox/Edge instead.
- **Benchmark inaccuracies**: Manually adjust via config if automated benchmark fails.

## 🐞 **Reporting Issues**
Submit bug reports or feature requests through GitHub issues.

## 📥 **Downloads**
Latest releases [here](#). *(Links to be added)*

---

🌟 **Happy Mining with NiceHash Miner!** 🌟
