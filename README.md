# My Claude Config

Lưu trữ các custom commands (skills) cho Claude Code.

---

## Cài đặt trên máy mới (hoặc sau khi cài lại máy)

Chạy 2 lệnh này trong Terminal:

```bash
mkdir -p ~/.claude/commands
cp ~/Documents/my-claude-config/build-idea.md ~/.claude/commands/
```

Mở Claude Code lên, gõ `/build-idea` là dùng được ngay.

---

## Danh sách skills

| File | Lệnh | Mô tả |
|------|------|-------|
| `build-idea.md` | `/build-idea` | Đồng hành từ ý tưởng đến sản phẩm hoàn chỉnh — hỏi ý tưởng, tạo project, hướng dẫn từng bước theo Golden Flow |

---

## Ghi chú

- Folder `~/.claude/commands/` là nơi Claude Code đọc tất cả custom commands
- Mỗi file `.md` trong đó tương ứng với một lệnh `/tên-file`
- Khi thêm skill mới: copy file vào `~/.claude/commands/` và lưu backup vào folder này
