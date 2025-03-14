# EUCLIDE
- Thuật toán Euclid phát biểu như sau :  UCLN của hai số nguyên không thay đổi khi thay số lớn hơn bằng hiệu của nó với số nhỏ hơnh
-  Quá trình thay thế này được lặp đi lặp lại cho tới khi 2 số bằng nhau, khi đó UCLN chính là 1 trong 2 số.
- Trong mục 2 khi a và b cách xa nhau thì thuật toán Euclid hoạt động không hiệu quả, ví dụ bạn tìm ULCN(1000000000, 1) thì thuật toán cần lặp 999999999 lần.
# Cải tiến
- Ta cải tiến thuật toán Euclid bằng nhận xét sau :  UCLN của hai số nguyên không thay đổi khi thay 1 trong 2 số thành số dư của nó với số còn lại. Có nghĩa là UCLN(a, b) = UCLN(b, a % b)
- Quá trình thay thế này được lặp đi lặp lại cho tới khi 1 trong 2 số bằng 0, khi đó UCLN chính là số còn lại
# Tính ước chung lớn nhất của một số nguyên lớn và số 64bit.
-  Dùng thuật toán Euclid để tìm số dư của N với M, khi đó số dư sẽ là số 64 bit => áp dụng UCLN với M cùng số dư đó sẽ trở về bài toán bình thường.
