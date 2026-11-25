# 하진이 첫돌 참석 답장

1. 압축을 풀고 그 안의 파일을 GitHub 저장소의 최상위에 올립니다.
2. Netlify의 Add new project → Import an existing project에서 저장소를 연결합니다. 게시 폴더와 함수 경로는 netlify.toml에 들어 있습니다.
3. Project configuration → Environment variables에서 ADMIN_KEY를 추가하고 값으로 사용할 관리자 비밀번호를 입력합니다. Functions 범위를 포함하고 프로덕션에 적용한 뒤 다시 배포합니다.
4. 프로젝트 이름을 설정하면 사용 가능한 이름으로 .netlify.app 주소를 받을 수 있습니다.
5. 가족에게는 기본 주소를 보내고, 응답 현황은 같은 주소 뒤에 /?admin을 붙여 확인합니다.

새 Netlify 사이트에는 빈 응답 목록이 생성됩니다. 기존 사이트의 데이터는 이 파일에 들어 있지 않습니다.
