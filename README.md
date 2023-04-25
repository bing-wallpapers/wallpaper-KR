# **Wallpaper-KR**

이 저장소는 Bing에서 매일 크롤링한 배경화면을 저장하는 데 사용되며, 한국 버전에 특화되어 있습니다. 배경화면은 ****[Bing](https://www.bing.com/)****의 일일 홈페이지 배경 이미지에서 가져옵니다.

## **디렉토리 구조**

```
.
├── .github
│   └── workflows
│       └── download.yml
├── src
│   └── index.ts
├── static
│   └── <date>-preview.jpg
├── .gitignore
├── README.md
├── package.json
├── tsconfig.json
└── yarn.lock
```

## **파일 설명**

- **`.github/workflows/download.yml`**: Bing에서 배경화면을 다운로드하고 저장소를 업데이트하는 작업을 예약 및 자동화하기 위한 GitHub Actions 워크플로 파일입니다.
- **`src/index.ts`**: 배경화면 크롤러 프로그램의 주요 소스 코드입니다.
- **`static`**: 다운로드한 배경화면 미리보기 이미지를 저장하는 폴더입니다.
- **`.gitignore`**: Git 무시 파일 구성입니다.
- **`README.md`**: 프로젝트 설명 파일입니다.
- **`package.json`**: 프로젝트 의존성 및 관련 구성입니다.
- **`tsconfig.json`**: TypeScript 설정 파일입니다.
- **`yarn.lock`**: 의존성 버전을 안정화하기 위한 Yarn 잠금 파일입니다.

## **사용 방법**

1. 이 저장소를 복제합니다.
    
    ```
    git clone https://github.com/your_username/wallpaper-KR.git
    ```
    
2. 의존성을 설치합니다.
    
    ```
    cd wallpaper-KR
    yarn install
    ```
    
3. 크롤러를 실행합니다.
    
    ```
    yarn start
    ```
    
4. 실행 후, 다운로드한 배경화면은 **`static`** 디렉토리에 저장됩니다.

## **라이선스**

이 프로젝트는 ****[MIT 라이선스](https://opensource.org/licenses/MIT)****에 따라 라이선스가 부여됩니다.
