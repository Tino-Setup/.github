<p align="center">
  <img style="width: auto; max-width: 50%; height: auto;" alt="Tino Setup logo" src="Tino Setup.png">
</p>

<h1 align="center">Tino Setup</h1>
<h3 align="center"><em>The GUI Setup for Linux — Create professional installers & uninstallers for your applications</em></h3>

---

**Tino Setup** is a complete installation framework for Linux desktop applications. It brings the simplicity and polish of Windows installers to the Linux ecosystem.

The suite consists of three components that work together:

| Component | Role |
|-----------|------|
| **[Tino Wizard](Wizard/)** | The developer tool — design and build installers via a GUI |
| **[Tino Installer](Wizard/Installer/)** | The end-user installer engine — guided graphical installation |
| **[Tino Uninstaller](Wizard/Uninstaller/)** | The end-user uninstaller — clean graphical removal |

---

### 🔄 How It Works

```
Developer                          End-User
────────                          ────────
                                  
Tino Wizard                       YourApp Setup
    │                                 │
    ├── Configure project             ├── Welcome & License
    ├── Add files & metadata          ├── Select additional tasks
    ├── Set desktop integration       ├── Extract & copy files
    └── Build ──────────────────►     ├── Create shortcuts
                                      └── Place uninstaller
                                  
                                  YourApp-Uninstaller
                                      │
                                      ├── Confirm removal
                                      ├── Remove files & shortcuts
                                      └── Done
```

---

### 📄 License

GNU GPL-3.0 License — See individual component license files for details.

Made with ❤️ for the Linux community.
