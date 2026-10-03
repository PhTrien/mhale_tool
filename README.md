# MHALE TOOL

<p align="center">
  <img src="https://github.com/user-attachments/assets/ee9ad0ca-3ee1-4458-bdb7-93cba11530f0" width="180" alt="MHALE TOOL Logo">
</p>

<p align="center">
  <b>Bộ công cụ tiện ích đa năng dành cho Windows 10 & Windows 11</b><br>
  Tối ưu hệ thống • Sao lưu dữ liệu • Cài đặt phần mềm • Sửa lỗi máy in • Quản lý BitLocker
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-blue?style=flat-square" alt="Platform">
  <img src="https://img.shields.io/badge/Python-3.8%2B-yellow?style=flat-square" alt="Python">
  <img src="https://img.shields.io/badge/GUI-PyQt5-green?style=flat-square" alt="GUI">
  <img src="https://img.shields.io/badge/License-BSL--1.0-orange?style=flat-square" alt="License">
</p>

---

## Giới thiệu

**MHALE TOOL** là bộ công cụ tích hợp nhiều tiện ích hữu ích giúp người dùng Việt Nam dễ dàng:

- Theo dõi thông tin phần cứng real-time
- Tối ưu và thiết lập Windows nhanh chóng
- Cài đặt Microsoft Office chính hãng
- Sao lưu WiFi, Driver, Dữ liệu cá nhân
- Sửa lỗi máy in & mạng LAN
- Quản lý BitLocker an toàn
- Cài đặt Microsoft Store cho Windows LTSC
- Kho driver Intel RST / VMD
- Gỡ bỏ bloatware & phần mềm rác

Giao diện hiện đại, tiếng Việt 100%, hỗ trợ tray icon và chạy ẩn console.

---

## Tính năng chính

### Hệ thống
| Tính năng | Mô tả |
|---------|------|
| **Thông tin máy tính** | Giám sát CPU, RAM, GPU, Ổ cứng, Pin real-time. Xuất Excel/CSV |
| **Thiết lập Windows** | Tối ưu File Explorer, Power Plan, đồng bộ thời gian NTP, chuẩn hóa ngày giờ Việt Nam |
| **Thiết lập Office** | Cấu hình chuẩn công văn (NĐ 30), font, căn lề, Normal.dotm |
| **Quản lý BitLocker** | Bật/tắt, khóa/mở khóa, tạm dừng bảo vệ, xuất Recovery Key 48 số |

### Sao lưu - Khôi phục
- **Sao lưu WiFi**: Lưu mật khẩu và cấu hình mạng đã kết nối
- **Sao lưu Driver**: Sao lưu toàn bộ DriverStore + OEM (hơn 800 driver)
- **Sao lưu Dữ liệu**: Desktop, Documents, Downloads, Pictures, Videos, Fonts, trình duyệt...

### Cài đặt
- **Kho ứng dụng**: Cài tự động Chrome, Cốc Cốc, 7-Zip, WinRAR, .NET, VLC, Notepad++, TeamViewer...
- **Cài đặt Office**: Hỗ trợ Office 2016 → 2025 / Microsoft 365 (64-bit & 32-bit)
- **Kho ISO**: Windows 10/11 (Consumer + LTSC), Ubuntu Desktop & Server + Autounattend
- **Thiết lập máy in**: Sửa lỗi Spooler, chia sẻ máy in, lỗi 0x... phổ biến

### Tiện ích khác
- **Zalo Tool**: Chạy nhiều tài khoản Zalo trên cùng máy (mỗi user Windows riêng)
- **Xóa / Gỡ phần mềm rác**: Gỡ bloatware Windows, 360, AVG, BKAV, McAfee, WPS...
- **Store cho Win LTSC**: Cài Microsoft Store + Xbox cho Windows 10/11 LTSC
- **Kho Driver IRST**: Driver Intel RST / VMD từ v15.x → v20.x (WHQL)

---

## Giao diện

| Module | Screenshot |
|--------|----------|
| Thông tin máy tính | ![Thông tin máy tính](https://github.com/user-attachments/assets/612b2594-d982-4449-adf7-595dfb0761bf) |
| Thiết lập Windows | ![Thiết lập Windows](https://github.com/user-attachments/assets/2ee31e53-e817-47ea-8ccc-7b95e56da000) |
| Cài đặt Office | ![Cài đặt Office](https://github.com/user-attachments/assets/df8c2367-d2c1-4ac5-902b-2b2c5da78e47) |
| Kho ISO | ![Kho ISO](https://github.com/user-attachments/assets/79fc9155-b3fa-4c15-88ba-349ed8d28938) |
| Quản lý BitLocker | ![BitLocker](https://github.com/user-attachments/assets/7b70fd36-1ef7-4f60-a604-5c1daa0171ea) |
| Tray Menu | ![Tray Menu](https://github.com/user-attachments/assets/06161577-0289-4104-9fe2-585c5d636532) |

---

## Yêu cầu hệ thống

- Windows 10 / Windows 11 (64-bit khuyến nghị)
- Python 3.8 trở lên (nếu chạy từ source)
- Quyền Administrator (một số chức năng cần)

---

## Cài đặt & Sử dụng

### Cách 1: Chạy bản đóng gói (Khuyến nghị)
1. Tải bản phát hành mới nhất từ [Releases](https://github.com/PhTrien/mhale_tool/releases)
2. Giải nén và chạy `MHALE TOOL.exe`
3. Cho phép quyền Administrator khi được hỏi

### Cách 2: Chạy từ mã nguồn
```bash
# Clone repository
git clone https://github.com/PhTrien/mhale_tool.git
cd mhale_tool

# Cài đặt thư viện
pip install -r requirements.txt

# Chạy ứng dụng
python tool.py
