# myflow-legal

[MyFlow](https://myflow.ai) 앱의 공개 법률 문서를 GitHub Pages로 서빙합니다.

- 개인정보처리방침: https://keonnno.github.io/myflow-legal/privacy/
- 서비스 이용약관: https://keonnno.github.io/myflow-legal/terms/

## 정본은 여기가 아닙니다

본문의 정본은 제품 저장소 `docs/legal/*.md`이고, 이 저장소의 파일은
`npm run gen:legal-payload`가 산출한 `docs/legal/firestore-payload/*.md`에
Jekyll front matter만 얹은 **배포 사본**입니다.

문서를 고칠 때는 정본을 고친 뒤 payload를 재생성해 여기에 복사하세요.
같은 payload가 앱 안(`system_configs/legal`)에도 들어가므로, 웹과 앱이
어긋나지 않으려면 두 곳을 같은 회차에 갱신해야 합니다.
