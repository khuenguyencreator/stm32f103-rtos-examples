# STM32F103 RTOS Examples

Code ví dụ **FreeRTOS** (CMSIS-RTOS v2) trên **STM32F103C8T6 (Blue Pill)**, project tạo bằng **STM32CubeIDE**. Mỗi thư mục là một bài trong series lập trình RTOS trên blog [khuenguyencreator.com](https://khuenguyencreator.com).

- MCU: STM32F103C8T6
- RTOS: FreeRTOS, giao diện CMSIS-RTOS v2 (cấu hình trong STM32CubeMX)
- IDE: STM32CubeIDE
- Nạp / debug: ST-Link

## Danh sách bài

| Project | Nội dung |
|---|---|
| [STM32_RTOS_CreateAndScheduleTask](STM32_RTOS_CreateAndScheduleTask) | Tạo task và cách scheduler lập lịch |
| [STM32_RTOS_TaskStates](STM32_RTOS_TaskStates) | Các trạng thái của task (Running, Ready, Blocked, Suspended) |
| [STM32_RTOS_Queue](STM32_RTOS_Queue) | Truyền dữ liệu giữa các task bằng Queue |
| [STM32_RTOS_Semaphore](STM32_RTOS_Semaphore) | Đồng bộ task bằng Semaphore |
| [STM32_RTOS_Mutex](STM32_RTOS_Mutex) | Bảo vệ tài nguyên dùng chung bằng Mutex |
| [STM32_RTOS_EventGroup](STM32_RTOS_EventGroup) | Đồng bộ nhiều sự kiện bằng Event Group |
| [STM32_RTOS_TaskNotifycation](STM32_RTOS_TaskNotifycation) | Task Notification |
| [STM32_RTOS_SoftwareTimer](STM32_RTOS_SoftwareTimer) | Software Timer |

## Cách sử dụng

1. Tải repo:
   ```bash
   git clone https://github.com/khuenguyencreator/stm32f103-rtos-examples.git
   ```
2. Mở STM32CubeIDE, chọn **File → Import → General → Existing Projects into Workspace**, trỏ tới thư mục project muốn chạy.
3. Build (Ctrl+B), cắm ST-Link rồi **Run / Debug**.
4. Cấu hình task, queue, semaphore… nằm trong file `.ioc` (mục Middleware → FREERTOS).

## Liên kết

- 📖 Bài viết hướng dẫn chi tiết: [khuenguyencreator.com](https://khuenguyencreator.com)
- 📚 Các repo khác: [github.com/khuenguyencreator](https://github.com/khuenguyencreator)

Nếu thấy hữu ích, hãy bấm ⭐ **Star** để ủng hộ nhé! Có lỗi hoặc thắc mắc, bạn tạo **Issue** trong repo này hoặc để lại bình luận trên blog.
