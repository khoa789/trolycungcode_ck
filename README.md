# My Claude Config

Lưu trữ các custom commands (skills) cho Claude Code.

---

## Cài đặt trên máy mới (hoặc sau khi cài lại máy)

Chạy 3 lệnh này trong Terminal:

```bash
git clone https://github.com/khoa789/trolycungcode_ck.git ~/Documents/my-claude-config
mkdir -p ~/.claude/commands
cp ~/Documents/my-claude-config/build-idea.md ~/.claude/commands/
```

Mở Claude Code lên, gõ `/build-idea` là dùng được ngay.

---

## Khi thêm skill mới

Copy file skill vào `~/.claude/commands/` và lưu backup vào folder này, rồi chạy:

```bash
cd ~/Documents/my-claude-config
git add . && git commit -m "Add [tên skill]" && git push
```

GitHub sẽ luôn là bản mới nhất.

---

## Danh sách skills

| File | Lệnh | Mô tả |
|------|------|-------|
| `build-idea.md` | `/build-idea` | Đồng hành từ ý tưởng đến sản phẩm hoàn chỉnh — hỏi ý tưởng, tạo project, hướng dẫn từng bước theo Golden Flow |

---

## Ghi chú

- Folder `~/.claude/commands/` là nơi Claude Code đọc tất cả custom commands
- Mỗi file `.md` trong đó tương ứng với một lệnh `/tên-file`
