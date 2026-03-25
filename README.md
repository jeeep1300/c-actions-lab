이 실습에서 배우는 내용은 다음과 같습니다.
C 언어 소스코드를 GitHub 저장소에 올리기 
push 이벤트로 GitHub Actions 자동 실행하기  
Ubuntu runner에서 gcc로 컴파일하기  
실행 결과를 로그로 확인하기 
GitHub Actions의 기본 YAML 구조 이해하기 
GitHub Actions는 코드 변경 시 빌드, 테스트, 배포를 자동화하는 CI/CD 플랫폼입니다. 저장소에 push가 발생하면 워크플로를 자동 실행하도록 구성할 수 있습니다. 


c-actions-lab/
├─ src/
│  └─ main.c
├─ Makefile
├─ README.md
└─ .github/
   └─ workflows/
      └─ c-build.yml

