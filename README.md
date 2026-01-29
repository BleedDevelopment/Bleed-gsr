# 🧪 bleed-gsr

Advanced Gunshot Residue (GSR) system for FiveM  
Built for **ESX**, **ox_lib**, and **ox_target**

---

## ✨ Features

### 🔫 GSR Detection
- GSR is applied **every 3 gunshots**
- Player receives a notification when GSR is applied
- GSR remains until:
  - Washed off in water
  - Automatically expires (configurable)

---

### 🚿 Washing GSR
- Press **E** while in water to wash GSR
- Works while:
  - Standing in water
  - Swimming
  - Underwater
- Circular progress bar (ox_lib)
- Hand washing animation when possible
- Splashing sound + wet-hands particle effect
- Washing **cancels if**:
  - Player leaves water
  - Player starts shooting
  - Player enters a vehicle

---

### 👮 Police GSR Testing
- **Third-eye (ox_target)** interaction on players
- Job & grade restricted
- Test animation for officer
- Synced hands-up animation for suspect
- Shows **POSITIVE / NEGATIVE** result
- **Cooldown per suspect** to prevent spam testing

---

### 🧾 Logging
- Logs every GSR test:
  - Officer name & ID
  - Suspect name & ID
  - Test result
  - Timestamp
- Logs print to server console
- Optional Discord webhook logging

---

## 📁 Resource Structure

