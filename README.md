# Windows 11 Clear (Home / Pro)

## Lightweight Windows 11 22H2 Build

---

# Tiếng Việt

## Giới thiệu

Windows 11 Clear là bản Windows 11 22H2 đã được tinh chỉnh nhằm giảm bớt ứng dụng rác, dịch vụ không cần thiết và một số tính năng nền của Windows để hệ thống hoạt động nhẹ hơn, ổn định hơn trên máy cấu hình thấp hoặc tầm trung.

Bản build hiện có:

* Windows 11 Clear Home
* Windows 11 Clear Pro

Mục tiêu của bản build:

* Giảm RAM nền
* Giảm tiến trình chạy ngầm
* Giảm ứng dụng mặc định không cần thiết
* Giữ lại trải nghiệm Windows 11 gần với bản gốc
* Vẫn đảm bảo tương thích phần mềm và game phổ thông

---

## Cấu hình đề nghị

### CPU

* Tối thiểu: 2 core 0.8GHz
* Tạm ổn: 2 core 1.2GHz
* Khuyến nghị: 2 core / 2 luồng 1.5GHz trở lên

### RAM

* Tối thiểu: 2GB
* Tạm ổn: 4GB
* Khuyến nghị: 8GB trở lên

### Ổ cứng

* Tối thiểu: SSD SATA 64GB
* Tạm ổn: SSD NVME 64GB
* Khuyến nghị: SSD NVME 128GB trở lên

---

## Những gì đã được tinh chỉnh

### Gỡ bớt ứng dụng mặc định

Một số ứng dụng UWP đã được loại bỏ để giảm tài nguyên nền và làm menu Start gọn hơn:

* Xbox Apps
* Clipchamp
* Microsoft Teams
* Bing News
* Bing Weather
* Your Phone
* Power Automate
* Feedback Hub
* Maps
* Alarms
* Camera
* Zune Music / Video
* Solitaire
* People
* To Do
* Windows Terminal
* và một số ứng dụng phụ khác

---

## Tối ưu hệ thống

Một số thành phần đã được giảm hoặc tắt:

* Telemetry
* Windows quảng cáo đề xuất
* Widgets / News
* Một số scheduled task nền
* Một số service ít dùng:

  * Fax
  * Remote Registry
  * Retail Demo
  * Geolocation
  * Offline Maps
  * Error Reporting
  * một số dịch vụ phụ khác

Windows Update không bị gỡ hoàn toàn nhưng đã được giảm hoạt động nền để hệ thống nhẹ hơn.

---

## Firefox được cài sẵn

Bản build có cài sẵn Mozilla Firefox để người dùng có thể sử dụng trình duyệt ngay sau khi cài Windows.

Điều này không phải quảng cáo. Firefox chỉ được chọn vì:

* nhẹ hơn trên nhiều máy yếu
* ít tiến trình nền hơn trong một số trường hợp
* dùng ổn định trên cấu hình thấp

Nếu muốn, bạn hoàn toàn có thể:

* gỡ Firefox
* cài Google Chrome
* hoặc dùng trình duyệt khác

---

## Lưu ý sau khi cài

Trên các máy ở mức tối thiểu hoặc một số máy cấu hình tạm ổn, sau khi vào desktop lần đầu có thể xuất hiện một cửa sổ CMD nhỏ chạy trong một khoảng thời gian ngắn.

Đây là script tối ưu hệ thống tự động:

* cấu hình page file theo RAM
* hoàn tất tối ưu service
* tắt một số task nền

Sau khi chạy xong cửa sổ sẽ tự đóng.

---

## Mức sử dụng RAM

Mức RAM sử dụng thực tế sẽ thay đổi tùy:

* dung lượng RAM vật lý
* driver
* ứng dụng nền
* máy ảo hoặc máy thật

Windows sẽ tự điều chỉnh cache và memory usage tùy cấu hình máy.

---

# English

## Introduction

Windows 11 Clear is a customized Windows 11 22H2 build designed to reduce unnecessary background apps, services, and system overhead while keeping the overall Windows 11 experience stable and familiar.

Available editions:

* Windows 11 Clear Home
* Windows 11 Clear Pro

Main goals:

* Lower idle RAM usage
* Reduce background processes
* Remove unnecessary bundled apps
* Keep good software compatibility
* Improve responsiveness on low-end hardware

---

## Recommended Hardware

### CPU

* Minimum: 2 cores 0.8GHz
* Decent: 2 cores 1.2GHz
* Recommended: 2 cores / 2 threads 1.5GHz or higher

### RAM

* Minimum: 2GB
* Decent: 4GB
* Recommended: 8GB or more

### Storage

* Minimum: 64GB SATA SSD
* Decent: 64GB NVME SSD
* Recommended: 128GB NVME SSD or higher

---

## Removed Applications

Several built-in UWP apps were removed to reduce background usage and clean up the Start menu:

* Xbox Apps
* Clipchamp
* Microsoft Teams
* Bing News
* Bing Weather
* Your Phone
* Power Automate
* Feedback Hub
* Maps
* Alarms
* Camera
* Zune Music / Video
* Solitaire
* People
* To Do
* Windows Terminal
* and several additional bundled apps

---

## System Optimizations

Some Windows features and background components were reduced or disabled:

* Telemetry
* Advertising suggestions
* Widgets / News
* Several scheduled tasks
* Some low-use services:

  * Fax
  * Remote Registry
  * Retail Demo
  * Geolocation
  * Offline Maps
  * Error Reporting
  * and several minor background services

Windows Update was not fully removed, but some background activity was reduced.

---

## Firefox Included

Mozilla Firefox is preinstalled so the system is ready to browse immediately after setup.

This is not an advertisement. Firefox was chosen because it is often:

* lighter on weaker hardware
* less aggressive with background usage in some cases
* stable for low-end systems

Users can still:

* uninstall Firefox
* install Google Chrome
* or use any other browser

---

## First Boot Notice

On minimum-spec systems or some mid-range systems, a small CMD window may briefly appear after reaching the desktop for the first time.

This is part of the automatic optimization script:

* configuring page file settings
* applying service tweaks
* disabling some background tasks

The window will close automatically after completion.

---

## RAM Usage

Actual RAM usage depends on:

* physical memory size
* drivers
* background software
* virtual machine or real hardware

Windows dynamically adjusts cache and memory usage depending on the system configuration.
