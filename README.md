## Link của bạn

Đã đăng xong tại: **https://egs-people-operations.github.io/egs-trungthu-2026/**

| Ai | Link |
| --- | --- |
| Bạn (host) | `https://egs-people-operations.github.io/egs-trungthu-2026/#host` |
| Mọi người | `https://egs-people-operations.github.io/egs-trungthu-2026/` |
| Màn chiếu | bấm nút **Open big screen** trong phòng chờ |

Khác nhau duy nhất là chữ `#host` ở cuối. Có `#host` thì thấy nút mở phòng; không có thì chỉ vào phòng bằng mã.

---

# Đưa game lên GitHub Pages

Thư mục này chứa đúng những gì cần đăng. Không cần cài gì trên máy, làm hết trên web.

Chỉ cần **một file duy nhất**: `index.html` — toàn bộ game nằm trong đó (4 MB).

---

## Bước 1 — tạo kho chứa (repository)

1. Vào https://github.com/new
2. **Repository name:** `egs-trungthu-2026`
3. Chọn **Public**.
   *Vì sao Public:* GitHub Pages miễn phí chỉ đăng được kho Public. Kho Private cần bản trả phí.
4. Bấm **Create repository**.

**Bạn sẽ thấy:** trang kho mới, trống, có dòng chữ "uploading an existing file".

> ⚠️ Kho Public nghĩa là ai có link cũng xem được file `index.html`. Nhưng **đáp án không nằm trong file này** — đáp án ở Supabase và không ai đọc được. Nên công khai vẫn an toàn.

## Bước 2 — tải file lên

1. Ở trang kho vừa tạo, bấm chữ **uploading an existing file**.
2. Kéo file `index.html` vào vùng thả file.
3. Bấm **Commit changes**.

**Bạn sẽ thấy:** file `index.html` hiện trong danh sách kho.

## Bước 3 — bật GitHub Pages

1. Trong kho, bấm tab **Settings** (bánh răng, trên cùng bên phải).
2. Menu bên trái, bấm **Pages**.
3. Ở phần **Source**, chọn **Deploy from a branch**.
4. Ở phần **Branch**, chọn `main` và thư mục `/ (root)`, bấm **Save**.

**Bạn sẽ thấy:** một khung xanh xuất hiện sau 1–2 phút với link dạng
`https://<tên-github-của-bạn>.github.io/egs-trungthu-2026/`

## Bước 4 — kiểm tra

1. Mở link đó.
   *Bạn sẽ thấy:* màn bìa game với thỏ và mặt trăng.
2. Thêm `#host` vào cuối link rồi mở lại.
   *Bạn sẽ thấy:* dòng chữ "You are the host. Pick any room code…"

## Bước 5 — link để gửi mọi người

| Ai | Link |
| --- | --- |
| Bạn (host) | `https://egs-people-operations.github.io/egs-trungthu-2026/#host` |
| Mọi người | `https://egs-people-operations.github.io/egs-trungthu-2026/` |
| Màn chiếu | bấm nút **Open big screen** trong phòng chờ |

Lưu ý dấu `/` cuối cùng phải có, nếu không link có thể không mở đúng.

---

## Lần sau muốn cập nhật game

1. Mình gói lại file `index.html` mới, bạn tải về.
2. Vào kho GitHub, bấm vào file `index.html`, bấm nút bút chì hoặc **⋮** → **Delete file** → Commit.
3. Bấm **Add file** → **Upload files** → thả file mới → Commit.
4. Đợi 1–2 phút, mở link và bấm `Ctrl + Shift + R` (Mac: `Cmd + Shift + R`) để nạp bản mới.

**Bạn sẽ thấy:** thay đổi mới xuất hiện. Nếu vẫn là bản cũ, đợi thêm 1 phút rồi nạp lại.

---

## Nếu muốn giữ kho Private

GitHub Pages với kho Private cần GitHub Team (trả phí). Hai cách thay thế miễn phí:

- **Netlify Drop** — vào https://app.netlify.com/drop, kéo file `index.html` vào. Có link ngay, không cần tạo kho, không công khai mã nguồn.
- **Cloudflare Pages** — tương tự, kéo-thả và nhận link.

Cả hai đều nhanh hơn GitHub cho việc chỉ đăng một file.
