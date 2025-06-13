# DX11 ImGui Overlay Hook

This project is a DirectX 11 DLL hook using ImGui for rendering custom in-game overlays.  
It is designed to inject a fully interactive menu into DX11 games.

---

## ✨ Features

- ✅ DirectX 11 internal hook (IDXGISwapChain)
- ✅ Fully integrated ImGui menu system
- ✅ Custom WndProc hook for input support
- ✅ Toggle menu with `VK_F2`
- ✅ Easy to inject & use
- ✅ Modular structure (Menu, Hook, Utils)

---

## 🧱 Requirements

- Visual Studio 2019 or newer
- Windows SDK
- DirectX SDK (June 2010 or included via Windows 10+ SDK)
- C++17 or higher

---

## 🔧 How to Build

1. Open the `.sln` project in Visual Studio.
2. Select **x64** and **Release** configuration.
3. Press `Ctrl + B` or click **Build > Build Solution**.
4. The final DLL will be in:  /Release/x64/dx11Hook.dll

---

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/484619e6-b5c1-49c6-ba01-982abb5dd5c0)


