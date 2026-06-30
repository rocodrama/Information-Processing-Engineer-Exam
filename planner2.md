# 정보처리기사 실기 Level-2 학습 플래너

## 컨셉

- **Level-1**: 개념 정리 중심 (출제기준 12챕터 구조)
- **Level-2**: 실전 문제 풀이 중심 (계산 공식 + 코드 해석 + 기출문제)
- 기출 출처: chobopark.tistory.com (2020~2025 기출 확인 완료, 접근 가능)
- 각 페이지는 **개념 요약 → 공식/패턴 → 예제 → 기출 유사 문제** 순으로 구성
- IP 마스크, 스케줄링, 페이지 교체 등 계산 문제는 **단계별 풀이 과정** 시각화

---

## 기출 URL 목록 (소스 데이터)

| 연도 | 회차 | URL |
|------|------|-----|
| 2025 | 1회 | https://chobopark.tistory.com/540 |
| 2025 | 2회 | https://chobopark.tistory.com/554 |
| 2025 | 3회 | https://chobopark.tistory.com/558 |
| 2024 | 1회 | https://chobopark.tistory.com/476 |
| 2024 | 2회 | https://chobopark.tistory.com/483 |
| 2024 | 3회 | https://chobopark.tistory.com/495 |
| 2023 | 1회 | https://chobopark.tistory.com/372 |
| 2023 | 2회 | https://chobopark.tistory.com/420 |
| 2023 | 3회 | https://chobopark.tistory.com/453 |
| 2022 | 1회 | https://chobopark.tistory.com/271 |
| 2022 | 2회 | https://chobopark.tistory.com/423 |
| 2022 | 3회 | https://chobopark.tistory.com/424 |
| 2021 | 1회 | https://chobopark.tistory.com/191 |
| 2021 | 2회 | https://chobopark.tistory.com/210 |
| 2021 | 3회 | https://chobopark.tistory.com/217 |
| 2020 | 1회 | https://chobopark.tistory.com/196 |
| 2020 | 2회 | https://chobopark.tistory.com/195 |
| 2020 | 3회 | https://chobopark.tistory.com/194 |
| 2020 | 4회 | https://chobopark.tistory.com/192 |

---

## 기출 분석 (2020~2025 실제 문제 기반)

### 분야별 출제 빈도 (회당 20문제 중)

| 분야 | 평균 문제 수 | 빈출 키워드 |
|------|------------|------------|
| C/Java/Python 코드 해석 | 6~8문제 | 포인터, 상속/오버라이딩, 슬라이싱, 재귀 |
| SQL | 2~4문제 | SELECT/JOIN/서브쿼리 결과, INSERT/UPDATE 빈칸 |
| 네트워크/보안 | 2~3문제 | IP 서브넷 계산, OSI계층, 공격유형, 암호화 |
| OS/알고리즘 | 2~3문제 | 스케줄링 계산, 페이지교체, 정렬 추적 |
| SW공학 | 2~3문제 | 디자인패턴, UML, 응집도/결합도, 테스트 |
| DB 이론 | 1~2문제 | 정규화, 트랜잭션, 관계대수, 무결성 |

### 반복 출제 기출 패턴 (★ = 매우 자주 출제)

**프로그래밍:**
- ★ C 포인터 & 2차원 배열 연산 → 출력값 맞추기
- ★ Java 상속/오버라이딩 → 어느 메서드가 호출되는지
- ★ Python 슬라이싱/딕셔너리 → 결과값 맞추기
- ★ C 재귀함수 (팩토리얼, 피보나치) → 출력값
- Java 예외처리 try-catch-finally 실행 순서
- C 구조체 포인터 (->연산자)
- Java 싱글톤 패턴 코드 분석

**SQL:**
- ★ SELECT + JOIN (INNER/LEFT/CROSS) + GROUP BY → 결과 행/값 맞추기
- ★ INSERT INTO ... VALUES / SELECT ... FROM 빈칸
- 서브쿼리 (IN, EXISTS) 결과
- UNION, CROSS JOIN 결과 (행 수 계산)
- DCL: GRANT, REVOKE
- 관계대수 기호 (π, σ, ⋈, ∪, -, ×)

**네트워크/보안:**
- ★ 서브넷 마스크 계산: IP/prefix → 네트워크주소, 브로드캐스트, 호스트 수
- ★ FLSM 서브넷 분할 → 브로드캐스트 IP
- OSI 7계층 프로토콜 이름 (ARP, RARP, OSPF, RIP)
- 공격 유형: SYN Flooding, Smurf, ARP Spoofing, XSS, SQL Injection
- 암호화: AES, DES, RSA, SHA, IPSec, SSH

**OS/알고리즘:**
- ★ RR(라운드로빈) 평균 대기시간 계산
- ★ SJF/SRT 스케줄링 → 간트차트, 평균 대기시간
- ★ 페이지 교체 (LRU, FIFO, OPT, LFU) → 페이지 부재 횟수
- 스택/큐 PUSH/POP 연산 결과

**SW공학:**
- ★ 디자인 패턴 이름 맞추기 (Singleton, Observer, Factory, Iterator, Proxy, Adapter, Bridge)
- ★ 응집도/결합도 종류 → 이름 맞추기
- UML 관계: 연관, 일반화, 의존, 집합, 구성
- 테스트 커버리지: 문장, 분기, 조건, 변경조건/결정
- IaaS / PaaS / SaaS 분류

---

## 페이지 구성 (총 12개 + index)

### index.html — Level-2 대시보드
- Level-1 카드 스타일 그대로 + "기출 분석 기반" 태그 추가
- 출제 빈도 퍼센트 표시
- Level-1 대시보드 링크 포함

---

### Section A: 프로그래밍 코드 추적 (3페이지)

#### 01_c_language.html — C언어 코드 추적
**출제 빈도: ★★★★★ (매회 2~3문제)**

포함 내용:
- 포인터 & 2차원 배열 주소 연산 (★★★)
- 구조체 & 구조체 포인터 (`->` 연산자)
- 재귀함수 (팩토리얼, 피보나치)
- 비트 연산 (`&`, `|`, `^`, `<<`, `>>`)
- static 변수 누적 동작
- 문자열 처리 (`strlen`, 포인터 증감)

기출 코드 수록:
- 2024 1회 Q2: 삼항연산자 + 비트시프트 → 151
- 2024 1회 Q4: 문자열 역순 → GECA
- 2024 2회 Q13: 2차원 배열 포인터 → 21
- 2024 2회 Q15: 문자열 복사 인덱스 합 → 10
- 2024 2회 Q18: 값 전달 + switch → -13
- 2024 3회 Q7: static 변수 누적 → 20
- 2024 3회 Q12: 연결리스트 교환 → 312
- 2024 3회 Q16: 이중 포인터 → 1
- 2023 3회 Q4: 완전수 → 34
- 2023 3회 Q8: 재귀 팩토리얼 → 5040
- 2022 3회 Q4: 배열 → 24513
- 2022 3회 Q13: 코드 → 2
- 2021 3회 Q12: 포인터 배열 → 37
- 2021 3회 Q17: 구조체 포인터 → 501
- (+ 추가 기출 복원 문제)

#### 02_java_language.html — Java 코드 추적
**출제 빈도: ★★★★★ (매회 2~3문제)**

포함 내용:
- 상속 + 오버라이딩 실행 순서 (★★★)
- 인터페이스 & 추상클래스
- 예외처리 try-catch-finally 실행 흐름
- 제네릭, 오버로딩
- 람다식 & 함수형 인터페이스
- 문자열 비교: `==` vs `.equals()`
- 싱글톤 패턴 코드 분석

기출 코드 수록:
- 2025 2회 Q5: Java 클래스 → BB
- 2025 2회 Q9: 람다식 → 19
- 2025 2회 Q10: 상속/오버라이딩 → 5P
- 2025 2회 Q15: 객체 참조 → 1a3b3
- 2024 3회 Q1: String 배열 비교 → OOAAA
- 2024 3회 Q11: 다형성 → 52
- 2024 3회 Q18: 예외처리 → 101
- 2024 3회 Q19: 제네릭 + 오버로딩 → B0
- 2024 2회 Q1: 배열 비교 `==` → NNN
- 2024 2회 Q14: 홀수/짝수 합계 → 25, 20
- 2024 2회 Q17: 재귀 역순 출력 → dcba
- 2024 1회 Q16: 다형성 → 9
- 2023 2회 Q14: 문자열 비교 → true/false/true/true
- 2022 3회 Q19: 루프 → 0123
- 2022 3회 Q20: → 993

#### 03_python_language.html — Python 코드 추적
**출제 빈도: ★★★★☆ (매회 1~2문제)**

포함 내용:
- 리스트 슬라이싱 패턴 총정리 (`a[::−1]`, `a[1:4:2]`)
- 딕셔너리: `.get()`, `.items()`, `.keys()`, `.values()`
- 집합(set) 연산
- 내장함수: `map`, `filter`, `sorted`, `enumerate`, `zip`
- 람다 & 함수형 스타일
- 클래스 `__init__`, `__str__`
- 타입체크: `isinstance`, `type`

기출 코드 수록:
- 2025 2회 Q17: 딕셔너리/집합 → 2
- 2024 3회 Q2: 리스트 역순 + 합산 → 3
- 2024 3회 Q10: 타입 검사 → 45
- 2024 1회 Q12: 리스트 문자 추출 → Seynaau
- 2023 3회 Q14: input().split()
- 2023 2회 Q19: 문자열 슬라이싱 → engneing
- 2022 3회 Q9: → [101,102,103,104,105]
- 2021 3회 Q14: → False
- 2020 4회 Q9: → [1,2,3] / 7 / 123 / 45 / 6789

---

### Section B: 데이터베이스 & SQL (2페이지)

#### 04_sql_queries.html — SQL 쿼리 실전
**출제 빈도: ★★★★★ (매회 2~4문제)**

포함 내용:
- SELECT 기본 + WHERE + ORDER BY
- JOIN 완전 정리 (INNER / LEFT / RIGHT / CROSS / SELF / NATURAL)
- GROUP BY + HAVING + 집계함수 (COUNT, SUM, AVG, MAX, MIN)
- 서브쿼리 (스칼라, 인라인뷰, 중첩)
- UNION / UNION ALL / INTERSECT / EXCEPT 결과 행 수
- INSERT INTO ... VALUES vs INSERT INTO ... SELECT
- UPDATE ... SET
- DCL: GRANT, REVOKE, WITH GRANT OPTION
- TCL: COMMIT, ROLLBACK, SAVEPOINT
- 윈도우 함수: ROW_NUMBER(), RANK(), DENSE_RANK()
- 관계대수 기호: π(프로젝트), σ(셀렉트), ⋈(조인), ∪(합집합), -(차집합), ×(카티션)

기출 문제 수록:
- 2025 1회 Q7: SQL SELECT → name/incentives/이순신/1000
- 2024 3회 Q3: JOIN + GROUP BY → 1
- 2024 2회 Q3: INSERT/UPDATE 빈칸 → VALUES, SELECT, FROM, SET
- 2024 1회 Q13: 서브쿼리 → B
- 2024 1회 Q18: COUNT 쿼리 → 1
- 2023 3회 Q6: UNION 정렬 → 4,3,2,1
- 2023 3회 Q19: 관계대수 기호
- 2022 3회 Q12: SQL 실행 결과 행 수 → 200, 3, 1
- 2020 4회 Q16: GROUP BY SELECT문 작성

#### 05_database_theory.html — DB 이론 심화
**출제 빈도: ★★★☆☆ (매회 1~2문제)**

포함 내용:
- 정규화 단계별 판별 (1NF~BCNF)
- 이상 현상 (삽입, 삭제, 갱신 이상)
- 트랜잭션 ACID + 회복 기법 (즉각갱신, 지연갱신)
- 무결성 제약 (개체, 참조, 도메인, 키)
- 데이터베이스 설계 단계 순서
- 관계 Cardinality(행 수), Degree(열 수)
- 인덱스 구조 (B-Tree, 클러스터드/넌클러스터드)
- 뷰 (View) 개념, CASCADE 옵션

기출 문제 수록:
- 2024 2회 Q2: 반정규화
- 2024 2회 Q4: Cardinality/Degree → 5, 4
- 2024 3회 Q8: 무결성 제약 → 개체
- 2024 1회 Q6: 정규형 판단 → 제3정규형
- 2023 3회 Q20: 참조 무결성
- 2023 2회 Q10: DB 설계 단계
- 2022 3회 Q18: ER다이어그램 기호
- 2020 4회 Q12: 이상 현상 3가지

---

### Section C: 계산 문제 (3페이지)

#### 06_network_ip.html — 네트워크 & IP 계산 ⭐핵심⭐
**출제 빈도: ★★★★☆**

**IP 주소 & 서브넷 마스크 계산 (단계별):**
```
예) IP: 223.13.234.132 / 서브넷마스크: 255.255.255.192

Step 1: prefix 구하기 → 192 = 11000000 → /26
Step 2: 호스트 비트 수 = 32 - 26 = 6
Step 3: 호스트 수 = 2^6 - 2 = 62
Step 4: 서브넷 블록 크기 = 2^6 = 64
Step 5: 네트워크 주소 = 223.13.234.128 (132를 64의 배수로 내림)
Step 6: 브로드캐스트 = 223.13.234.191 (128+64-1)
```

**FLSM 서브넷 분할:**
```
예) 192.168.1.0/24 → 3개 서브넷 분할
필요한 서브넷 비트: 2^2=4 ≥ 3 → /26 마스크
블록 크기: 64
1번: 192.168.1.0   ~ 192.168.1.63  (브로드캐스트: 192.168.1.63)
2번: 192.168.1.64  ~ 192.168.1.127 (브로드캐스트: 192.168.1.127) ← 기출 정답
3번: 192.168.1.128 ~ 192.168.1.191
```

**IPv4 클래스 암기표:**
- A클래스: 0.0.0.0 ~ 127.255.255.255 (/8)
- B클래스: 128.0.0.0 ~ 191.255.255.255 (/16)
- C클래스: 192.0.0.0 ~ 223.255.255.255 (/24)
- D클래스: 224.0.0.0 ~ 239.255.255.255 (멀티캐스트)
- E클래스: 240.0.0.0 ~ 255.255.255.255 (예약)

**사설 IP 대역:**
- 10.0.0.0/8
- 172.16.0.0/12 (172.16~172.31)
- 192.168.0.0/16

**OSI 7계층 + 프로토콜:**
7-응용: HTTP, HTTPS, FTP, SMTP, DNS, DHCP  
6-표현: SSL/TLS, JPEG, MPEG  
5-세션: NetBIOS, SSH  
4-전송: TCP, UDP  
3-네트워크: IP, ICMP, ARP, RARP, OSPF, RIP, BGP  
2-데이터링크: Ethernet, MAC, HDLC, PPP  
1-물리: RS-232, 허브, 리피터  

기출 문제 수록:
- 2025 2회 Q6: IP 223.13.234.132/26 → 서브넷 수 128, 호스트 62
- 2024 1회 Q5: 라우터 IP 할당 → 192.168.35.72 등
- 2022 3회 Q5: FLSM 3분할 2번째 브로드캐스트 → 192.168.1.127
- 2025 1회 Q6: ARP/RARP
- OSI 계층 이름 맞추기 (2021 3회 Q6)

**네트워크 공격 유형 정리:**
- SYN Flooding: 3-way handshake 취약점, ACK 미응답
- Smurf: ICMP Echo Reply 다중 호스트 공격
- ARP Spoofing: MAC 주소 위조
- XSS: 악성 스크립트 삽입
- SQL Injection: 쿼리 조작
- CSRF: 사용자 권한 도용

#### 07_os_scheduling.html — 운영체제 계산
**출제 빈도: ★★★★☆**

**스케줄링 계산 공식:**
```
반환시간 = 완료시간 - 도착시간
대기시간 = 반환시간 - 실행시간
평균 대기시간 = 전체 대기시간 합 / 프로세스 수
```

**FCFS, SJF, SRT, RR 비교:**
- FCFS: 도착 순서대로 (비선점)
- SJF: 실행시간 가장 짧은 것 우선 (비선점)
- SRT: 남은 실행시간 가장 짧은 것 우선 (선점) → SJF 선점 버전
- RR: 타임퀀텀만큼 실행 후 순환 (선점)
- 우선순위: 숫자 낮을수록 우선 (보통)

기출:
- 2025 2회 Q13: RR 평균 대기시간 → 11.75ms
- 2024 2회 Q12: SRT 평균 대기시간 → 6.5
- 2022 3회 Q16: SJF, RR, SRT 알고리즘 이름 매칭

**페이지 교체 알고리즘:**
```
참조 열: 7 0 1 2 0 3 0 4 2 3 0 3 2 1 2 0 1 7 0 1
프레임 수: 3개

LRU 계산: 가장 오래 전에 사용된 페이지 교체
→ 페이지 부재 횟수: 12 (2024 3회 Q4)
```
- FIFO: 먼저 들어온 것 교체 (Belady's Anomaly 가능)
- LRU: 최근 미사용 교체
- OPT: 앞으로 가장 오래 사용 안 할 것 교체 (최적)
- LFU: 사용 빈도 최소 교체

기출:
- 2024 3회 Q4: LRU 프레임 3 → 페이지 부재 12
- 2024 1회 Q9: LRU/LFU 부재 횟수 → 각 6
- 2020 4회 Q5: 비트 연산 → n%2

**교착상태 4가지 조건 (상점비순):**
1. 상호배제 (Mutual Exclusion)
2. 점유대기 (Hold and Wait)
3. 비선점 (Non-preemption)
4. 순환대기 (Circular Wait)

**프로세스 상태:**
준비(Ready) → 실행(Running) → 대기(Waiting) → 준비

#### 08_algorithm_trace.html — 알고리즘 & 자료구조 추적
**출제 빈도: ★★★★☆**

**정렬 알고리즘 비교표:**

| 알고리즘 | 최선 | 평균 | 최악 | 안정 |
|---------|------|------|------|------|
| 버블정렬 | O(n) | O(n²) | O(n²) | ✓ |
| 선택정렬 | O(n²) | O(n²) | O(n²) | ✗ |
| 삽입정렬 | O(n) | O(n²) | O(n²) | ✓ |
| 퀵정렬 | O(n log n) | O(n log n) | O(n²) | ✗ |
| 합병정렬 | O(n log n) | O(n log n) | O(n log n) | ✓ |
| 힙정렬 | O(n log n) | O(n log n) | O(n log n) | ✗ |

**각 정렬 단계별 추적 시각화:**
```
버블정렬 예) [5, 3, 8, 1, 2]
Pass1: 3 5 1 2 8
Pass2: 3 1 2 5 8
Pass3: 1 2 3 5 8
Pass4: 1 2 3 5 8 ← 완료
```

**트리 순회:**
```
전위(PreOrder):  루트 → 왼 → 오  (Root → L → R)
중위(InOrder):   왼 → 루트 → 오  (L → Root → R)  ← 이진탐색트리 정렬 결과
후위(PostOrder): 왼 → 오 → 루트  (L → R → Root)
```

**스택/큐 연산 추적:**
- 스택: LIFO (PUSH/POP)
- 큐: FIFO (Enqueue/Dequeue)
- 원형 큐: front/rear 포인터 연산

기출:
- 2025 2회 Q12: 원형 큐 → 2, 3
- 2023 2회 Q9: 스택 구현 → 213465

---

### Section D: SW공학 & 보안 (2페이지)

#### 09_sw_engineering.html — 소프트웨어 공학 실전
**출제 빈도: ★★★☆☆**

**디자인 패턴 23가지 + 기출 핵심:**

생성 패턴:
- Singleton: 인스턴스 하나만 생성 ★★★
- Factory Method: 서브클래스에서 객체 생성 ★★
- Abstract Factory: 관련 객체군 생성 ★ (2024 1회 Q20)
- Builder: 복잡한 객체 단계적 생성
- Prototype: 원본 객체 복사

구조 패턴:
- Adapter: 인터페이스 변환 ★★ (2025 1회 Q14)
- Bridge: 추상과 구현 분리 ★ (2022 3회 Q3)
- Decorator: 기능 동적 추가
- Facade: 복잡한 서브시스템 단순 인터페이스
- Proxy: 대리 객체 ★★ (2025 2회 Q7)
- Composite: 트리 구조 객체

행위 패턴:
- Observer: 상태 변경 시 알림 ★★ (2022 3회 Q3)
- Iterator: 컬렉션 순차 접근 ★★ (2024 2회 Q10)
- Strategy: 알고리즘 캡슐화 교체
- Command: 요청을 객체로 캡슐화
- Template Method: 알고리즘 골격 정의
- Factory Method: 생성 위임
- Visitor: 알고리즘 분리 ★ (2023 2회 Q11)

**응집도 (높은 순서 암기: 기순통절시논우):**
1. 기능적(Functional)
2. 순차적(Sequential)
3. 통신적(Communicational)
4. 절차적(Procedural)
5. 시간적(Temporal)
6. 논리적(Logical)
7. 우연적(Coincidental)

**결합도 (낮은 순서 암기: 자스제외공내):**
1. 자료(Data) - 가장 낮음(좋음)
2. 스탬프(Stamp)
3. 제어(Control) ← 기출 자주
4. 외부(External)
5. 공통(Common)
6. 내용(Content) - 가장 높음(나쁨)

기출:
- 2025 1회 Q12: 결합도 → 내용, 스탬프, 공통
- 2024 1회 Q3: 응집도 높은 순 → ㄱ,ㄴ,ㄹ,ㄷ
- 2024 2회 Q16: 제어 결합도

**McCabe 복잡도:** V(G) = E - N + 2P (E=간선, N=노드, P=연결요소)

**테스트 커버리지:**
- 문장(Statement): 모든 구문 한 번 이상 실행
- 분기(Branch/Decision): 모든 분기 방향 실행
- 조건(Condition): 각 조건식 T/F 모두 실행
- 변경조건/결정(MC/DC): 조건 + 분기 결합 ★
- 다중조건(Multiple Condition): 모든 조건 조합

기출:
- 2025 2회 Q11: 분기 커버리지 테스트 경로
- 2024 3회 Q13: 문장/분기/조건
- 2024 1회 Q14: MC/DC 커버리지

#### 10_security.html — 보안 & 암호화
**출제 빈도: ★★★☆☆**

**암호화 알고리즘 분류표:**

대칭키 (비밀키):
- DES: 56비트, 1977년 (★ 2021 3회 Q10)
- 3DES: DES 3번 적용
- AES: 128/192/256비트, 1997년 NIST (★ 2024 2회 Q7)
- ARIA: 국산, KISA
- SEED: 국산, 128비트

비대칭키 (공개키):
- RSA: 소인수분해 기반 (★)
- ECC: 타원곡선 (★ 2023 2회 Q15)
- DSA: 전자서명

해시함수:
- MD5: 128비트 출력
- SHA-1: 160비트
- SHA-256: 256비트 ★
- HMAC: 해시 + 키

**보안 공격 유형:**
- 스니핑(Sniffing): 패킷 수동 도청 (2020 4회 Q7)
- 스푸핑(Spoofing): IP/MAC 위조
- XSS: Cross-Site Scripting
- CSRF: Cross-Site Request Forgery
- SQL Injection: 쿼리 조작
- Buffer Overflow: 버퍼 초과 덮어쓰기
- DoS/DDoS: 서비스 거부 공격
- APT: 지능형 지속 위협 (2024 1회 Q17)
- Rootkit: 권한 탈취 후 은닉 (2024 1회 Q15)
- Ransomware: 파일 암호화 후 금전 요구
- 스케어웨어(Scareware): 가짜 보안 경고 (2025 1회 Q4)

**접근 통제 모델:**
- MAC (강제적): 시스템이 정책 결정 (2023 3회 Q7)
- DAC (임의적): 소유자가 접근 결정
- RBAC (역할기반): 역할에 따라 접근 (★)

**AAA 보안 (2021 3회 Q2):**
- Authentication (인증): 신원 확인
- Authorization (인가): 접근 권한 부여
- Accounting (계정관리): 사용 기록

---

### Section E: 기출문제 모음 (2페이지)

#### 11_past_2024_2025.html — 2024~2025 기출문제
**수록 시험: 2025년 1~2회 + 2024년 1~3회 = 100문제**

UI 구조:
- 상단: 연도/회차 필터 탭
- 카테고리 필터: 전체 / 프로그래밍 / SQL / 네트워크 / OS·알고리즘 / SW공학·보안
- 문제 카드: 클릭 시 해설 아코디언 펼침
- 오답 체크: localStorage 저장
- 반복 출제 문제 ★ 태그

수록 문제 (확인된 기출):
2025년 1회: Q1~Q20 (세션하이재킹, ARP/RARP, 결합도, 디자인패턴, C코드 등)
2025년 2회: Q1~Q20 (서브넷계산, RR스케줄링, 람다, 포인터, 큐, SQL 등)
2024년 1회: Q1~Q20 (싱글톤, C비트연산, 정규화, 페이지교체, Abstract Factory 등)
2024년 2회: Q1~Q20 (반정규화, SRT, 포인터, 제어결합도, Iterator, IPSec, AES 등)
2024년 3회: Q1~Q20 (다형성, LRU, Smurf, static변수, DB무결성, VPN 등)

#### 12_past_2020_2023.html — 2020~2023 기출문제
**수록 시험: 2023년 1~3회 + 2022년 1~3회 + 2021년 1~3회 + 2020년 1~4회 = 240문제**

UI 구조 (11번과 동일 + 연도 필터 추가):
- 연도별 그룹핑 (2023 / 2022 / 2021 / 2020)
- 반복 출제 패턴 강조 표시

수록 문제 (확인된 기출 포함):
2023년 3회: chmod/linux, 재귀팩토리얼, UNION정렬, 관계대수, NAT, IaaS/PaaS/SaaS 등
2023년 2회: INSERT SQL, 스택, 해시, 암호화알고리즘, 드라이버/스텁, 선택정렬 등
2022년 3회: FLSM서브넷, 디자인패턴(Bridge/Observer), LRU, 관계대수기호 등
2021년 3회: Singleton, AAA보안, Grant, OSI계층, Factory Method 등
2020년 4회: IPv6, 페이지교체, 이상현상, GROUP BY SQL 등

---

## 디자인 방향

- Level-1 다크 네이비 헤더 + 흰 카드 스타일 유지
- **계산 문제 페이지**: Step별 컬러 박스 (Step 1 → Step 2 → ...)
- **코드 추적**: 신택스 하이라이팅 + 변수 변화 추적 테이블
- **공식 카드**: 형광 배경 강조 (`background: #fef9c3`)
- **기출 문제**: 아코디언 (클릭 → 해설 펼침) + 오답 체크
- **공식 암기표**: sticky 사이드바 또는 상단 고정
- **정렬 시각화**: CSS animation으로 배열 상태 표시

---

## 제작 순서

1. `index.html` — Level-2 대시보드
2. `06_network_ip.html` — IP 계산 ★ (가장 중요, 먼저)
3. `07_os_scheduling.html` — 스케줄링/페이지교체
4. `08_algorithm_trace.html` — 정렬/트리/스택
5. `01_c_language.html` — C 코드 추적
6. `02_java_language.html` — Java 코드 추적
7. `03_python_language.html` — Python 코드 추적
8. `04_sql_queries.html` — SQL 심화
9. `05_database_theory.html` — DB 이론
10. `09_sw_engineering.html` — SW공학
11. `10_security.html` — 보안
12. `11_past_2024_2025.html` — 최신 기출 (2024~2025)
13. `12_past_2020_2023.html` — 구 기출 (2020~2023)
