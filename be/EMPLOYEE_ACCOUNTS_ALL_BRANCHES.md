# Tài khoản nhân viên (đủ tất cả chi nhánh)

File này dùng để tham khảo các tài khoản nhân viên mẫu theo từng chi nhánh.

- Mật khẩu mặc định: `123456`
- Mã chi nhánh (`branch_code`) được DataSeeder tự sinh theo format `CN01`, `CN02`, `CN03` (theo id chi nhánh).

## Danh sách tài khoản đề xuất

| Username | Vai trò (position) | Chi nhánh | Ghi chú |
|---|---|---|---|
| admin | ADMIN | (toàn hệ thống) | Admin xem toàn bộ lịch đặt |
| mgr1 | MANAGER | CN01 | Quản lý chi nhánh 1 |
| mgr2 | MANAGER | CN02 | Quản lý chi nhánh 2 |
| mgr3 | MANAGER | CN03 | Quản lý chi nhánh 3 |
| rec1 | RECEPTIONIST | CN01 | Lễ tân chi nhánh 1 |
| rec2 | RECEPTIONIST | CN02 | Lễ tân chi nhánh 2 |
| rec3 | RECEPTIONIST | CN03 | Lễ tân chi nhánh 3 |

## Gợi ý tạo dữ liệu

- Cách khuyến nghị: chạy backend để `DataSeeder` tự tạo/tự bổ sung tài khoản nếu thiếu.
- Nếu DB đã có nhân viên, DataSeeder sẽ không xoá dữ liệu cũ, chỉ bổ sung những tài khoản còn thiếu.
