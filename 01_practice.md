## 실습 과제

### 변수와 네이밍 관련

**1. 변수 선언 및 할당**

다음 정보를 적절한 변수명으로 저장하시오:
- 설비 이름: "CNC Milling Machine"
- 설비 ID: "MC001"
- 현재 온도: 185.5
- 목표 온도: 180.0
- 가동 상태: True
- 에러 코드: None

**예상 결과:**
```
설비 이름: CNC Milling Machine
설비 ID: MC001
현재 온도: 185.5
목표 온도: 180.0
가동 상태: True
에러 코드: None
```

---

**2. 여러 변수 동시 할당**

다음 값들을 한 줄에 변수에 할당하시오:
- temperature, pressure, humidity에 각각 185.5, 1.2, 45 할당
- 두 변수 a, b의 값을 교환 (a=10, b=20 → a=20, b=10)

**예상 결과:**
```
temperature: 185.5
pressure: 1.2
humidity: 45
교환 전 - a: 10, b: 20
교환 후 - a: 20, b: 10
```

---

### 숫자형 연산

**3. 박스 포장 계산**

```python
total_items = 1250
items_per_box = 48
```

총 생산량을 박스당 개수로 나눈 박스 수와 남는 개수를 계산하시오.

**예상 결과:**
```
필요한 박스: 26개
남는 개수: 2개
```

---

**4. 생산 효율 계산**

```python
actual_production = 850
target_production = 1000
work_hours = 8
```

다음을 계산하시오:
- 목표 대비 생산율 (백분율)
- 시간당 평균 생산량
- 목표 달성에 필요한 추가 생산량

**예상 결과:**
```
생산율: 85.0%
시간당 생산량: 106.25개
부족 수량: 150개
```

---

**5. 온도 단위 변환**

```python
celsius = 185.5
```

섭씨 온도를 화씨로 변환하시오. (공식: F = C × 9/5 + 32)

**예상 결과:**
```
섭씨: 185.5°C
화씨: 365.9°F
```

---

**6. 복합 대입 연산자**

```python
count = 100
```

다음 작업을 순서대로 수행하고 각 단계의 결과를 출력하시오:
- 50 증가
- 2배 증가
- 30 감소
- 3으로 나눈 몫

**예상 결과:**
```
초기값: 100
50 증가: 150
2배 증가: 300
30 감소: 270
3으로 나눈 몫: 90
```

---

**7. 거듭제곱과 나머지 연산**

```python
base = 2
exponent = 10
number = 1024
divisor = 7
```

다음을 계산하시오:
- 2의 10승
- 1024를 7로 나눈 몫과 나머지

**예상 결과:**
```
2^10 = 1024
1024 ÷ 7 = 몫 146, 나머지 2
```

---

### 문자열 기본

**8. 문자열 인덱싱**

```python
machine_id = "MC-2024-A001"
```

다음 값을 추출하시오:
- 첫 번째 문자
- 마지막 문자
- 연도 부분 (2024)
- 뒤에서 4자리 (A001)

**예상 결과:**
```
첫 문자: M
마지막 문자: 1
연도: 2024
뒤 4자리: A001
```

---

**9. 문자열 슬라이싱**

```python
serial = "FACTORY-MACHINE-12345"
```

다음을 추출하시오:
- 앞 7글자
- 뒤 5글자
- 중간 부분 (MACHINE)
- 역순으로 변환

**예상 결과:**
```
앞 7글자: FACTORY
뒤 5글자: 12345
중간 부분: MACHINE
역순: 54321-ENIHCAM-YROTCAF
```

---

**10. 문자열 연결과 반복**

```python
prefix = "MC"
number = "001"
separator = "-"
```

다음을 생성하시오:
- 설비 ID: prefix + separator + number
- 구분선 40개의 등호(=)

**예상 결과:**
```
설비 ID: MC-001
========================================
```

---

**11. 문자열 포맷팅 비교**

```python
item = "Bolt"
quantity = 1500
price = 25.5
```

% 연산자, format() 메서드, f-string 세 가지 방법으로 동일한 결과를 출력하시오.

**예상 결과:**
```
제품: Bolt, 수량: 1,500개, 가격: 25.50원
제품: Bolt, 수량: 1,500개, 가격: 25.50원
제품: Bolt, 수량: 1,500개, 가격: 25.50원
```

---

### 문자열 메서드

**12. 대소문자 변환**

```python
product_code = "SmArT-FaCtOrY-2024"
```

다음으로 변환하시오:
- 모두 대문자
- 모두 소문자
- 첫 글자만 대문자
- 각 단어의 첫 글자만 대문자

**예상 결과:**
```
대문자: SMART-FACTORY-2024
소문자: smart-factory-2024
첫 글자 대문자: Smart-factory-2024
제목 형식: Smart-Factory-2024
```

---

**13. 공백 제거 및 정렬**

```python
log_message = "   System Error 404   "
item_name = "Bolt"
```

다음을 수행하시오:
- 양쪽 공백 제거
- 왼쪽만 제거
- 오른쪽만 제거
- item_name을 20자리 왼쪽 정렬
- item_name을 20자리 오른쪽 정렬

**예상 결과:**
```
양쪽 제거: 'System Error 404'
왼쪽 제거: 'System Error 404   '
오른쪽 제거: '   System Error 404'
```

---

**14. 문자열 검색**

```python
log = "Machine MC001 temperature high at 14:30:25"
```

다음을 수행하시오:
- "temperature" 문자열의 위치 찾기
- "MC001" 문자열의 위치 찾기
- 문자 'e'의 등장 횟수 세기
- "Machine"으로 시작하는지 확인
- "25"로 끝나는지 확인

**예상 결과:**
```
temperature 위치: 14
MC001 위치: 8
e 등장 횟수: 5
Machine으로 시작: True
25로 끝남: True
```

---

**15. 문자열 치환 및 분리**

```python
log = "ERROR: Temperature exceeded at sensor-1"
data = "MC001,185.5,Running,Normal"
```

다음을 수행하시오:
- "ERROR"를 "WARNING"으로 변경
- "sensor-1"을 "sensor-2"로 변경
- data를 쉼표로 분리하여 리스트로 만들기
- 분리된 리스트를 " | "로 결합

**예상 결과:**
```
변경 후: WARNING: Temperature exceeded at sensor-2
분리: ['MC001', '185.5', 'Running', 'Normal']
결합: MC001 | 185.5 | Running | Normal
```

---

**16. 문자열 판별**

```python
code1 = "12345"
code2 = "MC001"
code3 = "ABCDE"
code4 = "   "
```

다음을 확인하시오:
- code1이 숫자로만 구성되었는지
- code2가 문자와 숫자로 구성되었는지
- code3가 문자로만 구성되었는지
- code4가 공백으로만 구성되었는지

**예상 결과:**
```
code1 숫자: True
code2 문자+숫자: True
code3 문자: True
code4 공백: True
```

---

### 문자열 포매팅

**17. f-string 고급 포매팅**

```python
machine_name = "CNC Machine"
current_temp = 185.5
target_temp = 180.0
production = 1500
efficiency = 0.856
```

다음 형식으로 출력하시오:
- 온도: 소수점 1자리
- 생산량: 천 단위 구분
- 효율: 백분율 (소수점 1자리)
- 온도 편차: 부호 포함

**예상 결과:**
```
[설비 상태 보고서]
설비명: CNC Machine
현재 온도: 185.5°C
목표 온도: 180.0°C
온도 편차: +5.5°C
생산량: 1,500개
효율: 85.6%
```

---

**18. 테이블 형식 출력**

```python
items = [
    ("MC001", 185.5, "Running"),
    ("MC002", 192.3, "Stopped"),
    ("MC003", 178.2, "Running")
]
```

다음 형식의 테이블을 출력하시오:
- ID는 왼쪽 정렬 (10자리)
- 온도는 오른쪽 정렬 (8자리, 소수점 1자리)
- 상태는 가운데 정렬 (10자리)

**예상 결과:**
```
ID        |   Temp  |  Status
MC001     |  185.5  |  Running
MC002     |  192.3  | Stopped
MC003     |  178.2  |  Running
```

---

### 불린과 논리 연산

**19. 비교 및 논리 연산**

```python
temperature = 185
pressure = 1.2
vibration = 0.05
is_maintenance = False
```

다음 조건을 평가하시오:
- 온도가 180 이상인지
- 압력이 1.0과 1.5 사이인지
- 진동이 0.1 미만인지
- 모든 센서가 정상 범위이고 정비 모드가 아닌지

**예상 결과:**
```
온도 >= 180: True
1.0 <= 압력 <= 1.5: True
진동 < 0.1: True
전체 정상: True
```

---

### None 타입과 형변환

**20. 형변환 및 None 처리**

```python
str_temp = "185.5"
str_count = "1000"
int_value = 42
float_value = 3.14159
error_code = None
```

다음을 수행하시오:
- str_temp를 실수로 변환하고 10 더하기
- str_count를 정수로 변환하고 2로 나누기
- int_value를 실수로 변환
- float_value를 소수점 2자리로 반올림
- error_code가 None인지 확인

**예상 결과:**
```
변환 후 온도: 195.5
변환 후 개수: 500
정수 → 실수: 42.0
반올림: 3.14
error_code is None: True
```
