### SW환경에 따른 설치파일  

#### 윈도우 및 macOS 설치파일 생성
<!-- 맥os는 64비트만 지원하기 때문에 프롬프트는 1개임 -->
```
#### 32비트 Windows 설치 파일 생성
npx electron-forge package --platform=win32 --arch=ia32
#### 64비트 Windows 설치 파일 생성
npx electron-forge package --platform=win32 --arch=x64
#### 64비트 macOS 설치 파일 생성
npx electron-forge package --platform=darwin --arch=x64
```

```bash
# 32비트 Windows 설치 파일 생성
npm run package:win32:ia32

# 64비트 Windows 설치 파일 생성
npm run package:win32:x64

# macOS 설치 파일 생성
npm run package:darwin:x64
```