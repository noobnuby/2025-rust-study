0. 오리엔테이션
  * IDE 셋업
  * 강의 목차 안내
1. 러스트 소개
  * 왜 만들어졌냐?
    - 저수준 코드를 고수준 언어 기능을 쓰면서 짜기 위해
    - "까다로운 툴체인의 세세한 특징" - C++ 컴파일러.....
  * 다른 언어와 비교했을 때 강점
    - 타입 시스템
    - 레퍼런스 추적
    - 가변성 관리
    - 메모리 안전성
  * 교육자들의 프로그래밍 경험 조사
  * Borrowck의 의미
    - 인터넷 밈과 비교
    - 왜 얘랑 싸우면 안되는가?
2. 프로그래밍 기초
  * 메모리 할당
    - 종이 노트에 비유
  * Stack vs Heap
    - 옆반 칠판 vs 노트로 비유
  * CPU 캐시
    - 공책이 더 빠른 이유
  * "프로그래밍에선 정보도 자원이다"
    - 메모리 복사
  * 포인터
    - 복사를 안할려면 위치를 대신 알려주면 된다
3. Cargo 기초 사용법
  * 새 프로젝트 생성
    - 왜 파이썬처럼 main.py 하나만으론 부족한가
  * Cargo.toml
    - requirements.txt 또는 build.gradle과 비교
  * lib.rs vs main.rs
4. 러스트 기초 문법
  * println!
  * 매크로 떡밥
    - println! vs printf 비교
  * 변수 선언
    - "노트 위의 그림"에 붙이는 "이름"
  * 기본 자료형
    - char u8 u16...
    - 왜 double float, byte short int long이 말장난인가
    - long long int.....
  * shadowing vs mut
  * 주석
  * 함수
    - f(x) = 2x + 15와 비교
  * 레퍼런스
    - 복사를 하지 않는 법
  * Borrow Checker와 소유권
    - 왜 정보는 물건인가?
    - Alias Tracking
  * 슬라이스 타입
    - Wide Pointer
  * 제어 흐름문1
    - if
    - 반복문
  * struct
  * enum
    - Option vs Null
    - Result vs Exception
  * 타입 이론 개요
    * 합 vs 곱 타입
    * invariant
    * 경우의 수
  * 제어 흐름문2
    - match
    - if let
    - Let Some(a) = .. else 
5. up/down 게임
  - use 기초
6. 러스트 심화 문법
  * impl T
    - Orphan rule
  * Trait
    - 게임, DB 등을 이용한 예시
    - Dependency Injection?
  * 제너릭
    - Trait 바운드
    - dyn
    - Box
  * 라이프타임
7. 프로젝트 실습 - Extra
  - 아이디어: 미정, 투표로 받을 것
  - Cargo 심화 사용법
    - 종속성 추가
    - crate란?
    - 컴파일 엔트리포인틑
  - 모듈
    - 모듈 가시성 (public member in private module)
    - use와 모듈
    - mod.rs vs "name".rs