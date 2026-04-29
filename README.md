# 🎥 Magic Factory — AI 올인원 크리에이티브 스튜디오

> **Magic Factory**는 AI 영상 생성, 뮤직비디오 자동 제작, 밈 자동 생성, 페이스스왑, AI 커버곡을 **하나의 데스크톱 프로그램**으로 제공하는 올인원 크리에이티브 스튜디오입니다.

🌐 **공식 사이트**: [magicfactory.kr](https://magicfactory.kr)

---

## 🎯 왜 Magic Factory인가?

| 특징 | Magic Factory | 클라우드 도구 (RunwayML, Pika 등) |
|------|--------------|------|
| **비용** | 1회 결제 (영구 라이선스) | 월 $15~$76 구독 |
| **생성 제한** | ♾️ 무제한 | 월 크레딧 제한 |
| **AI 모델** | LTX-2.3 + Wan 2.2 | 자체 모델 |
| **통합 도구** | 9가지 | 1~2가지 |
| **개인정보** | 100% 로컬 실행 | 클라우드 전송 |
| **LoRA 얼굴 학습** | ✅ | ❌ |

---

## 🛠️ 9가지 AI 도구

### 🎬 AI 동영상 생성
- **LTX-2.3** (Lightricks) — 최신 영상 생성 모델
- **Wan 2.2** (Alibaba) — 고품질 영상 모델
- 텍스트 → 영상, 이미지 → 영상 지원
- 멀티씬 분할 생성으로 일관된 스토리 영상

### 🎤 AI 뮤직비디오 자동 제작
- 음원(MP3/WAV) 업로드 → AI가 자동 씬 분할
- 각 씬별 프롬프트 자동/수동 설정
- LoRA 얼굴 적용으로 일관된 캐릭터 유지
- 개별 씬 재생성 (자동 랜덤 시드)

### 📹 밈 자동 생성 (숏폼 콘텐츠)
- 트렌드 밈 자동 검색
- AI 스크립트 자동 생성
- 멀티씬 영상 + BGM 자동 편집
- 유튜브 쇼츠/틱톡 최적 포맷

### 🎭 페이스스왑
- 실시간 얼굴 교체
- 영상/이미지 모두 지원

### 🎵 AI 커버곡
- **ACE-Step** — AI 음악 생성 엔진
- **RVC** — 음성 변환 (보이스 클로닝)
- 보컬 분리 → 음성 변환 → 자동 믹싱

### 🤖 LoRA 얼굴 학습
- 사진 5~10장으로 내 얼굴 학습
- 2000스텝 기본 / 최대 6000스텝
- **이어서 학습** 기능 (기존 모델에 추가 학습)
- 로컬 학습 (무료) + 클라우드 학습 (유료, 30~50분)

### 🎨 AI 이미지 생성
- **Flux** — 최신 이미지 생성 모델
- **SDXL** — Stable Diffusion XL

### 🔍 4K AI 업스케일
- 저해상도 영상/이미지를 4K로 확대

### 💧 워터마크 제거
- AI 기반 워터마크 자동 감지 및 제거

---

## 💻 시스템 요구사항

| 항목 | 최소 | 권장 |
|------|------|------|
| **GPU** | NVIDIA RTX 3060 (12GB VRAM) | RTX 4060 Ti+ (16GB VRAM) |
| **RAM** | 16GB | 32GB |
| **저장공간** | 50GB SSD | 100GB NVMe SSD |
| **OS** | Windows 10 | Windows 11 |
| **페이지파일** | 32GB | 64GB+ |

---

## 📚 문서

- [📖 시작하기 가이드](docs/getting-started.md)
- [🎤 뮤직비디오 제작 가이드](docs/music-video-guide.md)
- [🤖 LoRA 얼굴 학습 가이드](docs/lora-training-guide.md)
- [📹 밈 자동 생성 가이드](docs/meme-creation-guide.md)
- [🎵 AI 커버곡 가이드](docs/ai-cover-guide.md)
- [❓ FAQ](docs/faq.md)
- [🔧 트러블슈팅](docs/troubleshooting.md)

---

## 🔗 링크

- 🌐 **공식 사이트**: [magicfactory.kr](https://magicfactory.kr)
- 📰 **블로그**: [magicfactory.kr/blog](https://magicfactory.kr/blog/)
- 📧 **문의**: [magicfactory.kr](https://magicfactory.kr/#contact)

---

## 📋 최신 업데이트

### v2.5 (2026.04.29)
- ✨ LoRA 이어서 학습 기능 추가
- ✨ 학습 스텝 최대 6000까지 확장
- 🔧 재생성 시 자동 랜덤 시드 적용
- 🔧 GPU 순차 실행 큐잉 (VRAM 충돌 방지)

### v2.4 (2026.04.25)
- ✨ 클라우드 LoRA 학습 (RunPod A100)
- ✨ GPU Guard 워치독 (학습 중 브라우저 자동 차단)
- 🔧 ACE-Step + RVC 음질 최적화

### v2.3 (2026.04.20)
- ✨ 멀티씬 뮤직비디오 엔진 완전 리뉴얼
- ✨ Wan 2.2 엔진 추가
- ✨ 카메라 LoRA 지원

---

© 2026 Magic Factory. All rights reserved.
