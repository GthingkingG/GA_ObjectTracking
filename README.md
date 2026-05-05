# GA Object Tracking

Apple Vision Pro의 Object Tracking + CreateML 학습 프로젝트 — Apple Developer Academy C4 작업.

## 학습 목적
- **Vision Pro Object Tracking**: 실제 물체를 visionOS에서 인식·추적
- **CreateML**: 머신러닝 모델 학습 (`.mlproj` 프로젝트)
- Immersive Space + RealityKit 콘텐츠 결합
- Object Anchor를 통한 가상 오브젝트 부착

## 주요 컴포넌트
| 파일/폴더 | 역할 |
|----------|------|
| `GA_Object Tracking.mlproj/` | CreateML 모델 학습 프로젝트 (Data Sources + Model Containers) |
| `GA_ObjectTrackingApp.swift` | @main, AppModel 주입 |
| `AppModel.swift` | Immersive Space 상태 |
| `ContentView.swift` | 메인 윈도우 |
| `ImmersiveView.swift` | Object Tracking 시각화 |
| `Packages/RealityKitContent/` | RealityKit 콘텐츠 패키지 |

## 빌드 & 실행
```bash
git clone https://github.com/GthingkingG/GA_ObjectTracking.git
open GA_ObjectTracking/GA_ObjectTracking.xcodeproj
```
Xcode에서 visionOS 시뮬레이터 / Vision Pro 기기 선택 후 ⌘R.

## 인덱스
[Learning-Archive](https://github.com/GthingkingG/Learning-Archive) 대시보드의 `[Academy]` 카테고리 (C4 visionOS + ML 학습).
