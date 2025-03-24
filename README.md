## ⚠️ IMPORTANT
> Before using this launcher, please **turn off Real-Time Protection** or **whitelist the folder** containing the launcher in your antivirus. Rest assured, this launcher is **COMPLETELY SAFE** and does **not** steal personal information.

---

## 🌟 Features
- **Auto Download/Update**: Fetches the latest release from GitHub (`https://github.com/Scaredtzt/Repo`).
- **Auto Inject**: Injects the specified DLL into the game process automatically.
- **Steam & Cracked Support**: Compatible with both Steam (AppID: 3241660) and standalone REPO.exe.
- **Command Line Interface**: Advanced control via CLI (e.g., `inject`, `kill`, `restart`).
- **GUI Configuration**: Easy setup with a graphical interface on first run.
- ~~**Mica Effect**: Modern Windows UI with Mica transparency (Windows 11)~~.
- **Customizable**: Configurable via `config.json` or GUI (auto-inject, wait time, etc.).

---

## ❓ How to Use
1. Download the latest release from the link below.
2. Extract `S.C.A.R.E.D Launcher.exe` to a new folder.
3. Run the executable:
   - **First Run**: A GUI will prompt you to set the game path (`REPO.exe`) and DLL path (`scared_cheat.dll`).
   - **Subsequent Runs**: Auto-downloads updates and injects if configured.
4. Use commands (e.g., `inject 5`) for manual control if needed.

---

## 📋 Commands
- `inject [time] [--force]`: Inject the DLL after `[time]` seconds; `--force` overrides auto-inject restrictions.
- `kill`: Terminate the REPO process.
- `restart [time]`: Kill and restart the game with an optional delay.
- `auto_inject [true/false] [time]`: Toggle auto-injection and set wait time.
- `inject_wait_time`: Open GUI to set injection delay.
- `status`: Show current configuration and game status.
- `download_dll <url>`: Download a DLL from a specified URL.
- `help`: Display this list.

---

## 🙅 Disclaimer
This is an **automated launcher**. Any injection failures are due to the injector (`smi.exe`) or DLL (`scared_cheat.dll`), not the launcher itself. We only take responsibility for launcher-specific errors.

---

## 📜 License
MIT License - See [LICENSE](LICENSE) for details.

---

**Made by 21Scared**
