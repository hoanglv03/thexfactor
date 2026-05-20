# N-FACTOR · The X Factor — Số Chủ Đạo Calculator

Web tính số chủ đạo (Numerology Life Path Number) cho sự kiện **The X Factor** của team **N-FACTOR**.

## Tính năng
- Tính số chủ đạo cá nhân từ ngày sinh (rút gọn về 1 chữ số 1–9)
- Tính tổng số của cặp đôi (2 người chơi)
- Step-by-step hiển thị từng bước cộng/rút gọn
- KHÔNG giữ master numbers (11 → 2, 22 → 4, 33 → 6)

## Deploy lên Vercel (drag & drop, không cần CLI)

1. Mở https://vercel.com/new
2. Đăng nhập (Google / GitHub / Email đều được)
3. Kéo cả folder `n-factor-deploy/` này thả vào ô **"Deploy a static project"** (hoặc nút "Browse" → chọn folder)
4. Đặt Project Name (vd: `n-factor-x-factor`)
5. Bấm **Deploy** → đợi ~10 giây
6. Vercel sẽ cấp URL dạng `https://n-factor-x-factor.vercel.app` — share cho team xài!

## File trong folder
- `index.html` — toàn bộ web (HTML + CSS + JS, single-file)
- `vercel.json` — config cache & security headers
- `README.md` — file này
