# Ride Hailing Logistics Centralized Configuration Repository

Kho lưu trữ cấu hình tập trung bằng Git dành cho hệ thống Microservices Ride-Hailing & Logistics Platform, kết hợp với Spring Cloud Config Server.

## Danh sách tệp cấu hình:
- `application.yml`: Cấu hình chung cho toàn bộ các dịch vụ (Eureka Discovery, Logging, Actuator, Virtual Threads).
- `api-gateway.yml`: Định tuyến Spring Cloud Gateway và lọc bảo mật (Port 8080).
- `iam-service.yml`: Cấu hình kết nối cơ sở dữ liệu `iam_db` (Port 8081).
- `driver-service.yml`: Cấu hình kết nối cơ sở dữ liệu `driver_db` (Port 8082).
- `location-service.yml`: Cấu hình kết nối cơ sở dữ liệu `location_db` và Redis GEO (Port 8083).
- `pricing-service.yml`: Cấu hình kết nối cơ sở dữ liệu `pricing_db` (Port 8084).
- `trip-service.yml`: Cấu hình kết nối cơ sở dữ liệu `trip_db`, Redis Lock và Kafka Producer (Port 8085).
- `payment-service.yml`: Cấu hình kết nối cơ sở dữ liệu `payment_db` và Kafka Consumer (Port 8086).
