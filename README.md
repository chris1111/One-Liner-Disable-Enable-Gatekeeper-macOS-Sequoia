# One-Liner-Disable-Enable-Gatekeeper-macOS-Sequoia
- After using the command, system will shutdown in 10 secounds. Restart the Machine to take effect.

- [x] `Disable Gatekeeper:`
```bash
sudo defaults write /var/db/SystemPolicyConfiguration/SystemPolicy-prefs.plist enabled -string no && sudo shutdown -h +10s
```

After the Restart macOS Sequoia System

![Anywhere](https://github.com/user-attachments/assets/3fac82d6-8f87-43dc-b4a7-ed5f540c4fbc)



- [x] `Enable Gatekeeper:`
```bash
sudo defaults write /var/db/SystemPolicyConfiguration/SystemPolicy-prefs.plist enabled -string yes && sudo shutdown -h +10s
```

After the Restart macOS Sequoia System

![Enable](https://github.com/user-attachments/assets/b34ddd9e-02f4-43c1-988d-cf331a0b8668)
