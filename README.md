# 매곡축제 MBTI 키링 부스

아이패드 가로 화면에 맞춘 1~6학년 성향 체험 웹앱입니다.
정식 MBTI 검사가 아닌 축제용 활동입니다. 이름과 검사 결과를 서버에 저장하지 않습니다.

## 구성
- index.html / style.css / app.js: 웹앱
- vercel.json: Vercel 정적 배포 설정

## GitHub에 업로드
1. 새 저장소를 만듭니다. 이름 예: maegok-mbti-keyring
2. 이 폴더 안의 파일들을 저장소 최상위에 업로드하고 Commit changes를 누릅니다.
3. ZIP 파일 자체가 아니라 압축을 푼 파일들을 올립니다.

## Vercel 배포
1. Vercel에 로그인하고 Add New → Project를 선택합니다.
2. Import Git Repository에서 위 저장소를 선택합니다.
3. Framework Preset: Other, Root Directory: 저장소 최상위.
4. 별도 설치나 빌드가 필요 없습니다. vercel.json 설정을 사용합니다.
5. Deploy를 누르고 생성된 주소를 아이패드 Safari에서 엽니다.

## GitHub Pages로 배포하는 방법
공개 저장소의 Settings → Pages에서 Deploy from a branch를 선택합니다.
Branch: main / Folder: /(root)를 선택하고 Save를 누릅니다.

## 음성 및 효과음
읽어주기는 기기의 기본 한국어 음성을 사용합니다. 효과음은 답 선택 시와 결과 표시 시 재생됩니다.
아이패드 볼륨과 무음 설정을 확인하세요. 상단 효과음 버튼으로 효과음만 끌 수 있습니다.

공식 안내:
https://vercel.com/docs/git
https://vercel.com/docs/project-configuration/vercel-json
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
