https://programmers.co.kr/learn/courses/30/parts/17043

```SQL
SELECT MAX(DATETIME) FROM ANIMAL_INS

SELECT MIN(DATETIME) FROM ANIMAL_INS

SELECT COUNT(ANIMAL_ID) FROM ANIMAL_INS
SELECT SUM(*) FROM ANIMAL_INS

# 중복과 NULL값 모두 제외한 COUNT 추출
SELECT COUNT(DISTINCT NAME) FROM ANIMAL_INS WHERE NAME IS NOT NULL
```
