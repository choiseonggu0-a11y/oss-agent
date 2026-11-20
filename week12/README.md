# boxoffice — KOBIS 박스오피스 조회 스킬

## 하는 일
KOBIS 일별 박스오피스를 조회한다. 날짜를 받으면 1위 영화 제목을 알려주고, 날짜와 영화 제목을 받으면 그 영화의 관객 수를 알려 준다.

## 들어 있는 파일
- .claude/skills/boxoffice/SKILL.md
- .claude/skills/boxoffice/scripts/boxoffice.py
- .claude/skills/boxoffice/LICENSE

## 필요한 것
secret.py:KOBIS에서 정보를 받으려면 KEY가 필요한데 KEY를 노출시키면 안되니까 secret.py가 필요함.
tool.py:실제로 요청을 보낸는 함수가 tools.py에 있다.
requests 패키지:KOBIS같은 인터넷에 요청을 보내는 도구다. 그래서 필요함.

## 설치
boxoffice 폴더를 tools.py 가 있는 프로젝트 폴더의 .claude\skills\ 안에 둔다. Claude Code 는 이 위치에 있는 폴더만 스킬로 읽고, 스킬을 쓸 때 boxoffice.py 가 같은 폴더의 tools.py 를 호출한다.

## 바깥으로 요청하는 곳
KOBIS로만 요청한다.

## 키
키는 secret.py에 넣는다. 이 저장소에는 키가 없다.

## 권한
없다. 실행할 때 python 명령을 실행해도 되는지 묻는다.

## 라이선스
\week12\.claude\skills\boxoffice가 위치.
MIT라이선스이다. 누구나 무료로 쓰고, 복사, 고치기, 합치기, 배포, 판매도 가능.
조건은 저작권 표시와 이 허가 문구를 함께 넣어야함.
문제생겨도 책임은 안진다.
저작권자: Copyright (c) 2026 최성규