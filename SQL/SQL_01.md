# SQL_01

## SQL과 관계형 데이터베이스(RDB)
- **SQL**이란 **S**tructured **Q**uery **L**anguage의 약자로,   
관계형 데이터베이스가 이해할 수 있는 구조화된 질의어
- **RDB**는 **R**elational **D**ata **B**ase의 약자로,   
행과 열로 구성된 테이블이 다른 테이블과 관계를 맺고 모여있는 집합체

## 관계형 테이블
- 관계형 테이블은 관계형 데이터베이스에 저장되는 데이터의 집합으로,   
행(row)과 열(column)로 구성되어 있다.
- 관계형 테이블의 관계는 **1:1, 1:N, N:N** 세 가지 형태로,   
테이블 간의 연결이 가능하다는 것을 의미한다.

## SQL 기본 명령어의 분류
SQL 기본 명령어는   
데이터 정의어(DDL, Data Definition Language),   
데이터 조작어(DML, Data Manipulation Language),   
데이터 제어어(DCL, Data Control Language),   
트랜젝션 제어어(TCL, Transaction Control Language)   
**4가지**로 분류된다.
### 데이터 정의어(DDL, Data Definition Language)
- 테이블의
  - 생성
  - 변경
  - 삭제

### 데이터 조작어(DML, Data Manipulation Language)
- 데이터의
  - 삽입
  - 조회
  - 수정
  - 삭제

### 데이터 제어어(DCL, Data Control Language)
- 데이터 접근 권한의
  - 부여
  - 제거

### 트랜젝션 제어어(TCL, Transaction Control Language)
- 데이터 조작어(DML)의
  - 실행
  - 취소
  - 임시저장

# 내가 주로 공부할 것
데이터베이스에서 데이터를 조회한 후 분석하기 위한  DML
