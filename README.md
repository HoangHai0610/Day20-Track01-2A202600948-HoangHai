# Day18-Track1-2A202600864-VuNgocVinh

Bài thực hành Ngày 18 — Human-Centered AI Design

**Track chọn:** AI Personal Assistant for Students
**Lát cắt tính năng:** AI quản lý deadline và tạo nhiệm vụ học tập từ email/lịch học (StudyMate AI)

## Cách xem prototype

Mở file [index.html](index.html) trực tiếp bằng trình duyệt 
## Cấu trúc prototype 

- `00` Flow map & phạm vi tính năng
- `01` Onboarding (S0 — bắt buộc)
- `02` Trong khi AI hỗ trợ: S1 (kết nối dữ liệu), S2 (ưu tiên nhiều deadline + explainability), S4 (tạo nhiệm vụ từ email + evidence), S3 (đề xuất kế hoạch học)
- `03` Agency: S5 (ranh giới Act/Ask/Don't Act khi nhắc việc), S9 (soạn email cho giảng viên — draft/review/send)
- `04` Failure & Recovery: S6 (AI gán nhầm deadline — vòng lặp khôi phục đầy đủ 7 bước), S8 (AI nhắc việc không còn cần làm)
- `05` Ma trận feedback 2×2 (explicit/implicit × user/system)
- `06` Design rationale tổng hợp
- `07` Demo path 5 phút

Mỗi flow có thẻ rationale đặt cạnh, giải thích AI biết/chưa biết gì, rủi ro, và lý do chọn Act/Ask/Don't Act.
