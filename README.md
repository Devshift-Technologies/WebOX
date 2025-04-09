# Webox

Webox is a web-based hypervisor platform that allows users to create and manage virtual machines directly from their browser. It offers customizable configurations including CPU, RAM, GPU, and storage — all backed by a powerful custom hypervisor backend and modern web technologies.

---

## 🚀 Features

- 🧠 Custom hypervisor backend (not using QEMU, libvirt, or Proxmox)
- 🖥️ VM creation via browser with a clean interface
- 🧩 Choose between:
  - **CPU**: 2–36 cores
  - **RAM**: 2–86 GB
  - **GPU**: Optional GeForce RTX 5090 D passthrough
  - **Storage**: 260GB dynamic VHD
- 🎮 GPU drivers preinstalled on VM boot
- 🔐 Admin/subscriber-only full access
- 🆓 Free version for regular users (ISO boot only)

---

## 🌐 Who Can Use It?

| Type                        | Features                                              |
| --------------------------- | ----------------------------------------------------- |
| Admins / Update Subscribers | Full access to VM customization (CPU, RAM, GPU, etc.) |
| Regular Users               | ISO upload + VM creation only (free tier)             |

Subscribe by entering your email through the contact form to unlock full features.

---

## 🛠️ Tech Stack

- **Frontend**: TypeScript, Next.js, TSX
- **Backend**: Supabase, custom hypervisor backend, Azure cloud
- **Storage**: Dynamic 260GB VHDs
- **GPU Support**: GeForce RTX 5090 D with preloaded drivers
- **Virtual CPU**: AMD EPYC vCPUs with SVM / AMD-V emulation
- **Optional**: WASM for frontend-side detection and CPU feature routing

---

## ⚙️ Setup (Coming Soon)

The setup guide will include:

- How to run the frontend locally
- Prebuilding ISO with boot scripts
- Running the backend hypervisor engine
- Creating and booting VMs through Webox

> Currently in development.

---

## 📫 Contact

Want to contribute, test, or partner with us?

- Email: [[YourEmail@example.com](mailto\:alexmum@devhshift.tech)]
- Project Lead: [Alexander Mummert]

---

## 🤝 Contributing

Contributions are welcome! Stay tuned for our contributing guidelines and issue tracker.

---

## 📜 License

This project is under development. License details coming soon.



# Dedicated Supporters

## 1. GPUMart
