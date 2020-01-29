## 참고 URL

블로그: https://dzone.com/articles/deploy-spring-boot-app-to-gcp-app-engine<br />
-> '3. Deploy to Standard Environment'<br />
깃허브: https://github.com/mydeveloperplanet/mygoogleappengineplanet/tree/feature/standardenv<br />

## 작업 순서

사용할 프로젝트를 설정: gcloud config set project joshua-crasb<br />
소스 코드 가져와 병합하기: git pull<br />
앱을 테스트: mvn appengine:run<br />
앱을 배포: mvn -DskipTests appengine:deploy<br />
배포된 애플리케이션: http://joshua-crasb.appspot.com/<br />
