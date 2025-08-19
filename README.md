# ShopTool

**ShopTool** is an internal production utility from [Flint Creek Woodworks](https://flintcreekwoodworks.com) that streamlines cabinet-shop workflows, manages job data, and integrates with Trello and Mozaik.

This **public repository** is used for:
- 🐞 **Issue tracking** (bugs & feature requests)
- 📚 **Documentation** for users and admins

> ⚠️ The application **source code is not included** here. Development happens in a private repo.

---

## 📦 Downloads

Get the latest Windows build from **[Releases](../../releases)**.

**System requirements**
- Windows 10/11 (64-bit)
- No admin needed; portable binary

**Install / Run**
1. Download the `ShopTool-<version>-win64.zip` from Releases.
2. Unzip anywhere (e.g., `C:\Tools\ShopTool`).
3. Run `ShopTool.exe`.

**Where data lives**
- Settings:  
  `%LOCALAPPDATA%\ShopTool\settings.json`
- Logs (useful for troubleshooting):  
  `%LOCALAPPDATA%\ShopTool\logs\shoptool.log`

---

## 🧾 Reporting Issues

1. Open **[Issues](../../issues)** → **New issue**.
2. Pick a template (Bug / Feature).
3. Include:
   - **Version** (see *About* in the app, e.g., `2.0.0`)
   - **Steps to reproduce**
   - **Expected vs. actual**
   - **Relevant logs** (attach `shoptool.log`)
   - Optional: sample files (redact sensitive data)

> 🔐 **Redact secrets** (API keys, tokens, customer info) before attaching logs or screenshots.

---

## 💬 Support

Have a question that isn’t a bug or feature request? Use **[Discussions](../../discussions)**.

---

## 🗺️ Release Notes & Roadmap

- Changelogs are on **[Releases](../../releases)** (e.g., *v2.0.0 — First Stable*).
- High-level plans are tracked via pinned issues or discussions.

---

## 🔒 Privacy & Access

ShopTool is proprietary software for internal use at Flint Creek Woodworks.  
This repo is public to enable transparent issue tracking and docs; **source code is not open-sourced**.

---

## 📜 License

Documentation and issue templates in this repository are licensed under **MIT**.  
The ShopTool **application** remains proprietary and is **not** covered by this MIT license.

See [LICENSE](LICENSE) for details.
