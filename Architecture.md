.
└── defaultdependencies
    ├── DefaultDependenciesApplication.java
    ├── global
    │   ├── config
    │   └── exception
    └── module
        ├── member
        │   ├── application
        │   │   └── MemberService.java
        │   ├── domain
        │   │   ├── Member.java
        │   │   ├── MemberRepository.java
        │   │   ├── cond
        │   │   │   └── FollowerCond.java
        │   │   └── query
        │   │       ├── MemberRepositoryCustom.java
        │   │       └── MemberRepositoryCustomImpl.java
        │   ├── dto
        │   │   ├── request
        │   │   │   └── ApiRequest.java
        │   │   └── response
        │   │       └── ApiResponse.java
        │   ├── exception
        │   ├── presentation
        │   │   └── MemberController.java
        │   └── utils
        │       └── MemberServiceUtils.java
        └── recipe
            ├── application
            ├── domain
            │   ├── cond
            │   └── query
            ├── dto
            │   ├── request
            │   │   └── ApiRequest.java
            │   └── response
            │       └── ApiResponse.java
            ├── exception
            ├── presentation
            └── utils