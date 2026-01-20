
## 5. Updated README.md (Hiring Gold)
```markdown
# Windows USB Lockdown Solution (.reg Files)

[![Endpoints](https://img.shields.io/badge/Deployed-100%2B_Corporate-red)](https://github.com/faraimushipe/windows-usb-lockdown)

## 💼 Real Corporate Deployment
**Problem:** Executives bypassing AV with infected USBs → 12 malware incidents/month

**Solution:** Double-click .reg files → Reboot → Zero USB storage access

## 🎯 3-Tier Strategy
| Tier | File | Effect | Use Case |
|------|------|--------|----------|
| **Full Block** | `01-usb-block.reg` | No USB storage | Standard users |
| **Read-Only** | `02-usb-readonly.reg` | Read but no copy | Executives |
| **Emergency** | `03-usb-unblock.reg` | Full restore | IT Support |

## 📈 Impact @ Inclusive Financial Services
👥 100+ endpoints secured
📉 100% malware reduction (6 months)
⚡ 30-second deployment
🔄 Reversible for emergencies