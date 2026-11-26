# 🚀 Implementasikan-Inter-VLAN-Routing-dan-DHCP-untuk-jaringan-perkantoran (Cisco Packet Tracer)
# 🧠 Gambaran Umum
Lab ini mendemonstrasikan Inter-VLAN dan DHCP dengan menggunakan Cisco Packet Tracer.
Proyek ini mencakup:
- 🔁 Pembuatan VLAN pada switch.
- 🌐 Pengaktifan DHCP Server pada router.
- 💻 Komunikasi antar-PC dalam VLAN yang sama.
# 🖥️ Topologi
<img width="464" height="408" alt="Screenshot 2026-11-21 070355" src="https://github.com/user-attachments/assets/65122e5b-53ee-4f65-8657-6b7adb8bd1d3" />

# 🧪 Cara Pengujian
1. Buka PC mana pun dan pastikan:
- IP telah diberikan melalui DHCP
- Anda dapat melakukan ping ke PC lain sesuai dengan VLAN-nya.
2. Buka Router dan periksa:
- `show ip route`
# 📄 Catatan Konfigurasi
| ROUTER dan SWITCH |
| :--- |
| -> Konfigurasikan DHCP pada router |
| -> Konfigurasikan VLAN pada switch |
| -> Konfigurasikan trunk pada setiap switch yang terhubung ke switch lain atau ke router |
