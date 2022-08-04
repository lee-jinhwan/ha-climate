# Home Assistant Climate extension Custom Components

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-41BDF5.svg)](https://github.com/lee-jinhwan/ha-climate)
![Version](https://img.shields.io/github/v/release/lee-jinhwan/ha-climate)

 Home Assistant core에서 Climate에 `AI 쾌적` 모드를 추가한 컴포넌트 입니다.

## 최소 지원 버전
Home Assistant `2022.7.0` 이상

## 설치
### HACS
1. HACS - Integrations - 우측상단 메뉴 - `Custom repositories` 선택
2. `Add custom repository URL`에 `https://github.com/lee-jinhwan/ha-climate` 입력, `Category`는 `Integration` 선택
3. HACS - Integrations 에서 `Climate extension` 찾아 설치
4. HomeAssistant 재시작

### 수동설치
1. Git에서 코드 다운로드
2. `custom_components` 에 복사
```
    └── ...
    └── configuration.yaml
    └── custom_components
        └── ...
        └── climate
            └── translations
            └── __init__.py
            └── ...            
```
3. Home Assistant 재시작

## 지원 기능
 - `AI 쾌적` 모드 지원 (SmartThings 에어컨에서만 지원)
