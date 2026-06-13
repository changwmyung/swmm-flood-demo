# SWMM Web Demo — 도시 우수관망 침수 시뮬레이터

EPA SWMM의 동역학파(dynamic-wave) 라우팅 알고리즘을 브라우저에서 실시간 구현한 시연용 시뮬레이터입니다.
소유역 유출 → 노드 연속방정식 → 관거 Manning·동역학파 흐름 → 과부하 시 월류(침수)의
SWMM 라우팅 절차를 그대로 따릅니다.

**라이브 데모:** https://changwmyung.github.io/swmm-flood-demo/

- 단일 HTML 파일, 의존성·서버 없음 (더블클릭으로 실행)
- 강우강도(30~160 mm/h) 프리셋으로 약한 비 → 극한강우 시 침수 거동 시연
- 시연용 소규모 배수분구 1개(7노드)

알고리즘 출처: [USEPA/Stormwater-Management-Model](https://github.com/USEPA/Stormwater-Management-Model) `src/solver/dynwave.c`
