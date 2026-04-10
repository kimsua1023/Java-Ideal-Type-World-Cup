# 🏆 교수님 이상형 월드컵 (Java Swing Project)
> 사용자의 몰입감을 높이는 UX 요소가 포함된 Java 기반 토너먼트 게임

### 🛠 Key Features
- **Dynamic UX**: `javax.swing.Timer`를 활용한 타이핑 애니메이션 및 2초 간격 배경 슬라이드 구현.
- **Robust Logic**: `Collections.shuffle`을 이용한 랜덤 대진 생성 및 토너먼트 알고리즘 구현.
- **Data Tracking**: `HashMap`을 이용해 각 항목의 선택 횟수를 기록하고 실시간 통계(Statistics) 창 제공.
- **Layout Management**: `GridBagLayout`과 `BorderLayout`을 중첩 사용하여 해상도에 대응하는 UI 설계.

### 💡 문제 해결 경험
- **컴포넌트 간 데이터 전달**: `StartClass`에서 선택한 라운드 정보를 `GameClass`로 안전하게 전달하기 위해 생성자 주입 방식을 사용했습니다.
- **리소스 최적화**: `dispose()` 호출 시 실행 중인 `Timer`를 명확히 정지시켜 메모리 누수를 방지했습니다.
