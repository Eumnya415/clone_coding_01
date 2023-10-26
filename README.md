# Personal_project (2) : DB + MyBatis 연동

23년 10월 개인 프로젝트 과제 - `DB+MyBatis` 연동<br>
풀스택 3기 교육과정에서의 개인 프로젝트 과제물 업로드 (`23년 10월`)<br>
주소록 저장 프로그램 제작 (`CRUD`)
<BR><BR>

## 사용한 기술 스택 

### MySQL
`MySQL`은 관계형 데이터베이스 관리 시스템(`RDBMS`)으로, 데이터 저장 및 관리 역할을 수행한다. 주소록 프로그램에서의 주요 역할은 다음과 같다.
* 데이터 저장: 주소록 애플리케이션의 정보를 효율적으로 저장한다. 데이터는 테이블 형태로 구조화되고 `SQL` 쿼리를 사용하여 관리된다.
* 데이터 검색: `MyBatis`와 함께 `DB`에서 필요한 정보를 검색하고, 결과를 `Java` 객체로 반환합니다.
* 데이터 보관: 데이터는 `MySQL DB`에 지속적으로 보관되며, 향후에도 액세스 가능하다.

### Java
`Java`는 주소록 프로그램의 핵심 언어로 사용되며, 주요 기능은 다음과 같다.
* 비즈니스 로직: 주소록 애플리케이션의 주요 기능 및 동작을 구현한다.
* 데이터 모델: `DB`의 레코드를 `Java` 객체로 매핑하고, `Java` 클래스를 통해 데이터를 다룬다. 이 예제에서는 `Contact` 클래스를 사용하여 주소록 항목을 나타낸다.
* 데이터 액세스: `MyBatis`를 사용하여 데이터베이스와 상호 작용한다. 데이터를 `DB`에 저장, 검색, 수정, 및 삭제한다. (`CRUD`)

### MyBatis
`MyBatis`는 `DB`와 `Java` 객체 사이의 매핑 및 상호 작용을 관리한다. 주요 역할은 다음과 같다.
* `ORM` (객체-관계 매핑): `MyBatis`는 데이터베이스 레코드를 `Java` 객체에 매핑하고, 이 객체를 데이터베이스 레코드로 돌려주는 역할을 한다. 이것을 통해 `Java` 코드에서 `SQL`을 직접 작성하지 않아도 된다.
* `DB` 연결 관리: `MyBatis`는 데이터베이스 연결 및 세션 관리를 담당한다. `DB` 커넥션풀 및 세션 관리를 통해 애플리케이션의 성능을 향상시키고, 리소스 유출을 방지한다.
* `SQL` 쿼리 정의: `MyBatis`는 `SQL` 쿼리를 `XML` 또는 애너테이션을 통해 정의하고, 이를 `DB`에 보내고 결과를 반환하는 역할을 한다.

  
## 작성 시 신경 쓴 부분
*`Java`, `MySQL` 및 `MyBatis`를 사용하여 주소록 애플리케이션을 생성하려면 DB 설정, `MyBatis` 구성, 데이터 액세스를 위한 `Java` 클래스 생성 및 애플리케이션 구축을 포함한 여러 단계가 필요한데, 각 단계에 맞게 설정하기 위해 신경을 썼다.
* 위의 단계를 순차적으로 진행하여 최종 구현이 되는지 고려하였다.

## 회고
* 모두 아직 익숙치 않지만, `MyBatis`는 처음이라 더 힘들었다. 툴에 더 익숙해져야 겠다고 생각했다. 특히 Java만 다루는 것이 아니라, 각 스택에 맞게끔 운용을 해야 했다. 스택에 대한 개념을 알고, 각 스택이 어떻게 작동하는지 구조도를 파악해야 겠다.






