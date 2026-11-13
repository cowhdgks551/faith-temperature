# 운영진 관리자 설정

1. Supabase 대시보드에서 Authentication > URL Configuration으로 이동합니다.
2. Site URL을 `https://faith-temperature.onrender.com`으로 설정합니다.
3. Redirect URLs에도 `https://faith-temperature.onrender.com`을 추가합니다.
4. 신앙온도계 사이트에서 `운영진 관리` 탭을 엽니다.
5. 관리자 허용목록에 등록된 이메일로 `처음 관리자 계정 만들기`를 진행합니다.
6. 수신한 이메일의 인증 링크를 연 뒤 사이트로 돌아와 이메일과 비밀번호로 로그인합니다.

관리자 로그인 후 응답 목록, 이름 검색, 평균 온도, 온도 분포 및 CSV 다운로드를 사용할 수 있습니다.

주의: 관리자 허용목록에 등록되지 않은 이메일은 관리자 권한을 받을 수 없습니다. 비밀번호나 Supabase 비밀 키를 공개 저장소에 올리지 마세요.
