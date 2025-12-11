# 📚 ArduinoCore-API for STM32duino

Fork of [`arduino/ArduinoCore-API`](https://github.com/arduino/ArduinoCore-API)  
Designed to be used as a git submodule in [`stm32duino/Arduino_Core_STM32`](https://github.com/stm32duino/Arduino_Core_STM32)

---

## 🎯 Purpose

This repository is a fork which reworks the folder structure to contain only the official Arduino API and hardware‑independent code, in order to simplify Arduino API integration into STM32duino via a git submodule.

It will also contain some updates/changes/enhancements/fixes.

---

## 📦 What's Included?

- ✅ Official Arduino API files (`api/` folder)
- ✅ some updates, changes, enhancements and fixes.

---

## 🚀 Submodule usage

### 1️⃣ Add the Submodule

In the `Arduino_Core_STM32` repository, run:

```bash

git submodule add https://github.com/stm32duino/ArduinoCore-API.git cores/arduino/api
```
### 2️⃣ Initialize and update
```bash
git submodule update --init 
```

---

## 🔗 Official Resources

| Resource | Link |
|----------|------|
| **Official ArduinoCore-API** | https://github.com/arduino/ArduinoCore-API |
| **STM32duino** | https://github.com/stm32duino/Arduino_Core_STM32 |

---

## 📝 License

This repository is a fork of `arduino/ArduinoCore-API` and maintains the **same license** (LGPL 2.1+).

See the [LICENSE](License) file in the repository root for details.

---

## 💡 Important Notes

### ✅ Advantages of Using a Submodule

- **Traceability**: Know exactly which version of the API you're using
- **Easy Updates**: Simple `git submodule update` to sync
- **Isolation**: API stays in its own code branch
- **Compatibility**: STM32-specific modifications remain separate

### ⚠️ Points to Consider

- After cloning **Arduino_Core_STM32**, run:
  ```bash
  git submodule update --init --recursive
  ```

---

## 📊 Project Information

| Property | Value |
|----------|-------|
| **Type** | fork |
| **Use Case** | Submodule for STM32duino |
| **Language** | C/C++ |
| **License** | LGPL 2.1+ |
| **Original Repository** | https://github.com/arduino/ArduinoCore-API |
---

## ✨ Quick Start

### Clone **Arduino_Core_STM32** with this submodule

```bash
git clone --recurse-submodules https://github.com/stm32duino/Arduino_Core_STM32.git
```

### Update submodule

```bash
git submodule update --remote
```

---