# Quản Lý Nhân Viên

Ứng dụng web quản lý nhân viên sử dụng HTML, Bootstrap và API.

## Tính năng

- ✅ Hiển thị danh sách nhân viên
- ✅ Thêm nhân viên mới
- ✅ Cập nhật thông tin nhân viên
- ✅ Xóa nhân viên
- ✅ Tính toán tổng lương và xếp loại
- ✅ Thông báo trạng thái thao tác

## Công nghệ sử dụng

- HTML5
- Bootstrap 5
- JavaScript (ES6+)
- Font Awesome Icons
- API: https://svcy.myclass.vn/api/QuanLyNhanVien

## Cách sử dụng

1. Mở file `index.html` trong trình duyệt
2. Trang sẽ tự động tải danh sách nhân viên từ API
3. Sử dụng form để thêm/sửa nhân viên
4. Click các nút thao tác để sửa/xóa

## Cấu trúc dữ liệu

```json
{
  "taiKhoan": "string",
  "hoTen": "string", 
  "email": "string",
  "matKhau": "string",
  "luongCoBan": "number",
  "chucVu": "string",
  "gioLam": "number"
}
```

## Chức vụ và hệ số lương

- **Sếp**: Hệ số 3
- **Trưởng phòng**: Hệ số 2  
- **Nhân viên**: Hệ số 1

## Xếp loại theo giờ làm

- **Xuất sắc**: ≥ 192 giờ
- **Giỏi**: ≥ 176 giờ
- **Khá**: ≥ 160 giờ
- **Trung bình**: < 160 giờ
