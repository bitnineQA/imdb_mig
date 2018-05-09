"# imdb_mig" 
1. agens 설치
2. imdb 생성
$ createdb imdb

-- 작업 directory 생성
mkdir $HOME/export
tmp 폴더 아래 압축 파일 풀기

3. table 생성
$ agens -d imdb -f imdb.sql
4. data load
$ agens -d imdb -f imdb2.sql
5. graph 생성, graph 데이터 load
$ ./export/imdb/imdb_agens.sh
