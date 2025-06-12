# JSTechTools

A free, open-source Windows utility toolkit for IT technicians. JSTechTools combines essential remote system management functions into a single, easy-to-use interface — saving you time when managing devices on a Windows domain.

---

## 🔧 Features

✔️ **Ping and Traceroute**
- Quickly test network connectivity and path tracing to remote machines.

✔️ **Remote Tools**
- Retrieve uptime, OS details, hard drive space, network adapters, and running processes.
- Start, stop, or restart services remotely.
- Query System and Application Event Logs.
- Renew IP addresses on remote systems.

✔️ **Profile Management**
- List user profiles on remote devices.
- Run **Delprof2** to delete remote profiles:
  - Delete all profiles quietly.
  - Prompt before deletion.
  - Delete profiles older than 30 days.
- All Delprof2 output is captured in-app for logging and troubleshooting.

✔️ **Port Scanner**
- Scan for open TCP ports on a target machine within a specified range.

✔️ **DNS Lookup**
- Perform quick DNS resolution lookups for a given hostname or IP.

✔️ **Dark Mode Toggle**
- Switch between light and dark UI themes.

✔️ **Resizable Form Lock**
- Fixed window sizing for a clean, consistent interface.

---

## ⚠️ Requirements

- **Windows 10/11**
- **.NET 8.0 Runtime**
- **Domain Administrator privileges** for most remote management features (e.g. service control, Delprof2 profile management).

---

## 🚀 How to Use

1. **Download the release build or clone the repository.**
2. **Run `JSTechTools.exe`** from the `bin/Release/net8.0-windows` folder or your chosen install path.
3. **Run as Administrator** to unlock remote administrative functions.
4. Use the navigation buttons to access different tools.
5. View all command output in the **ConsoleOutput** textbox for easy review.

---

## 📦 Packaging / Deployment

- The application can be distributed as a **portable executable**.
- To build:
  - Open in Visual Studio 2022+
  - Set `Release` configuration
  - Build solution
  - Copy the `bin/Release/net8.0-windows` folder and deploy.

---

## 📜 License

MIT License — free for personal and commercial use. Attribution appreciated but not required.

---

## 🤝 Contributions

Suggestions, issues, and improvements are welcome! Submit a pull request or open an issue via GitHub.

---

## 🙏 Acknowledgements

- **Delprof2** by Helge Klein — included for profile management.
- .NET and Windows Management Instrumentation (WMI)
- Community contributions welcome!

---

**Built by Jamie Stevens for the IT support community.**
