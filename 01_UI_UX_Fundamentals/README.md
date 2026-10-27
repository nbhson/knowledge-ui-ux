# 01. UI/UX Fundamentals — Nền tảng UI/UX

## Tổng quan
Nền tảng thiết kế giao diện người dùng (UI) và trải nghiệm người dùng (UX): usability, accessibility, visual hierarchy, consistency, responsive design.

## Các nguyên lý cốt lõi

### 5 thuộc tính chất lượng giao diện (Nielsen)
1. **Learnability** — Dễ học, người mới có thể hoàn thành task cơ bản nhanh
2. **Efficiency** — Hiệu quả, sau khi học xong thì thao tác nhanh
3. **Memorability** — Dễ nhớ, quay lại sau thời gian dài vẫn dùng được
4. **Errors** — Ít lỗi, tỷ lệ mắc lỗi thấp, có cách khôi phục
5. **Satisfaction** — Hài lòng, thích thú khi sử dụng

### Laws of UX (J. Nielsen & nhiều tác giả)
- **Jakob's Law**: Người dùng dành phần lớn thời gian trên các site khác → thiết kế của bạn phải quen thuộc
- **Fitts's Law**: Thời gian để di chuyển con trỏ đến target tỷ lệ thuận với khoảng cách và tỷ lệ nghịch với kích thước → button to, gần
- **Hick's Law**: Thời gian quyết định tăng khi số lựa chọn tăng → giảm lựa chọn
- **Miller's Law**: Người ta xử lý ~7±2 items trong bộ nhớ ngắn hạn → chunking information
- **Doherty Threshold**: Tương tác < 400ms giữ cảm giác "instant"
- **Aesthetic-Usability Effect**: Thiết kế đẹp tạo ấn tượng dễ sử dụng hơn

### 10 Usability Heuristics (Jakob Nielsen, 1994)
1. Visibility of system status
2. Match between system and the real world
3. User control and freedom
4. Consistency and standards
5. Error prevention
6. Recognition rather than recall
7. Flexibility and efficiency of use
8. Aesthetic and minimalist design
9. Help users recognize and recover from errors
10. Help and documentation

## Cập nhật 2025-2026

### WCAG 2.2 (W3C, 10/2023)
10 tiêu chí mới mà designer cần nắm:

| Success Criterion | Mô tả |
|---|---|
| 2.4.11 Focus Not Obscured (Min) | Focus indicator không bị che bởi other content |
| 2.4.12 Focus Not Obscured (Enhanced) | Focus indicator hoàn toàn visible |
| 2.4.13 Focus Appearance | Độ tương phản ≥ 3:1, diện tích ≥ 18px² |
| 2.5.7 Dragging Movements | Mọi action kéo-thả phải có alternative |
| 2.5.8 Target Size (Min) | Interactive target ≥ 24×24px CSS |
| 3.2.6 Consistent Help | Help mechanisms nhất quán vị trí |
| 3.3.7 Redundant Entry | Không hỏi lại info user đã nhập |
| 3.3.8 Accessible Auth (Min) | Không dùng CAPTCHA/puzzle nếu có alternative |
| 3.3.9 Accessible Auth (Enhanced) | Cognitive function test chỉ khi bắt buộc |

Ref: https://www.w3.org/WAI/WCAG22/quickref/

### AI-native Design
- Figma Make (2025): AI prompt → wireframe → UI
- v0.dev, Lovable, Relume: AI-generated UI components
- Paradigm shift: từ "design → handoff" sang "prompt → preview → iterate"
- Role designer: ngày càng thiên về systems thinking + prompt craft

> ⚠️ **Cập nhật 10/2026:** Nội dung cơ bản trong folder này đúng nguyên lý. Tuy nhiên cần bổ sung:
> - Các nguồn sách PDF trong folder có niên đại 2010-2015 — nên cập nhật bằng các ấn phẩm mới hơn.
> - **WCAG 2.2 criteria** (9 SC mới từ 10/2023) cần được tích hợp vào mọi design decision.
> - **AI-native design** (Figma Make, v0.dev, Lovable) là paradigm mới cần nghiên cứu thêm.
