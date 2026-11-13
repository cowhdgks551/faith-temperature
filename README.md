# 등달자 신앙온도계

등달자 수련회에서 사용하는 신앙 돌아보기 설문 웹사이트입니다.

## 구성
- `index.html`: 설문 화면 및 운영진 관리 화면
- Supabase Edge Functions: 설문 응답 저장 및 관리자 권한 확인
- Supabase Database: 응답 및 관리자 정보 저장

## 배포
- 공개 주소: https://faith-temperature.onrender.com
- GitHub: https://github.com/cowhdgks551/faith-temperature
- 호스팅: Render Static Site

`main` 브랜치에 변경 사항을 푸시하면 Render가 자동 배포합니다.

## 설문
10개 문항을 각 1~4점으로 계산하며, 총점 40점을 100도 기준으로 환산합니다. 회고와 내년 목표 문항은 점수에 반영하지 않습니다.
