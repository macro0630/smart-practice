16. 생산 라인 실시간 모니터링

production_line = [
    {"position": 1, "product_id": "P001", "status": "OK", "temperature": 185.5},
    {"position": 2, "product_id": "P002", "status": "OK", "temperature": 186.2},
    {"position": 3, "product_id": "P003", "status": "NG", "temperature": 192.5},
    {"position": 4, "product_id": "P004", "status": "OK", "temperature": 184.8},
    {"position": 5, "product_id": "P005", "status": "CRITICAL", "temperature": 205.0},
    {"position": 6, "product_id": "P006", "status": "OK", "temperature": 185.0},
]
다음 조건으로 생산 라인을 모니터링하시오:

각 제품의 위치, ID, 상태를 출력
온도가 190도 이상이면 "고온 경고" 표시
상태가 "NG"이면 불량 카운트 증가
상태가 "CRITICAL"이면 즉시 라인 정지
최종 합격/불량 통계 출력
예상 결과:

[위치 1] P001: OK (185.5°C)
[위치 2] P002: OK (186.2°C)
[위치 3] P003: NG (192.5°C) ⚠️ 고온 경고
[위치 4] P004: OK (184.8°C)
[위치 5] P005: CRITICAL (205.0°C) ⚠️ 고온 경고
!!! 치명적 불량 발견 - 라인 긴급 정지 !!!

===== 검사 결과 =====
검사 제품 수: 5개
합격: 3개
불량: 2개
라인 상태: 긴급 정지
