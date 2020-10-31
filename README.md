## 참고 URL

블로그: https://dzone.com/articles/deploy-spring-boot-app-to-gcp-app-engine<br />
-> '3. Deploy to Standard Environment'<br />
깃허브: https://github.com/mydeveloperplanet/mygoogleappengineplanet/tree/feature/standardenv<br />

## 작업 순서 (Cloud Shell)

사용할 프로젝트를 설정: **gcloud config set project joshua-crasb**<br />
작업 디렉토리로 이동: **cd my-app-backend-gae-standard/**<br />
소스 코드 가져와 병합하기: **git pull**<br />
앱을 빌드: **mvn clean package**<br />
앱을 테스트: **mvn appengine:run**<br />
앱을 배포: **mvn -DskipTests appengine:deploy**<br />
배포된 애플리케이션: **http://joshua-crasb.appspot.com/**<br />

[201031 작업내용]
사용할 프로젝트를 설정: **gcloud config set project annular-aria-293902**<br />
(처음에만) 기존 저장소를 Clone하기: **git clone https://github.com/gpe-joshua/my-app-backend-gae-standard**<br />
작업 디렉토리로 이동: **cd my-app-backend-gae-standard/**<br />
(코드 변경시) 소스 코드 가져와 병합하기: **git pull**<br />
앱을 빌드: **mvn clean package**<br />
앱을 테스트: **mvn appengine:run**<br />
앱을 배포: **mvn -DskipTests appengine:deploy**<br />
배포된 애플리케이션: **https://annular-aria-293902.ue.r.appspot.com**<br />
