# CS 학습 로드맵 진행 현황

## 📅 현재 단계

- [ ] 1단계: 웹 & 네트워크 기초 (완료)
- [ ] 2단계: 성능 최적화 (진행 중)
- [ ] 3단계: 자료구조 & 알고리즘
- [ ] 4단계: 운영체제 & 메모리
- [ ] 5단계: 데이터베이스 & 백엔드
- [ ] 6단계: 보안
- [ ] 7단계: 소프트웨어 공학 & 협업
- [ ] 8단계: Docker
- [ ] 9단계: Kubernetes

---

# 🗓️ 전체 플랜 요약 (약 6~9개월)

- **1~2개월차**: 웹/네트워크 + 성능 최적화
    
- **3~4개월차**: 자료구조/알고리즘 + 운영체제
    
- **5개월차**: DB + 보안
    
- **6개월차**: 소프트웨어 공학 + Docker
    
- **7~8개월차**: Kubernetes 기초~심화
    
- **9개월차 이후**: CI/CD 통합 → 실무 프로젝트에 적용

---

# 📚 CS 학습 로드맵 (FE 개발자 + Docker/K8s 확장 버전)

## 1단계. 웹 & 네트워크 기초 (1개월)

- **브라우저 동작 원리**
    
    - 렌더링 과정 (DOM, CSSOM, Render Tree → Layout → Paint → Composite)
        
    - Reflow vs Repaint, 이벤트 루프와 마이크로태스크
        
- **네트워크 기본**
    
    - HTTP/HTTPS 구조, 요청/응답 헤더, 상태 코드
        
    - 쿠키·세션·JWT·OAuth2 인증
        
    - CORS / Same-Origin Policy
        
    - DNS, CDN, Proxy 개념
        
- **실습**: DevTools Network 탭 분석, API 캐싱 전략 적용
    

---

## 2단계. 성능 최적화 & 실무 적용 (1개월)

- **Critical Rendering Path 최적화**
    
- **리소스 최적화**: Code Splitting, Lazy Loading, Tree Shaking
    
- **이미지 최적화**: WebP, AVIF, responsive image
    
- **CSR vs SSR vs SSG vs ISR** 이해 (Next.js 활용)
    
- **실습**: Lighthouse로 프로젝트 성능 측정 → 개선 적용
    

---

## 3단계. 자료구조 & 알고리즘 (1~2개월)

- **복잡도 분석**: Big-O 표기법
    
- **자료구조**: 배열, 스택, 큐, 해시맵, 트리, 그래프
    
- **알고리즘**: 정렬, 탐색, BFS/DFS, 투 포인터, 슬라이딩 윈도우
    
- **실무 응용**:
    
    - 해시맵 → 상태 관리 최적화
        
    - 트리/그래프 → DOM 탐색, 메뉴 구조, 라우팅
        
- **실습**: 프로그래머스/LeetCode Easy~Medium 꾸준히 풀이
    

---

## 4단계. 운영체제 & 메모리 (1개월)

- **프로세스 vs 스레드, 멀티스레딩**
    
- **동기 vs 비동기 I/O** (Node.js와 연계)
    
- **메모리 구조**: 스택/힙, 클로저 메모리 관리
    
- **Garbage Collection 방식 (Mark & Sweep 등)**
    
- **실습**: Node.js로 CPU bound vs IO bound 작업 성능 비교
    

---

## 5단계. 데이터베이스 & 백엔드 이해 (1개월)

- **RDB 기초**: 인덱스, 트랜잭션, ACID
    
- **NoSQL**: Document 기반, CAP 이론
    
- **API 패러다임**: REST vs GraphQL vs gRPC
    
- **실무 응용**: 페이지네이션, N+1 문제
    
- **실습**: SQLite + Node.js로 간단한 API 서버 구현
	-

---

## 6단계. 보안 (2주)

- **OWASP Top 10 (FE 관련)**: XSS, CSRF, Clickjacking
    
- **HTTPS & TLS Handshake**
    
- **인증/인가 흐름** (OAuth2, OpenID Connect)
    
- **실습**: XSS 시뮬레이션 후 방어 코드 적용
    

---

## 7단계. 소프트웨어 공학 & 협업 (2주)

- **디자인 패턴**: 싱글톤, 옵저버, 팩토리, MVC/MVVM
    
- **테스트 전략**: 단위 테스트(Jest/Vitest), E2E(Playwright)
    
- **CI/CD 개념**: GitHub Actions, Git Flow vs Trunk-Based
    
- **실습**: FE 프로젝트에 최소 1개 단위 테스트 + Actions 파이프라인 적용
    

---

## 8단계. Docker (1개월)

- **Docker 기초**
    
    - 이미지 vs 컨테이너 vs 레이어
        
    - Dockerfile 작성, `docker build/run`
        
    - `docker-compose`로 FE+BE+DB 환경 구성
        
- **Docker 심화**
    
    - 멀티스테이지 빌드 (build → runner 분리)
        
    - volume, network, env 관리
        
- **실습**: React/Vite/Next.js 프로젝트를 Docker로 빌드 → Nginx 배포
    

---

## 9단계. Kubernetes (1~2개월)

- **K8s 기초**
    
    - Pod, Deployment, Service, Ingress 개념
        
    - ConfigMap, Secret, Volume 사용법
        
    - `kubectl` 기본 명령어
        
- **K8s 심화**
    
    - HPA (Horizontal Pod Autoscaler)
        
    - Rolling Update / Canary Deployment
        
    - Helm chart 구조
        
- **실습**
    
    - Minikube에 FE 컨테이너 배포 후 스케일링
        
    - GitHub Actions → Docker build → K8s 배포 파이프라인 구성