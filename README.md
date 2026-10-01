# AI Serving · Backend · Infrastructure

AI 모델을 **실제 서비스 환경에서 안정적으로 배포하고 운영하는 시스템**을 개발합니다.
**데이터 → 추론 → API → 배포 → 모니터링**으로 이어지는 흐름에서 성능과 운영 안정성을 함께 고민합니다.

## Selected Projects

### [CCTV Safety Vision](https://github.com/9imyong/cctv-safety-vision)

건설 현장 CCTV에서 안전보호구 미착용과 위험 상황을 검출하는 AI 영상분석 시스템.
TensorRT 기반 다채널 추론, GStreamer 기반 HLS 재송출, 이벤트 영상 녹화와 외부 관제 연동을 다룹니다.

### [Model Serving Platform](https://github.com/9imyong/model-serving)

OCR 모델 서빙을 위한 FastAPI 기반 플랫폼 스켈레톤.
API·Worker·도메인 로직을 분리하고, 비동기 처리와 Kubernetes 배포 및 모니터링을 고려한 구조를 설계합니다.

### [CCTV AI Streaming Platform](https://github.com/9imyong/streaming-pipeline)

장시간 실행되는 CCTV 스트리밍을 API 요청과 분리한 이벤트 기반 플랫폼.
Kafka 기반 명령 처리, Lease 기반 중복 실행 방지, 워커 장애 시 인계 구조를 다룹니다.

## What I Do

### AI Serving & Pipeline

- Python / FastAPI 기반 추론 API 및 비동기 Worker 구성
- STT · Wake Word · Vision 파이프라인과 데이터셋·학습 흐름 구축
- GPU 병목 분석, ONNX / TensorRT 최적화 및 추론 지연시간 개선

### Infrastructure & Deployment

- Docker 기반 컨테이너화 및 Kubernetes 배포 환경 구성
- NGINX 기반 서비스 라우팅
- CI/CD와 배포·복구 자동화

### Observability & Reliability

- Prometheus / Grafana 기반 지표 수집과 모니터링
- 헬스 체크 및 구조화된 로깅
- 장애 원인 분석과 복구 절차 설계

## Tech Stack

| 분야 | 기술 |
| --- | --- |
| Backend / Serving | Python · FastAPI · Django · Redis · Kafka · Celery |
| AI / Inference | PyTorch · ONNX · TensorRT · OpenVINO · CUDA |
| Infrastructure | Docker · Docker Compose · Kubernetes · NGINX · Linux |
| Observability | Prometheus · Grafana |

> **Building AI systems that work beyond the model.**
