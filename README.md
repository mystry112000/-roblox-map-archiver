# MYSTERY!-ASSETS LEAK - Mystery Decompiling

<p align="center">
  <img src="https://img.shields.io/badge/Discord-MYSTERY!-7289DA?style=for-the-badge&logo=discord" alt="Discord" />
  <img src="https://img.shields.io/badge/Roblox-Exploit-orange?style=for-the-badge&logo=roblox" alt="Roblox" />
  <img src="https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua" alt="Lua" />
</p>

> **⚠️ FOR EDUCATIONAL PURPOSES ONLY - Use on games you own or have permission to test on.**

Mystery Decompiling is a powerful Roblox game debugging and decompiling suite AI-powered script cleaning via BetterDecompiler.

## 🔗 Discord Server
**Join our community:** [discord.gg/Mppf6wXe](https://discord.gg/Mppf6wXe)

**Developer:** mystry112000

---

## ✨ Features

- **Full Game Explorer** - Browse entire game hierarchy including Terrain, CSG objects (Unions, Negates), and nil instances
- **Properties Editor** - Edit any instance properties with full type support
- **AI Script Cleaner** - Integrates BetterDecompiler to clean and rename decompiled scripts using GPT-4o
- **Script Viewer** - View and analyze Lua/Luau scripts with syntax highlighting
- **Search System** - Advanced filtering with `isa=`, `remotes`, `rad(50)` support
- **Save Instances** - Export game assets and scripts locally

---

## 🎮 Supported Executors

| Executor | Status | Notes |
|----------|--------|-------|
| **Synapse X** | ✅ Full Support | Recommended |
| **Krnl** | ✅ Full Support | Free, reliable |
| **Fluxus** | ✅ Full Support | Free |
| **Script-Ware** | ✅ Full Support | |
| **Electron** | ✅ Full Support | |
| **Temple** | ✅ Full Support | |
| **Oxygen U** | ⚠️ Partial | Some features may not work |
| **Other compatible** | ⚠️ Try it | Needs `decompile`, `getnilinstances`, `getscriptbytecode` |

**Required Functions:**
- `decompile()` or `getscriptbytecode()`
- `readfile`, `writefile`, `makefolder`
- `getnilinstances` (recommended)
- `gethui` or `protect_gui` (recommended)

---

## 🚀 Quick Start

### Method 1: Loadstring (Easiest)
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/mystry112000/-roblox-map-archiver/main/mystery_decompiling.lua"))()
```

### Method 2: Local File
1. Download `mystery_decompiling.lua`
2. Put it in your executor's script folder
3. Load and execute

---

## 🤖 AI Script Cleaning Setup

Mystery Decompiling includes **BetterDecompiler** AI integration. To use it:

### Step 1: Start the AI Server
```bash
# Navigate to the project folder
cd /path/to/BetterDecompiler

# Install dependencies
pip install -r requirements.txt

# Start the AI server
python flask_ai_server.py
```

The server runs on `http://localhost:5000`

### Step 2: Use in Roblox
1. Load Mystery Decompiling in your executor
2. Open Script Viewer
3. Select any script
4. Click "Clean Script" to send to AI
5. Get cleaned, commented, and renamed code back!

**Note:** The AI server uses `g4f` (GPT4Free) with `gpt-4o` model. Internet connection required.

---

## 📖 How to Use

### Basic Navigation
1. **Explorer** - Shows all game instances (left panel by default)
2. **Properties** - Edit selected instance properties (right panel)
3. **Script Viewer** - View and clean scripts

### Keyboard Shortcuts
- `Ctrl+C` - Copy selected instances
- `Ctrl+V` - Paste instances
- `Ctrl+D` - Duplicate selected
- `Ctrl+Shift+V` - Paste into selected

### Search Filters
- `isa=Part` - Find all Parts
- `isa=RemoteEvent` or `remotes` - Find remotes
- `rad(50)` - Find instances within 50 studs
- `bindables` - Find BindableEvents/Functions
- Regular text - Search by name

---

## 🛡️ Safety & Usage Guidelines

### ⚠️ IMPORTANT DISCLAIMERS

1. **ONLY use on games you own or have explicit permission to test on**
2. **NEVER use on other players' games without permission**
3. **This tool is for LEARNING and DEBUGGING purposes**
4. **Developer is not responsible for misuse**

### Safety Tips
- ✅ Use in **local single-player** games or your own places
- ✅ Test in a **private server** you own
- ✅ Use for **learning Roblox scripting** and game structure
- ❌ Don't use on other people's games to steal assets
- ❌ Don't use to cheat or exploit in public servers

### Executor Safety
- Only use trusted executors from official sources
- Keep your antivirus active
- Don't run scripts from unknown sources
- This script is open-source - verify the code yourself!

---

## 📁 File Structure

```
-roblox-map-archiver/
├── README.md                          # This file
├── LICENSE                            # MIT License
├── mystery_decompiling.lua            # Main script (modified Dex + BetterDecompiler)
├── main.lua                          # BetterDecompiler entry point
├── flask_ai_server.py                # AI cleaning server (Python)
└── requirements.txt                   # Python dependencies
```

---

## 🏆 Credits

- **Developer:** mystry112000
- **Discord:** [discord.gg/Mppf6wXe](https://discord.gg/Mppf6wXe)


---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## ❓ Support & Community

- **Discord Server:** [discord.gg/Mppf6wXe](https://discord.gg/Mppf6wXe)
- **GitHub Issues:** [Report bugs here](https://github.com/mystry112000/-roblox-map-archiver/issues)
- **Developer Contact:** mystry112000

---

## ⚠️ FINAL WARNING

**By using this software, you agree that:**
1. You will only use it for educational/debugging purposes
2. You will NOT use it to steal or exploit other people's work
3. You understand this is a powerful tool that should be used responsibly
4. The developer is NOT responsible for any misuse of this software

**Stay safe, learn, and respect other developers' work! 🚀**
