# 🛠 Universal Automation Tool-Box

반복적인 작업 자동화와 시스템 관리에 활용할 수 있도록 스크립트와 명령어를 정리한 저장소입니다.

## 🚀 주요 기능 (Features)

### 🖥 Windows Scripts
| 분류 | 도구명 | 설명 | 주요 기술 |
| :--- | :--- | :--- | :--- |
| **System** | [Time Fixer](./Windows/System-Time-Control) | 테스트/캡처용 시스템 시간 고정 | Batch, VBS |

### 🖥 Windows Commands
| 분류 | 도구명 | 설명 | 주요 기술 |
| :--- | :--- | :--- | :--- |
| **System Repair** | [CheckHealth](./Windows/System-Repair/dism-checkhealth.md) | Windows 이미지 손상 기록 확인 | CLI |
| **System Repair** | [ScanHealth](./Windows/System-Repair/dism-scanhealth.md) | Windows 이미지 손상 여부 검사 | CLI |
| **System Repair** | [RestoreHealth](./Windows/System-Repair/dism-restorehealth.md) | Windows 이미지 손상 복구 | CLI |
| **System Repair** | [SFC Scannow](./Windows/System-Repair/sfc-scannow.md) | Windows 시스템 파일 검사 및 복구 | CLI |

### 🐧 Linux Scripts
- (준비 중입니다. 곧 업데이트될 예정입니다!)

---

## 📖 상세 설명

### Time Fixer
- **문제 인식**: UI 테스트나 튜토리얼 캡처 시 시계가 계속 변하는 불편함 해결
- **최적화**: `timeout`을 사용해 CPU 부하를 방지한 Stable 버전 제공
- **편의성**: VBScript를 통해 백그라운드 실행 지원

### CheckHealth
- **문제 인식**: Windows 이미지에 손상 기록이 있는지 먼저 확인할 필요가 있는 상황에 사용
- **핵심 역할**: 현재 시스템 이미지의 기록 상태를 빠르게 확인
- **활용성**: 복구 작업 전 기본 상태 점검용 명령어로 활용 가능

### ScanHealth
- **문제 인식**: Windows 이미지의 손상 여부를 보다 자세히 확인할 필요가 있는 상황에 사용
- **핵심 역할**: 구성 요소 저장소의 손상 여부를 검사
- **활용성**: 이미지 상태를 점검하는 단계에서 활용 가능

### RestoreHealth
- **문제 인식**: Windows 이미지 손상이 의심되거나 복구가 필요한 상황에 사용
- **핵심 역할**: 구성 요소 저장소의 손상을 검사하고 복구
- **활용성**: 시스템 복구 단계에서 활용 가능

### SFC Scannow
- **문제 인식**: Windows 시스템 파일 손상이 의심되거나 무결성 확인이 필요한 상황에 사용
- **핵심 역할**: 보호된 시스템 파일의 손상 여부를 검사하고 복구
- **활용성**: 시스템 파일 복구 단계에서 활용 가능
