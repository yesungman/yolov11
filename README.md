##### 인공지능
### 마크다운 방법
### 구리고등학교
### 1학년
![image](https://github.com/user-attachments/assets/ecab8930-7cc6-4a27-b3ff-583a8dbcb071)
# 구구단 출력 코드
```bash
for i in range(2, 10):  # 2단부터 9단까지 반복
    print(f"📌 {i}단")
    for j in range(1, 10):  # 1부터 9까지 곱하기
        print(f"{i} x {j} = {i * j}")
    print()  # 단마다 줄 바꿈
```

# 구구단 출력 (사용자 입력)
dan = int(input("출력할 구구단을 입력하세요 (2~9): "))

if 2 <= dan <= 9:
    print(f"📌 {dan}단")
    for i in range(1, 10):
        print(f"{dan} x {i} = {dan * i}")
else:
    print("⚠️ 2부터 9 사이의 숫자를 입력해주세요!")
    ```
