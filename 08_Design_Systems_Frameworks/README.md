# 08. Design Systems & Frameworks — Hệ thống thiết kế và framework

## Design System là gì?

Design System = **Shared language** giữa designer và developer, bao gồm:
- Components (buttons, forms, cards, modals)
- Design Tokens (color, spacing, typography)
- Patterns (navigation, data entry, feedback)
- Guidelines (usage, do's & don'ts)
- Documentation (Storybook, Zeroheight)

## Các Design System phổ biến

| System | Nguồn | Style |
|---|---|---|
| Material Design 3 | Google | Modern, expressive, customizable |
| Apple Human Interface | Apple | Minimal, translucency, depth |
| Fluent UI | Microsoft | Professional, enterprise |
| Polaris | Shopify | E-commerce focused |
| Atlassian Design | Atlassian | Collaboration-focused |
| Ant Design | Ant Group | Enterprise, React |
| Radix UI / shadcn/ui | Open source | Headless, Tailwind-first |

## Cập nhật Design Systems 2025-2026

### Material 3 Expressive (Google I/O 5/2025)
Material 3 Expressive rollout từ 9/2025 với:
- **Motion physics system** — spring, damping, stiffness thay vì duration fixed
- **Expressive color** — tonal palettes tự động tạo harmony
- **Adaptive components** — tự động điều chỉnh density theo device
- **New typography** — Google Sans, weighted axes

Ref: https://m3.material.io/blog/building-with-m3-expressive

### Apple Liquid Glass (WWDC 2025)
Ngôn ngữ thiết kế mới cho iOS 26, macOS 26:
- Translucent + blur layers (vibrancy effect)
- Depth qua shadow và motion thay vì flat layers
- Color: vibrancy, tinting, tint groups
- Ref: https://developer.apple.com/design/human-interface-guidelines/materials

### W3C Design Tokens DTCG 2025.10 (Stable)
Design tokens đã đạt Candidate Recommendation 10/2025:
- Format chuẩn: Figma, Penpot, Sketch, Style Dictionary hỗ trợ
- Nguồn duy nhất cho màu, spacing, typography → single source of truth
- Ref: https://www.designtokens.org/TR/2025.10/format/

### Figma Config 2025 Announcements
- **Figma Make**: AI prompt → wireframe → UI (tạo UI từ mô tả)
- **Dev Mode**: Ready-for-Dev annotations, GitHub integration, code connections
- **Figma AI**: AI-powered design suggestions, auto-layout improvements
- Ref: https://www.figma.com/blog/config-2025-recap/

## Tooling

### Component Documentation
- **Storybook 8.x**: Component-driven development, MDX support, addon ecosystem
- **Zeroheight**: Design system documentation (Living style guide)
- **Storybook + Chromatic**: Visual regression testing

### Design Token Pipeline
```
Figma Token → Style Dictionary → CSS Variables / Swift / Kotlin / etc.
```
- **Token Studio (Figma)**: Chỉnh sửa design tokens trực tiếp
- **Style Dictionary (Amazon)**: Transform tokens → multi-platform

> ⚠️ **Cập nhật 10/2026:** File PDF "Modular Design Frameworks" (2016) trong folder này đã cũ. Thay thế kiến thức bằng Material 3 Expressive, Apple Liquid Glass, và W3C DTCG. Figma AI và AI-generated UI đang thay đổi paradigm của design systems.

### So sánh Material 3 Expressive vs Liquid Glass (P2 — 28/10/2026)

Hai ngôn ngữ thiết kế này phục vụ hai hệ sinh thái hoàn toàn khác nhau. Không phải "chọn cái nào tốt hơn" mà là "cái nào phù hợp với platform của bạn."

| Khía cạnh | Material 3 Expressive (Google) | Liquid Glass (Apple) |
|-----------|-------------------------------|----------------------|
| **Platform** | Android (từ Android 16) | iOS 26, iPadOS 26, macOS Tahoe 26 |
| **Định hướng** | Color-forward, expressive, playful | Translucency + depth, refined minimalism |
| **Nền tảng kỹ thuật** | Dynamic color (tonal palettes), motion springs | Blur (vibrancy), refraction, specular highlights |
| **Motion** | Spring physics (damping, stiffness, mass) | Physics-based tự nhiên, parallax depth |
| **Icons** | Phong cách Google Sans, multi-layer | SF Symbols, multi-layer glass overlay |
| **Typography** | Google Sans (variable font) | SF Pro (system), không thay đổi lớn |
| **Dark mode** | Tonal surfaces, không dùng pure black | True dark + vibrancy trên nền thực |

**Khuyến nghị:**
- **Web / Multi-platform**: DTCG tokens + Radix UI / shadcn/ui (không gắn với 1 hệ sinh thái)
- **Android native**: Material 3 Expressive (Android 16 QPR1)
- **iOS/macOS native**: Liquid Glass (iOS 26 SDK)
- **Cross-platform (React Native / Flutter)**: Theo platform guidelines riêng; không cố gắng hòa trộn hai paradigm

> ⚠️ Cả hai đều **không phù hợp cho web** — chỉ dùng cho native app. Web design nên follow WCAG 2.2 và responsive principles.
