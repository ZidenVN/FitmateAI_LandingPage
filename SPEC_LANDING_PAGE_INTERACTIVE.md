# Fitmate Landing Page - Interactive Frontend Specification
**Project**: Fitmate - Nền Tảng Sức Khỏe, Dinh Dưỡng, Tập Luyện & Huấn Luyện Viên Cá Nhân  
**Course Context**: EXE201 - FPT University  
**Focus**: High-converting interactive landing page supporting CAP (Customer Acquisition Plan) & B2C Conversion Validation (Outcomes 1, 2, 3).

---

## 1. Problem Statement & User Value
- **Context**: The design team created a high-fidelity Stitch prototype (`code.html`, `DESIGN.md`, `screen.png`). However, it lacks interactive behavior, simulated data flows, lead capture capabilities, and realistic app demos needed to convince evaluators and acquire real users.
- **Target Personas**:
  1. *Người mới bắt đầu*: Needs easy workout guides, clear Vietnamese instruction, reassurance.
  2. *Người bận rộn*: Needs rapid camera food scanning, auto-saved workout sessions.
  3. *Người tập cùng PT*: Needs transparent PT profiles, verified credentials, clear booking & cancellation rules.
  4. *EXE201 Evaluator / Mentor*: Needs proof of MVP readiness, lead acquisition funnel, and functional verification.

---

## 2. Interactive Feature Scope

### A. Navigation & Shell
- Dynamic Sticky Navbar with scroll spy indicator.
- Working Mobile Navigation Drawer with backdrop blur and smooth transitions.
- VI / EN Language Switcher.

### B. Interactive Demos (Living Product Experience)
1. **AI Food Scanner Simulator (Section 4)**:
   - 4 Vietnamese dish presets (Phở Bò Tái Nạm, Cơm Tấm Sườn Bì, Salad Ức Gà Bơ, Bún Bò Huế).
   - Local image upload preview with simulated AI laser scanning animation (1.2s loading state).
   - Dynamic portion multiplier (0.5x, 1.0x, 1.5x, 2.0x) recalculating Calo, Protein, Carb, Fat in real time.
   - "Xác nhận và lưu vào nhật ký" action with success toast and daily calorie counter increment.

2. **Realtime Workout Tracker (Section 5)**:
   - Live Rest Countdown Timer with Start, Pause, Reset, and +15s buttons.
   - Interactive Set Manager: Toggle sets between Done (`✓ Hoàn thành`), Rest (`⏳ Đang nghỉ`), and Queued (`▶ Chờ tập`).
   - Weight & Reps quick adjustments (+/- 2.5kg, +/- 1 rep).
   - Live workout session stopwatch.
   - "Kết thúc buổi tập" confirmation modal with workout summary stats.

3. **PT Discovery & Booking Flow (Section 6)**:
   - Filter PTs by specialty: Tất cả, Tăng cơ & Thể hình, Giảm mỡ & Cardio, Yoga & Pilates, Phục hồi chức năng.
   - Interactive PT Cards with verified badges, ratings, and price per session.
   - 4-Step Booking Modal:
     - Step 1: Chọn ngày & Khung giờ (Sáng / Chiều / Tối).
     - Step 2: Thông tin học viên (Họ tên, SĐT Zalo, Mục tiêu).
     - Step 3: Xác nhận chi phí minh bạch & chính sách hủy 24h.
     - Step 4: Nhận Mã Đặt Lịch & Thẻ QR Pass điện tử.

4. **Community Social Feed (Section 7)**:
   - Interactive Like button with instant count increment/decrement.
   - 3-Photo Album Carousel with working Next/Previous and indicator dots.
   - Interactive Comment Section: expand comments drawer, submit new comment with instant optimistic update.
   - Bookmark toggle and Share Modal with clipboard copy.

5. **Fitmate AI Assistant (Section 8 - Dark Theme)**:
   - Conversational chat demo in Vietnamese.
   - Quick prompt chips for instant testing.
   - Input message box with send action.
   - Realistic streaming/typing response generator for fitness and nutrition queries.
   - Conversation switcher in sidebar (switch active threads, create new thread).

6. **Pricing & Lead Acquisition Funnel (Sections 10 & 13)**:
   - Monthly vs Annual Billing Toggle (-20% discount tag).
   - Lead Capture Modal ("Trải nghiệm Fitmate" / "Đăng ký Beta"):
     - Captures: Họ tên, Email, SĐT (Zalo), Mục tiêu, Nền tảng (Android / iOS / Web).
     - Persists leads in `localStorage`.
     - Displays real-time registration counter (e.g., "148/200 người đã đăng ký").
     - Issues instant VIP Beta Pass code + simulated APK download link (aligns with Outcome 1 & 3 requirements).
   - Secret Admin Lead Viewer (Accessible via footer link or `Ctrl+Shift+L`): Allows team to view and export captured leads to CSV for grading reports.

7. **FAQ Search & Accordions (Section 12)**:
   - Real-time search filter for all 10 FAQ questions.
   - Smooth accordion expand/collapse.

---

## 3. Data Contracts & State Resilience (5-State Rule)
- **Empty State**: Clear empty message with action button when search finds no PT or FAQ.
- **Loading State**: Scanning laser animation, AI thinking indicator, spinner on lead submit.
- **Success State**: Toast notifications, verified checkmarks, VIP pass modal.
- **Error State**: Field validation error labels (empty phone, invalid email).
- **Mutation State**: Disabled buttons with spinner icons during processing.
