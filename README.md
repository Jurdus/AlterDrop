# AlterDrop

**AlterDrop** is a lightweight Windows desktop application for sharing files over your local network — no internet required, no accounts, no hassle. Just launch the app, scan the QR code on any device, and start transferring files instantly.

---

## Features

- 📡 **Local network file sharing** — Hosts a lightweight web server so any device on the same Wi-Fi can upload or download files via a browser
- 📷 **QR code** — Instantly displays a scannable QR code linking to the web interface, no typing required
<img width="277" height="548" alt="image" src="https://github.com/user-attachments/assets/788341c6-8e28-4169-8746-69064fd6fd1a" />
<img width="308" height="548" alt="20260403_164857_946_IMG_8309" src="https://github.com/user-attachments/assets/acf4900e-d9d7-4034-9f21-0898e5b5a9d1" />


---

## Getting Started

### Requirements

- Windows 10 or later
- Both devices must be on the **same local network (Wi-Fi or LAN)**

### Installation

1. Download the latest release from the [Releases](https://github.com/Jurdus/AlterDrop/releases/tag/Release) page
2. Run the installer or extract the portable `.exe`
3. Launch **AlterDrop**

---

## Usage

1. **Launch AlterDrop** on your Windows PC
2. *(Optional)* Click **Select download directory** to choose where received files will be saved
3. *(Optional)* Change the **Port** if the default (`5000`) is in use, then click **Save** → **Apply**
4. The app displays the local address (e.g. `http://192.168.1.x:5000`) and a **QR code**
5. On your phone or another device, **scan the QR code** or manually enter the address in a browser
6. Use the web interface to **send or receive files**

---

## Settings

| Setting | Description |
|---|---|
| **Directory** | The local folder where uploaded files are saved |
| **Port** | The port the web server listens on (default: `5000`) |
| **Reset** | Revert settings to their last saved state |
| **Save** | Save the current settings |
| **Apply** | Apply changes and restart the server |

---

## Troubleshooting

**Can't connect from another device?**
- Make sure both devices are on the **same Wi-Fi or LAN**
- Check that your **Windows Firewall** allows AlterDrop or the configured port
- Try a different port if `5000` is blocked

**QR code not scanning?**
- Ensure you haven't changed the port without clicking **Apply**
- Confirm the IP shown (`http://192.168.x.x:PORT`) is reachable from the other device
