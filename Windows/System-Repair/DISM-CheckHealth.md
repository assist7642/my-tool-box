# DISM CheckHealth

## 개요
이 명령어는 현재 실행 중인 Windows 이미지에 손상 기록이 있는지 확인할 때 사용하는 점검 명령어입니다.

Windows 구성 요소 저장소(Component Store)의 기록 상태를 확인하는 데 사용됩니다.

## 문법
```cmd
DISM /Online /Cleanup-Image /CheckHealth
```

## 옵션
- `DISM`  
  Deployment Image Servicing and Management의 약자로, Windows 이미지의 점검 및 복구에 사용하는 명령줄 도구입니다.

- `/Online`  
  현재 실행 중인 Windows 운영체제를 대상으로 작업합니다.

- `/Cleanup-Image`  
  Windows 이미지의 상태 점검 및 복구 관련 작업에 사용됩니다.

- `/CheckHealth`  
  Windows 이미지에 손상 기록이 있는지 확인합니다.

## 방법

### 1. 관리자 권한으로 실행
시작 메뉴에서 `명령 프롬프트` 또는 `PowerShell`을 검색한 뒤 관리자 권한으로 실행합니다.

### 2. 명령어 입력
아래 명령어를 입력하고 실행합니다.

```cmd
DISM /Online /Cleanup-Image /CheckHealth
```

## 결과
실행 후 현재 Windows 이미지에 손상 기록이 있는지 여부를 확인할 수 있습니다.

## 참고
- 관리자 권한으로 실행하는 것이 좋습니다.
- 점검 또는 복구 작업 전에는 중요한 데이터 백업을 권장합니다.
- `CheckHealth`는 비교적 짧게 끝나는 편이지만, 시스템 상태에 따라 소요 시간이 달라질 수 있습니다.
