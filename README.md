# StudyMate AI — Day 18 → Day 21

Prototype và eval-input workspace một trang cho track **AI Personal Assistant for Students**.

## Phạm vi

StudyMate AI giúp sinh viên phát hiện deadline từ email/lịch học, kiểm chứng thông tin nguồn, xác nhận task và đưa task vào kế hoạch ưu tiên.

Prototype giữ baseline Human-Centered AI Design của Day 18 và bổ sung đầy đủ yêu cầu Day 20:

1. Prototype Day 18 / Current State.
2. Customer Retention Canvas.
3. Core Action, Active User và Retention Metric.
4. Onboarding Audit.
5. Redesigned Onboarding → First Core Action.
6. Before/After và Recovery Path.
7. Measurement Ladder.
8. North Star và Input Metrics.
9. Nature vs Nurture.
10. Hook Review.
11. Metric Tracking Requirement.
12. Demo Path 8 phút.

Day 21 tiếp tục cùng use case và bổ sung:

13. Use Case, Unit of AI Work và Quality Question.
14. User Input Grid với bốn dimensions.
15. 12 Meaningful Combinations.
16. Prompt AI generation và Human Filter.
17. Individual Scenario Dataset v0 gồm 24 rows.
18. Solo Merge, dimension normalization và Coverage Matrix.
19. Scenario Dataset v1 gồm 32 rows.
20. Coverage Review và Known Gaps.
21. Handoff Note và Demo Path 5 phút.

## Phân biệt các ngày

- **Day 18 — phần gốc:** tab `00`, gồm prototype StudyMate ban đầu, scenario, ranh giới agency, explainability, feedback và recovery flow.
- **Day 20 — phần bổ sung:** tab `01–12`, dùng Day 18 làm đầu vào để phân tích retention và chỉnh sửa prototype.
- **Day 21 — AI Evals Test Inputs:** tab `13–21`, chọn lát cắt AI work, thiết kế coverage và tạo Scenario Dataset v0/v1; chưa chạy agent hoặc đọc trace.
- Trong giao diện, **màu cam** và nhãn `PHẦN GỐC · DAY 18` chỉ nội dung Day 18; **màu xanh** và nhãn `PHẦN BỔ SUNG · DAY 20` chỉ nội dung mới của Day 20.
- Day 21 dùng **màu tím** và nhãn `AI EVALS TEST INPUTS · DAY 21`.
- Tab `04–06` thể hiện trực tiếp quan hệ giữa hai ngày: audit current state Day 18, thiết kế flow Day 20 và bảng Before/After.

## Cách xử lý bài nhóm khi làm một mình

- Dataset v0 có một owner: `2A202600948 · Hoàng Hải`.
- Phần group merge được thực hiện dưới dạng **solo merge** minh bạch: đóng băng v0, chuẩn hóa dimensions, deduplicate, review coverage và bổ sung gap rows.
- Không giả lập thành viên khác; mọi row trong v1 giữ `source_owner` thật và có `merge_decision`.
- Dataset v0 và v1 có thể tải CSV trực tiếp trong prototype.

## Chạy prototype

Mở trực tiếp `index.html` trong trình duyệt. Không cần cài package, API hoặc dữ liệu email thật.
