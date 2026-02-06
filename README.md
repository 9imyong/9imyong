# 👋 안녕하세요, 9IMYONG입니다

**AI Model Serving · Infra · SRE**

> GPU 기반 AI 모델 서빙 시스템을  
> **운영 관점에서 안정적으로 설계·구현하는 엔지니어**입니다.

---

## 🧭 제가 집중하는 영역
- **AI Model Serving**
  - 비동기 아키텍처 기반 모델 서빙
  - GPU 병목 분리 및 직렬화/배치 전략 설계
- **Infra / DevOps**
  - Docker · Kubernetes 기반 배포 환경 구성
  - CI/CD 및 서비스 안정성 확보
- **SRE 관점 운영**
  - 장애 예측 → 대응 → 복구 → 재발 방지까지 구조로 해결

---

## 🛠 기술 스택

### Backend / Serving
- Python, FastAPI
- Kafka, Redis
- Celery 기반 Worker 아키텍처

### AI / GPU
- TensorRT, CUDA
- YOLO / OCR 파이프라인
- GPU 동시성 제어 및 자원 관리

### Infra / Platform
- Docker, Docker Compose
- Kubernetes (Minikube / Kind / K3s)
- NGINX, systemd

### Observability
- Prometheus, Grafana
- 구조화 로그
- Health Probe / Metrics / Tracing

---

## 📌 주요 프로젝트

### 🔹 model-serving-platform
> 실서비스 기준으로 설계한 AI 모델 서빙 포트폴리오

- API ↔ Worker 분리 (EDA 구조)
- Kafka 기반 Job 처리
- GPU 직렬화 및 배치 전략 적용
- 장애 복구 시나리오 및 Runbook 포함

**기술**: FastAPI · Kafka · Celery · MySQL · Prometheus

---

### 🔹 ocr-serving
> OCR 비동기 처리 파이프라인

- 요청/응답 토픽 분리
- 멱등성 보장 Job 설계
- Worker 재시작에도 안전한 처리 구조

**기술**: Kafka · Python · OCR Engine

---

### 🔹 streaming-pipeline
> CCTV 영상 스트리밍 파이프라인

- RTSP → HLS / MJPEG 변환
- GStreamer 기반 고성능 스트리밍
- 해상도 및 프레임 제어

---

### 🔹 k8s-deploy
> 로컬부터 실서버까지 이어지는 Kubernetes 배포 환경

- Minikube / Kind 기반 로컬 테스트
- 서비스 분리 배포 전략
- 리소스 제한 및 안정성 고려

---

## 🧪 엔지니어링 철학
- **“비동기는 성능을 위한 선택이 아니라, 장애를 분리**
