# DApp_Recycle

## Giới thiệu

DApp_Recycle là dự án xây dựng hệ thống ứng dụng phi tập trung (DApp) hỗ trợ việc quản lý và tái chế bằng công nghệ web hiện đại. Phần backend sử dụng NestJS - một framework Node.js tiên tiến giúp phát triển các ứng dụng server-side hiệu quả và dễ mở rộng, chủ yếu với TypeScript.

## Chức năng chính

- Cung cấp API cho các chức năng liên quan đến quản lý tái chế.
- Xây dựng kiến trúc backend hiện đại, dễ mở rộng và bảo trì.
- Sẵn sàng tích hợp với các nền tảng blockchain hoặc DApp frontend.

## Cài đặt và khởi chạy dự án

### Bước 1: Cài đặt thư viện

```bash
yarn install
```

### Bước 2: Khởi chạy dự án

- Chạy ở chế độ phát triển:
  ```bash
  yarn run start
  ```
- Chạy ở chế độ tự động reload:
  ```bash
  yarn run start:dev
  ```
- Chạy ở chế độ production:
  ```bash
  yarn run start:prod
  ```

Sau khi chạy, API sẽ hoạt động tại địa chỉ: `http://localhost:3001`

### Bước 3: Kiểm thử

- Test đơn vị:
  ```bash
  yarn run test
  ```
- Test end-to-end:
  ```bash
  yarn run test:e2e
  ```
- Kiểm tra độ phủ code:
  ```bash
  yarn run test:cov
  ```

## Triển khai

Bạn có thể triển khai ứng dụng NestJS lên các nền tảng đám mây như AWS thông qua [NestJS Mau](https://mau.nestjs.com). Tham khảo thêm tài liệu [deployment](https://docs.nestjs.com/deployment).

## Tài nguyên tham khảo

- [NestJS Documentation](https://docs.nestjs.com)
- [NestJS Discord channel](https://discord.gg/G7Qnnhy)
- [NestJS Devtools](https://devtools.nestjs.com)
- [Deploy Mau](https://mau.nestjs.com)

## License

Dự án sử dụng giấy phép MIT.

---

*Lưu ý*: README này chủ yếu mô tả backend API của hệ thống. Nếu dự án có thêm phần frontend hoặc tích hợp blockchain, bạn nên bổ sung thêm hướng dẫn sử dụng, kiến trúc và các chức năng liên quan.
