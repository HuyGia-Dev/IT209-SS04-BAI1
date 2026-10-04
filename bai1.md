# Báo cáo Bài 1: Khởi tạo Local Repository và Cấu hình danh tính

## 1. Các lệnh đã thực hiện

```bash
# 1. Khởi tạo Local Git Repository
git init

# 2. Cấu hình danh tính ở cấp độ cục bộ (--local)
git config --local user.name "Nguyen Van A"
git config --local user.email "nguyenvana@example.com"

# 3. Tạo tệp tin mới và đưa vào Staging Area
echo "# First Project" > main.txt
git add main.txt

# 4. Thực hiện commit đầu tiên
git commit -m "Initial commit: Khởi tạo dự án"
```

---

## 2. Kết quả kiểm tra

### 2.1. Kiểm tra cấu hình danh tính cục bộ (`git config --local --list`)

```text
user.name=Nguyen Van A
user.email=nguyenvana@example.com
```

Hoặc kiểm tra chi tiết từng thuộc tính:
- `git config --local user.name` -> `Nguyen Van A`
- `git config --local user.email` -> `nguyenvana@example.com`

### 2.2. Kiểm tra lịch sử commit (`git log --oneline`)

```text
7f3a1b2 (HEAD -> main) Initial commit: Khởi tạo dự án
```