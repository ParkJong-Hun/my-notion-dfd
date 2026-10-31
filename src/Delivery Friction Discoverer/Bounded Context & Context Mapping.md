# Bounded Context & Context Mapping

<aside>
💡

DDD에서 나온 개념으로, 시스템이나 조직 내의 다양한 경계와 그 경계들 사이의 관계를 지도처럼 그리는 기법.

</aside>

- Customer-Supplier
    - 한 팀의 작업 결과가 다른 팀의 작업의 입력
- Conformist
    - 상대가 주는 것을 그대로 받아서 써야하는 상태
- Anti-Corruption Layer
    - 타 부서의 나쁜 스펙이나 레거시가 우리 시스템을 오염시키지 않도록 중간에 변환/자동화 레이러를 두는 방식
    - ACL, 완충 계층이라고 함

---

## 日本語

<aside>
💡

DDD（ドメイン駆動設計）由来の概念で、システムや組織内に存在するさまざまな境界と、境界間の関係を地図のように描く手法。

</aside>

- Customer-Supplier
    - あるチームの成果物が別チームの作業の入力となる関係
- Conformist
    - 相手が提供するものを、そのまま受け取って使うしかない状態
- Anti-Corruption Layer
    - 他部門の悪い仕様やレガシーが自分たちのシステムを汚染しないよう、中間に変換／自動化レイヤーを置くやり方
    - ACL（緩衝層）とも呼ぶ