# Bài 1: Python là ngôn ngữ thông dịch hay biên dịch? Tại sao?

Python là **ngôn ngữ thông dịch (Interpreted Language)**.

## Giải thích:

- Mã nguồn Python được thực thi từng dòng bởi trình thông dịch (Python Interpreter).
- Không cần biên dịch toàn bộ chương trình thành tệp thực thi trước khi chạy.
- Khi chạy chương trình, Python sẽ chuyển mã nguồn thành **bytecode (.pyc)**, sau đó được **Python Virtual Machine (PVM)** thực thi.
- Điều này giúp Python dễ học, dễ sửa lỗi và có thể chạy trên nhiều hệ điều hành khác nhau.

**Kết luận:** Python chủ yếu được xem là **ngôn ngữ thông dịch**, mặc dù trong quá trình thực thi vẫn có bước biên dịch sang bytecode.

---

# Bài 2

## 1. Các kiểu dữ liệu trong Python

### Kiểu số

- `int` : Số nguyên
- `float` : Số thực
- `complex` : Số phức

### Kiểu logic

- `bool` : Giá trị đúng/sai (`True`, `False`)

### Kiểu chuỗi

- `str` : Chuỗi ký tự

### Kiểu tập hợp dữ liệu

- `list` : Danh sách
- `tuple` : Bộ dữ liệu
- `set` : Tập hợp
- `dict` : Từ điển (Dictionary)

### Kiểu đặc biệt

- `NoneType` : Giá trị `None`

---

## 2. Các toán tử trong Python

### a. Toán tử số học

- `+` : Cộng
- `-` : Trừ
- `*` : Nhân
- `/` : Chia
- `//` : Chia lấy phần nguyên
- `%` : Chia lấy dư
- `**` : Lũy thừa

### b. Toán tử so sánh

- `==`
- `!=`
- `>`
- `<`
- `>=`
- `<=`

### c. Toán tử gán

- `=`
- `+=`
- `-=`
- `*=`
- `/=`
- `//=`
- `%=`
- `**=`

### d. Toán tử logic

- `and`
- `or`
- `not`

### e. Toán tử thành viên

- `in`
- `not in`

### f. Toán tử định danh

- `is`
- `is not`

---

## 3. Mệnh đề điều kiện và vòng lặp

### a. Mệnh đề điều kiện

- `if`
- `elif`
- `else`

**Ví dụ:**

```python
age = 18

if age >= 18:
    print("Đủ tuổi")
else:
    print("Chưa đủ tuổi")
```

### b. Vòng lặp

#### Vòng lặp `for`

```python
for i in range(5):
    print(i)
```

#### Vòng lặp `while`

```python
i = 1
while i <= 5:
    print(i)
    i += 1
```

### Các câu lệnh điều khiển vòng lặp

- `break`
- `continue`
- `pass`

---

## 4. Kiểu dữ liệu True, False

Python sử dụng kiểu dữ liệu **bool (Boolean)** để biểu diễn hai giá trị:

- `True` : Đúng
- `False` : Sai

Ví dụ:

```python
a = 10
b = 5

print(a > b)   # True
print(a < b)   # False
```

Các giá trị thường được xem là `False`:

- `False`
- `0`
- `0.0`
- `""` (chuỗi rỗng)
- `[]` (danh sách rỗng)
- `{}`
- `()`
- `set()`
- `None`

Các giá trị còn lại thường được xem là `True`.

---

# Kết luận

- Python là ngôn ngữ **thông dịch**, có biên dịch sang bytecode trước khi thực thi.
- Python hỗ trợ nhiều kiểu dữ liệu như: `int`, `float`, `bool`, `str`, `list`, `tuple`, `set`, `dict`,...
- Các nhóm toán tử gồm: số học, so sánh, gán, logic, thành viên và định danh.
- Mệnh đề điều kiện sử dụng `if`, `elif`, `else`; vòng lặp sử dụng `for` và `while`.
- Kiểu dữ liệu `bool` gồm hai giá trị: `True` và `False`.
