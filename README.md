# javascript-lunch

우아한테크코스 레벨1 점심 뭐 먹지 미션

# 1단계 - 음식점 목록

## 🎯 기능 요구 사항

캠퍼스 주변의 점심 식사 스팟 목록을 관리하는 앱을 만든다.

- 음식점 목록을 확인할 수 있다.
  - 카테고리별로 필터링해서 확인할 수 있다.
  - 이름순/거리순으로 정렬해서 확인할 수 있다.
- 음식점 목록에 새로운 음식점을 추가할 수 있다.
  - 음식점의 카테고리, 이름, 거리(도보 이동 시간), 설명, 참고 링크를 입력해서 추가할 수 있다.
  - 카테고리, 거리는 셀렉트 박스, 이름/설명/참고 링크는 텍스트 인풋을 사용한다.
  - 카테고리, 이름, 거리는 입력 필수.
    - 카테고리는 "한식", "중식", "일식", "아시안", "양식", "기타" 중 하나를 선택한다.
    - 거리는 캠퍼스로부터 도보로 걸리는 시간(분). 5, 10, 15, 20, 30 중 하나를 선택한다.
  - 설명, 참고 링크는 옵션. 입력하지 않아도 음식점을 추가할 수 있어야 한다.
  - 입력값이 잘못되었을 때 사용자에게 알려주는 방식은 자유롭게 구현한다.
- 새로고침해도 추가한 음식점 정보들이 유지되어야 한다.


# 2단계 - 자주 가는 음식점

## 🎯 기능 요구 사항

음식점의 상세 정보를 확인하고, 자주 가는 음식점으로 지정할 수 있는 기능을 추가한다.

- 음식점 상세 정보를 확인할 수 있다.
  - 카테고리, 이름, 거리, 설명, 참고 링크를 확인할 수 있다.
  - 음식점을 삭제할 수 있다.
- 자주 가는 음식점을 추가하고 목록으로 확인할 수 있다.
  - 음식점 목록에서 자주 가는 음식점을 추가할 수 있다.
  - 음식점 상세 정보에서 자주 가는 음식점으로 추가할 수 있다.
  - 자주 가는 음식점 탭에서 추가한 음식점 목록을 확인할 수 있다.
- 새로고침해도 추가한 정보들이 유지되어야 한다.

# 실행 방법

```

npm run start

```

# 배포 링크

[링크](https://yeopto.github.io/javascript-lunch)
