# Số chia hết cho 3:
- Số có tổng các chữ số chia hết cho 3
# Số chia hết cho 4:
- Là số có một chữ số chia hết cho 4
- Hoặc có 2 chữ số cuối cùng ghép lại chia hết cho 4.
# Số chia hết cho 5:
- Số có chữ số cuối cùng là 0 hoặc 5.
# Số chia hết cho 11:
- Lấy chênh lệch giữa tổng chữ số vị trí chẵn và tổng chữ số vị trí lẻ, khoảng chênh lệch này phải chia hết cho 11.
# Số chia hết cho 15:
- Là số có thể chia hết cho cả 3 và 5
# Số chia hết cho 25:
- Số có 2 chữ số cuối cùng là 00
- Hoặc 2 chữ số cuối cùng chia hết cho 25;

# Chia số nguyên lớn M cho N
- Duyệt từng chữ số của N từ trái qua , r ban đầu = ; sau đó
`r = r*10 + số đó`; sau đó r = r%n là xong. Số cuối cùng là `r`
Cho số nguyên dương N là số nguyên lớn. Hãy tìm chữ số cuối cùng của 2008^n.

Hay nói cách khác đề bài yêu cầu bạn tìm 2008^n % 10.

Gợi ý : 2008^n % 10 = (2008 % 10) ^ n % 10 = 8 ^ n % 10. Mà 8 là lũy thừa của 2, vì thế chữ số cuối cùng cùng của 8^n cũng sẽ tuần hoàn với chu kỳ 4.
