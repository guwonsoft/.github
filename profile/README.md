<div align="center">

<!-- Hero Banner & Brand Identity -->
<a href="https://guwonsoft.com" target="_blank" rel="noopener noreferrer">
  <img src="https://raw.githubusercontent.com/guwonsoft/.github/main/assets/guwon-logo-horizontal-white.svg" 
       alt="GUWON SOFT Logo" 
       width="480"
       onerror="this.src='https://guwonsoft.com/og-image.png'; this.style.borderRadius='12px';"/>
</a>

<br/><br/>

### **Engineering Ideas into Production-Grade Reality.**
# 생각을 제품으로. 제대로, 끝까지.

<p align="center">
  <b>구원소프트(GUWON SOFT)</b>는 아이디어의 기획 단계부터 고가용성 클라우드 아키텍처, 런타임 결함 없는 프론트엔드까지<br/>
  비즈니스 임팩트를 만들어내는 <b>엔드투엔드(End-to-End) 소프트웨어 엔지니어링 스튜디오</b>입니다.
</p>

<!-- Live Badges & Quick Links -->
<p align="center">
  <a href="https://guwonsoft.com"><img src="https://img.shields.io/badge/OFFICIAL_WEBSITE-guwonsoft.com-0f172a?style=for-the-badge&logo=googlechrome&logoColor=38bdf8" alt="Website"/></a>
  <a href="mailto:skjil1218@kakao.com"><img src="https://img.shields.io/badge/BUSINESS_INQUIRY-skjil1218@kakao.com-fee500?style=for-the-badge&logo=kakaotalk&logoColor=000000" alt="Email"/></a>
  <a href="https://github.com/guwonsoft"><img src="https://img.shields.io/badge/GITHUB_ORG-@guwonsoft-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Code_Coverage-90%25+-brightgreen?style=flat-square&logo=vitest&logoColor=white" alt="Coverage"/>
  <img src="https://img.shields.io/badge/Zero_Type_Errors-TypeScript_5-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Architecture-Clean_%26_Modular-6366F1?style=flat-square" alt="Architecture"/>
  <img src="https://img.shields.io/badge/Status-Accepting_New_Projects-10B981?style=flat-square" alt="Status"/>
</p>

</div>

---

## 🏛️ Engineering Philosophy: How We Build

구원소프트는 타협하지 않는 엔지니어링 표준을 기반으로 코드를 작성합니다.

```
       [ 01. Clarify ]                 [ 02. Architecture ]                [ 03. Loop Verify ]                 [ 04. Continuous Scale ]
  +-----------------------+       +--------------------------+       +---------------------------+       +--------------------------+
  |  요구사항 정의 & PRD  |  ==>  | Domain-Driven Design     |  ==>  | TDD / Strict Type Check   |  ==>  | Zero-Downtime CI/CD      |
  |  가치 중심의 범위 설정|       | Clean Layered Structure  |       | Automated Test Suites     |       | APM & Error Tracking     |
  +-----------------------+       +--------------------------+       +---------------------------+       +--------------------------+
```

### 1. **Zero-Defect Loop Engineering (루프 엔지니어링)**
* `Code` ➡️ `Static Analysis (ESLint)` ➡️ `Type Check (tsc --noEmit)` ➡️ `Unit/Integration Tests (Vitest)`
* 자동화된 검증 파이프라인을 통과하지 못한 코드는 메인 브랜치에 머지되지 않습니다.
* 모든 비즈니스 로직은 테스트 커버리지로 검증되어 리팩토링 및 빠른 기능 추가에도 프로덕션 안정성을 보장합니다.

### 2. **Context-Driven Architecture**
* 단순 오버엔지니어링을 지양하고, 비즈니스의 현재 규모와 확장성에 가장 부합하는 구조(Modular Monolith, Serverless, Event-Driven)를 설계합니다.
* 데이터 스키마와 API 계약(Contract)을 Zod/OpenAPI로 선행 확정하여 프론트엔드와 백엔드의 병렬 생산성을 극대화합니다.

---

## ⚡ Technical Capabilities & Stack

<table width="100%">
  <thead>
    <tr>
      <th width="25%" align="left">Layer</th>
      <th width="75%" align="left">Tech Ecosystem & Standards</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Frontend & App</b></td>
      <td>
        <img src="https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
        <img src="https://img.shields.io/badge/TypeScript_5-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
        <img src="https://img.shields.io/badge/Tailwind_CSS_v4-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white"/>
        <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=react-query&logoColor=white"/>
        <img src="https://img.shields.io/badge/Zustand-443E38?style=flat-square&logo=react&logoColor=white"/>
        <br/>
        <sub>• Server Components (RSC) 기반의 초기 렌더링 최적화, 코어 웹 바이탈(LCP, INP, CLS) 지표 극대화</sub>
      </td>
    </tr>
    <tr>
      <td><b>Backend & Cloud</b></td>
      <td>
        <img src="https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
        <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
        <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
        <br/>
        <sub>• 트랜잭션 정합성 보장, 쿼리 인덱싱 튜닝 및 Redis 기반의 분산 락/인메모리 캐싱 아키텍처</sub>
      </td>
    </tr>
    <tr>
      <td><b>DevOps & Infra</b></td>
      <td>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
        <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>
        <img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white"/>
        <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
        <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white"/>
        <br/>
        <sub>• 무중단 배포(Blue/Green, Rolling), 인프라 자동화 및 실시간 로그 모니터링 환경 구축</sub>
      </td>
    </tr>
    <tr>
      <td><b>Quality & Testing</b></td>
      <td>
        <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white"/>
        <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white"/>
        <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white"/>
        <img src="https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white"/>
        <br/>
        <sub>• 컴포넌트 단위 테스트, E2E 시나리오 테스트 및 입출력 런타임 타입 검증</sub>
      </td>
    </tr>
  </tbody>
</table>

---

## 🔬 Core Product Principles

```
  01. Measurable Velocity          02. Robust Core                  03. Clear Communication
  빠른 프로토타이핑을 넘어,            런타임 크래시 제로를 목표로          엔지니어링 진행 상황과 지표를
  실제 작동하는 완성도 높은            엄격한 타입 안전성과 테스트         실시간으로 공유하고 투명하게
  MVP를 단기간 내 배포합니다.         기반 코어 로직을 작성합니다.         프로덕트를 함께 다듬어갑니다.
```

* **첫 미팅부터 아키텍처 정의까지:** 아이디어가 모호한 상태라도 괜찮습니다. 기획 의도를 기술적 스펙(PRD/Schema)으로 명확히 구체화합니다.
* **유지보수 가능한 코드베이스:** 프로젝트가 완료된 이후에도 고객사 내부 개발팀이 즉시 인계받아 확장할 수 있는 표준화된 문서 및 클린 코드를 제공합니다.

---

## 📈 Organization Activity & Overview

<div align="center">

<table width="100%">
  <tr>
    <td align="center" width="50%">
      <img src="https://github-readme-stats.vercel.app/api?username=guwonsoft&show_icons=true&theme=tokyonight&hide_border=true&title_color=38bdf8&icon_color=38bdf8" alt="GitHub Stats" width="95%"/>
    </td>
    <td align="center" width="50%">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=guwonsoft&layout=compact&theme=tokyonight&hide_border=true&title_color=38bdf8" alt="Top Languages" width="95%"/>
    </td>
  </tr>
</table>

</div>

---

## 🤝 Start a Project with Us

구원소프트는 단순 외주 개발사가 아닌, 성공적인 비즈니스 프로덕트를 함께 런칭하는 **기술 파트너**입니다.  
신규 서비스 런칭, 기존 레거시 시스템 고도화, 고성능 웹 솔루션 구축이 필요하시다면 언제든 문의해 주세요.

<br/>

<div align="center">

[![Website](https://img.shields.io/badge/Visit-guwonsoft.com-0f172a?style=for-the-badge&logo=googlechrome&logoColor=38bdf8)](https://guwonsoft.com)
&nbsp;&nbsp;
[![Send Email](https://img.shields.io/badge/Email-skjil1218@kakao.com-fee500?style=for-the-badge&logo=kakaotalk&logoColor=000000)](mailto:skjil1218@kakao.com)

<br/><br/>

<sub><b>GUWON SOFT CO., LTD.</b> | 생각을 제품으로. 제대로, 끝까지.</sub><br/>
<sub>© 2026 GUWON SOFT. All rights reserved.</sub>

</div>
