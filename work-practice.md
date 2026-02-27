# 사우나 사업 리서치 — Work Practice 🔄

## 서브에이전트 협업 순서

```
[요청 수신]
    ↓
1. Project Lead
   - Shawn 요청 확인
   - project-note.md에서 사업 방향성 조회 & 업데이트
   - 주제 확정 → workspace/brief.md에 브리프 작성
    ↓
2. Market Analyst
   - brief.md 참조
   - 시장 환경 / 소비 트렌드 / 규제 분석
   - 결과 → workspace/market_output.md
    ↓
3. Industry Analyst
   - brief.md + market_output.md 참조
   - 산업 구조 / 경쟁 / 벤치마크 분석
   - 결과 → workspace/industry_output.md
    ↓
4. Business Modeler
   - brief.md + market_output.md + industry_output.md 참조
   - 수익 모델링 / 투자비 / P&L 시뮬레이션
   - 결과 → workspace/business_output.md
    ↓
5. Research Director
   - 모든 output 파일 수합
   - 상세 노트 → notes/YYYY-MM-DD.md
   - 요약 브리핑 → 텔레그램 전달
    ↓
6. 정리
   - workspace/ 내 임시 output 파일 삭제
   - project-note.md 갱신 (새로운 방향성 반영)
```

## 중간 산출물 파일 규칙
- **경로**: `shawn/sauna-business/workspace/`
- **파일명**: `brief.md`, `market_output.md`, `industry_output.md`, `business_output.md`
- **수명**: 최종 노트 완성 후 삭제 (1회성)
- **형식**: 각 에이전트 지침(md)의 산출물 포맷을 따름

## 브리프 파일 구조 (brief.md)
```
# 사우나 리서치 Brief — YYYY-MM-DD

**주제**: [리서치 주제]
**배경**: [왜 이 주제를 조사하는가]
**핵심 질문**: [답해야 할 질문들]
**사업 방향성 요약**: [project-note.md 기반]
**분석 유형**: [시장 탐색 / 모델 비교 / 입지 분석 / 재무 시뮬레이션]
```
