# 1. 준비
- node js 설치

    https://nodejs.org/en/

- git에서 파일 다운로드
  
  우측 상단은 초록색 버튼(Code) 클릭 후 DownloadZip 선택

- 하드 드라이브에 압축해제

- 압축 해제 폴더의 cmd에서 아래 커맨드 실행
```
npm i 
```

# 2. BABEL 사용법
```
npx babel ./input --out-dir ./ouput
```
./input 에 있는 파일을 ie에서 사용할수 있도록 변환하여 ./ouput에 저장함


# 3. uglify 사용법
```
npm install uglify-js -g
```
설치 후 
```
uglifyjs ${파일}.js -o ${파일}.min.js -m
```