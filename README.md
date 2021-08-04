# Oracle_SQL

## PART 1「입문」 SQL 첫발 내딛기
<br>

1. select 절<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1-1. 테이블에서 특정 열(COLUMN) 선택하기<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1-2. 테이블에서 모든 열(COLUMN) 출력하기<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1-3. 컬럼 별칭을 사용하여 출력되는 컬럼명 변경하기<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1-4. 연결 연산자 사용하기(||)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1-5. 중복된 데이터를 제거해서 출력하기(DISTINCT)<br>

2. order by절<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2-1. 데이터를 정렬해서 출력하기(ORDER BY)<br>

3. where 절<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3-1. WHERE절 배우기 1(숫자 데이터 검색)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3-2. WHERE절 배우기 2(문자와 날짜 검색)<br>

4. 연산자 다루기<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4-1. 산술 연산자 배우기(*, /, +, -)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4-2. 비교 연산자 배우기 1(〉, 〈, 〉=,〈=, =, !=,〈〉, ^=)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4-3. 비교 연산자 배우기 2(BETWEEN AND)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4-4. 비교 연산자 배우기 3(LIKE)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4-5. 비교 연산자 배우기 4(IS NULL)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4-6. 비교 연산자 배우기 5(IN)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4-7. 논리 연산자 배우기(AND, OR, NOT)<br>


## PART 2「초급」 SQL 기초 다지기
<br>

5. 문자열 다루기<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5-1. 대소문자 변환 함수 배우기(UPPER, LOWER, INITCAP)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5-2. 문자에서 특정 철자 추출하기(SUBSTR)  <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5-3. 문자열의 길이를 출력하기(LENGTH)  <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5-4. 문자에서 특정 철자의 위치 출력하기(INSTR)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5-5. 특정 철자를 다른 철자로 변경하기(REPLACE)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5-6. 특정 철자를 N개 만큼 채우기(LPAD, RPAD)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5-7. 특정 철자 잘라내기(TRIM, RTRIM, LTRIM)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5-8. 반올림해서 출력하기(ROUND)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5-9. 숫자를 버리고 출력하기(TRUNC)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5-10. 나눈 나머지 값 출력하기(MOD)<br>

6. 날짜 다루기<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6-1. 날짜 간 개월 수 출력하기(MONTHS_BETWEN)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6-2.  개월 수 더한 날짜 출력하기(ADD_MONTHS)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6-3.  특정 날짜 뒤에 오는 요일 날짜 출력하기(NEXT_DAY)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6-4.  특정 날짜가 있는 달의 마지막 날짜 출력하기(LAST_DAY)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6-5.  문자형으로 데이터 유형 변환하기(TO_CHAR)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6-6.  날짜형으로 데이터 유형 변환하기(TO_DATE)<br>

7. 데이터 변환<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7-1. 암시적 형 변환 이해하기<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7-2. NULL 값 대신 다른 데이터 출력하기(NVL, NVL2)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7-3. IF문을 SQL로 구현하기 1(DECODE)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7-4. IF문을 SQL로 구현하기 2(CASE)<br>

8. 집계함수<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8-1. 최대값 출력하기(MAX)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8-2. 최소값 출력하기(MIN)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8-3. 평균값 출력하기(AVG)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8-4. 토탈값 출력하기(SUM)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8-5. 건수 출력하기(COUNT)<br>

9. 데이터 분석함수<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9-1. 데이터 분석 함수로 순위 출력하기 1(RANK)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9-2. 데이터 분석 함수로 순위 출력하기 2(DENSE_RANK)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9-3. 데이터 분석 함수로 등급 출력하기(NTILE)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9-4. 데이터 분석 함수로 순위의 비율 출력하기(CUME_DIST)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9-5. 데이터 분석 함수로 데이터를 가로로 출력하기(LISTAGG)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9-6. 데이터 분석 함수로 바로 전 행과 다음 행 출력하기(LAG, LEAD)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9-7. COLUMN을 ROW로 출력하기 1(SUM+DECODE)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9-8. COLUMN을 ROW로 출력하기 2(PIVOT)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9-9. ROW를 COLUMN으로 출력하기(UNPIVOT)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9-10. 데이터 분석 함수로 누적 데이터 출력하기(SUM OVER)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9-11. 데이터 분석 함수로 비율 출력하기(RATIO_TO_REPORT)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9-12. 데이터 분석 함수로 집계 결과 출력하기 1(ROLLUP)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9-13. 데이터 분석 함수로 집계 결과 출력하기 2(CUBE)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9-14. 데이터 분석 함수로 집계 결과 출력하기 3(GROUPING SETS)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9-15. 데이터 분석 함수로 출력 결과 넘버링 하기(ROW_NUMBER)<br>

## PART 3「중급」 SQL 실력 다지기
<br>

10. 출력되는 행 제한하기<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;10-1. 출력되는 행 제한하기 1(ROWNUM)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;10-2. 출력되는 행 제한하기 2(Simple TOP-n Queries)<br>

11. 테이블 병합<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;11-1. 여러 테이블의 데이터를 조인해서 출력하기 1(EQUI JOIN)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;11-2. 여러 테이블의 데이터를 조인해서 출력하기 2(NON EQUI JOIN)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;11-3. 여러 테이블의 데이터를 조인해서 출력하기 3(OUTER JOIN)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;11-4. 여러 테이블의 데이터를 조인해서 출력하기 4(SELF JOIN)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;11-5. 여러 테이블의 데이터를 조인해서 출력하기 5(ON절)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;11-6. 여러 테이블의 데이터를 조인해서 출력하기 5(USING절)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;11-7. 여러 테이블의 데이터를 조인해서 출력하기 6(NATURAL JOIN)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;11-8. 여러 테이블의 데이터를 조인해서 출력하기 7(LEFT/RIGHT OUTER JOIN)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;11-9. 여러 테이블의 데이터를 조인해서 출력하기 8(FULL OUTER JOIN)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;11-10. 집합 연산자로 데이터를 위아래로 연결하기 1(UNION ALL)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;11-11. 집합 연산자로 데이터를 위아래로 연결하기 2(UNION)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;11-12. 집합 연산자로 데이터의 교집합을 출력하기(INTERSECT)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;11-13. 집합 연산자로 데이터의 차이를 출력하기(MINUS)<br>

12. 서브쿼리<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;12-1. 서브 쿼리 사용하기 1(단일행 서브쿼리)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;12-2. 서브 쿼리 사용하기 2(다중 행 서브쿼리)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;12-3. 서브 쿼리 사용하기 3(NOT IN)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;12-4. 서브 쿼리 사용하기 4(EXISTS와 NOT EXISTS)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;12-5. 서브 쿼리 사용하기 5(HAVING절의 서브 쿼리)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;12-6. 서브 쿼리 사용하기 6(FROM절의 서브 쿼리)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;12-7. 서브 쿼리 사용하기 7(SELECT절의 서브 쿼리)<br>

13. 테이블 수정하기<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;13-1. 데이터 입력하기(INSERT)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;13-2. 데이터 수정하기(UPDATE)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;13-3. 데이터 삭제하기(DELETE, TRUNCATE, DROP)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;13-4. 데이터 저장 및 취소하기(COMMIT, ROLLBACK)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;13-5. 데이터 입력, 수정, 삭제 한번에 하기(MERGE)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;13-6. 락(LOCK) 이해하기<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;13-7. SELECT FOR UPDATE절 이해하기<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;13-8. 서브 쿼리를 사용하여 데이터 입력하기<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;13-9. 서브 쿼리를 사용하여 데이터 수정하기<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;13-10. 서브 쿼리를 사용하여 데이터 삭제하기<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;13-11. 서브 쿼리를 사용하여 데이터 합치기<br>

14. 계층형 질의문<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;14-1. 계층형 질의문으로 서열을 주고 데이터 출력하기 1<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;14-2. 계층형 질의문으로 서열을 주고 데이터 출력하기 2<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;14-3. 계층형 질의문으로 서열을 주고 데이터 출력하기 3<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;14-4. 계층형 질의문으로 서열을 주고 데이터 출력하기 4<br>

15. 테이블 생성<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;15-1. 일반 테이블 생성하기(CREATE TABLE)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;15-2. 임시 테이블 생성하기(CREATE TEMPORAY TABLE)<br>

16. 뷰<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;16-1. 복잡한 쿼리를 단순하게 하기 1(VIEW)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;16-2. 복잡한 쿼리를 단순하게 하기 2(VIEW)<br>

17. 인덱스<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;17-1. 데이터 검색 속도를 높이기(INDEX)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;17-2. 절대로 중복되지 않는 번호 만들기(SEQUENE)<br>

18. 실수로 지운 데이터 복구하기<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;18-1. 실수로 지운 데이터 복구하기 1(FLASHBACK QUERY)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;18-2. 실수로 지운 데이터 복구하기 2(FLASHBACK TABLE)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;18-3. 실수로 지운 데이터 복구하기 3(FLASHBACK DROP)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;18-4. 실수로 지운 데이터 복구하기 4(FLASHBACK VERSION QUERY)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;18-5. 실수로 지운 데이터 복구하기 5(FLASHBACK TRANSACTION QUERY)<br>

19. 데이터 품질 높이기<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;19-1. 데이터의 품질 높이기 1(PRIMARY KEY)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;19-2. 데이터의 품질 높이기 2(UNIQUE)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;19-3. 데이터의 품질 높이기 3(NOT NULL)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;19-4. 데이터의 품질 높이기 4(CHECK)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;19-5. 데이터의 품질 높이기 5(FOREIGN KEY)<br>

20. with절<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;20-1. WITH절 사용하기 1(WITH ~ AS)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;20-2. WITH절 사용하기 2(SUBQUERY FACTORING)<br>

21. 알고리즘<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;21-1. SQL로 알고리즘 문제 풀기 1(구구단 2단 출력)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;21-2. SQL로 알고리즘 문제 풀기 2(구구단 1단 ~ 9단 출력)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;21-3. SQL로 알고리즘 문제 풀기 3(직각삼각형 출력)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;21-4. SQL로 알고리즘 문제 풀기 4(삼각형 출력)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;21-5. SQL로 알고리즘 문제 풀기 5(마름모 출력)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;21-6. SQL로 알고리즘 문제 풀기 6(사각형 출력)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;21-7. SQL로 알고리즘 문제 풀기 7(1부터 10까지 숫자의 합)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;21-8. SQL로 알고리즘 문제 풀기 8(1부터 10까지 숫자의 곱)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;21-9. SQL로 알고리즘 문제 풀기 9(1부터 10까지 짝수만 출력)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;21-10. SQL로 알고리즘 문제 풀기 10(1부터 10까지 소수만 출력)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;21-11. SQL로 알고리즘 문제 풀기 11(최대 공약수)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;21-12. SQL로 알고리즘 문제 풀기 12(최소 공배수)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;21-13. SQL로 알고리즘 문제 풀기 13(피타고라스의 정리)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;21-14. SQL로 알고리즘 문제 풀기 14(몬테카를로 알고리즘)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;21-15. SQL로 알고리즘 문제 풀기 15(오일러 상수 자연상수 구하기)<br>

<br>
출처: IT WILL 유연수 선생님 강의
