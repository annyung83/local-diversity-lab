# 관리자 로그인
https://annyung83.github.io/local-diversity-lab/#admin

## 주제 변경 방법
Ctrl+F로 아래 검색: TOPICS
javascriptconst TOPICS = ['지역정책', '이주·이민', '공동체 연구', '도시사회학', '현장 메모'];

수정 방법
주제 추가 — 따옴표로 감싸서 쉼표 뒤에 추가
javascriptconst TOPICS = ['지역정책', '이주·이민', '공동체 연구', '도시사회학', '현장 메모', '새주제'];
주제 삭제 — 해당 항목과 쉼표를 지우기
javascriptconst TOPICS = ['지역정책', '이주·이민', '공동체 연구', '도시사회학'];
주제명 변경 — 따옴표 안의 텍스트만 바꾸기

주제별 목표 글 수도 함께 수정
바로 아랫줄에 이런 코드도 있어요:
javascriptconst TOPIC_GOALS = { '지역정책': 10, '이주·이민': 12, ... };
주제를 추가하거나 이름을 바꾸면 여기도 함께 수정해야 사이드바의 진척 막대가 제대로 작동합니다.
