# MARCH AI

MARCH에서 확보한 원문을 요약·분류하고 근거를 검증하는 영역입니다. [제품 기획·디자인](https://github.com/march-my-archive/FE) · [BE](https://github.com/march-my-archive/BE) · [개발 흐름](CONTRIBUTING.md)

## 책임

- 설명문 등 확보된 입력에서 제목·요약·도메인·재료·단계·직접 인용을 구조화합니다.
- 스키마, 원문에 연속해 존재하는 인용, 숫자·분량 일치를 검증합니다. 확보 범위를 결과와 함께 넘깁니다.
- Luna, Gemini, 규칙 기반 발췌를 비교합니다. 토큰·지연·실패까지 포함한 비용을 기록합니다.

v0.2 파일럿 기본은 Luna입니다. [동일 원문 실측과 한계](https://github.com/march-my-archive/FE/blob/main/docs/DECISIONS.md#2-어떤-모델이-요약에-더-효율적인가)는 제품 결정 기록에 있습니다. 초기 저장소에는 담당 범위와 공통 CI를 배치했습니다. 분석 코드를 옮길 때는 합성 fixture와 스키마 검사를 CI에 연결합니다. 공급자 실호출은 별도 실험으로 실행합니다.
