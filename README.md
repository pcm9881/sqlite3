# Sqlite3 사용법 정리

## 접근
``` sh
$ sqlite3 데이터베이스이름.db 
```

## 나가기
``` sql
> .q
> .exit
> .quit
```

## 헤더 설정과 컬럼에 맞게 표기
``` sql
> .headers on
> .mode column
```

## pragma 설정 
``` sql
> pragma table_info("table_name")
> select * from pragma_table_info("table_name");
```
