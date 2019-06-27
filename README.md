# Rules for Git

* 이 페이지는 각자의 저장소를 관리하기 위한 가이드 문서입니다.
* 개인 당 하나의 저장소(repository)를 사용합니다.
* 원활한 소스 공유를 위해, 저장소의 이름에 본인의 닉네임(혹은 이름)과 주로 사용하시는 언어를 표시해 주세요. (ex. C, CPP, JAVA)
* 각자의 저장소는 branch 생성, merge, PR등 git 기능을 사용하셔서 자유롭게 관리하시면 됩니다.
* 다만, 아래의 구조를 지켜주세요.
```
# JAVA일 경우
(저장소 ROOT)/
├── (문제 번호)
│   └── Solution.java
├── (문제 번호)
│   └── Solution.java
├── .git
└── .gitignore

# C, CPP일 경우
(저장소 ROOT)/
├── (문제 번호).cpp
├── (문제 번호).cpp
├── .git
└── .gitignore

```
