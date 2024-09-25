# One-Liner-Disable-Enable-Gatekeeper-macOS-Sequoia
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
