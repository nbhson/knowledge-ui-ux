# 05. Specific UI/UX Areas — Lĩnh vực UI/UX cụ thể

## Các lĩnh vực chuyên biệt

### Mobile UX
- Touch target ≥ 44×44px (Apple HIG) / ≥ 48×48dp (Material)
- Thumb zone: đặt action chính ở bottom-center
- System patterns: tab bar, navigation stack, gesture navigation
- Offline-first: thông báo khi mất kết nối, sync state rõ ràng

### Web UX
- Responsive design: mobile-first approach
- Performance budget: < 3s load time trên 3G
- Core Web Vitals (Google, 2021+):
  - **LCP** (Largest Contentful Paint) < 2.5s
  - **FID** (First Input Delay) < 100ms
  - **CLS** (Cumulative Layout Shift) < 0.1
  - **INP** (Interaction to Next Paint) < 200ms (2024 update)

### Voice & Conversational UI
- VUI principles: confirm clear, graceful recovery
- Chatbot design: context-aware, fallbacks rõ ràng
- Multimodal: kết hợp voice + visual

### Data Visualization
- Chart selection: so sánh → bar, xu hướng → line, tỷ lệ → pie
- Color: dùng palette accessible (≥ 4.5:1 contrast)
- Mobile data viz: simplified charts, scrollable tables

### Accessibility (a11y)
- WCAG 2.1 Level AA là standard baseline
- Semantic HTML: button, nav, main, section, article
- ARIA labels khi semantic không đủ
- Keyboard navigation hoàn chỉnh
- Screen reader testing: VoiceOver, NVDA, JAWS

### Micro-interactions
- Animation có mục đích: feedback, state change, orientation
- Spring physics thay vì fixed duration (Material 3 Expressive, Apple UIKit)
- 200-500ms cho transitions, < 100ms cho instant feedback

## Cập nhật 2025-2026

### Motion Design
- **Material 3 Expressive**: spring-based animation với stiffness, damping, mass
- **Apple UIKit Dynamics**: UIKit spring animations, SF Symbols animated
- **Figma Smart Animate**: prototype với physics-based transitions

### AI-integrated UI
- Streaming responses → skeleton loading → rendered output
- Progressive disclosure cho AI-generated content
- Error states khi AI hallucinate: trust calibration UI

> ⚠️ **Cập nhật 10/2026:** Nội dung cơ bản trong folder này đúng nguyên lý. Tuy nhiên cần bổ sung:
> - Các nguồn sách PDF trong folder có niên đại 2010-2015 — nên cập nhật bằng các ấn phẩm mới hơn.
> - **WCAG 2.2 criteria** (9 SC mới từ 10/2023) cần được tích hợp vào mọi design decision.
> - **AI-native design** (Figma Make, v0.dev, Lovable) là paradigm mới cần nghiên cứu thêm.
