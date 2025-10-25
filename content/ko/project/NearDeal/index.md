---
title: NearDeal - 학생 맞춤형 제휴 할인 큐레이션 플랫폼
summary: 실시간으로 특정 할인 스위치를 켜서 유동 인구를 즉각적으로 늘리고, 학생들은 자신의 위치와 소속 단과대학 기준으로 맞춤 할인을 제공받는 O2O 서비스
tags:
  - React
  - Next.js
  - TypeScript
  - React Query
  - Tailwind CSS
date: 2025-09-07
external_link: https://near-deal.vercel.app/

image:
  caption: "NearDeal"
  focal_point: "Smart"
---

## 💡 프로젝트 개요

지역 하이퍼 로컬 O2O 플랫폼 **NearDeal**은 우리 동네 가게를 위한 실시간 매출 부스팅 서비스입니다.

소상공인들이 유휴 시간대(비수기)를 활용할 수 있도록 가게별 쿠폰/이벤트를 실시간으로 발행하고, 사용자는 가까운 제휴 매장 정보를 쉽게 확인할 수 있습니다.

## 🏬 주요 기능

### 👨‍👩‍👧 사용자(고객)

- 실시간 제휴 매장 및 쿠폰 정보 조회
- 사용자 위치 기반 근처 매장 검색
- 쿠폰 다운로드 및 사용 내역 관리
- 단과대학별 제휴업체 자동 분류

### 🧾 점주(가게)

- 가게 등록 및 프로필 관리
- 실시간 쿠폰 발급/만료 관리
- 매출 통계 시각화 (일/주/월 단위)
- 푸시 알림을 통한 이벤트 홍보

### 🏫 학교 및 단대 제휴

- 단대별 제휴업체 정보 페이지 제공
- 교내 단체 및 동아리와의 협업 기능

## 🖥️ 기술 스택

| 구분                | 기술                                                  |
| ------------------- | ----------------------------------------------------- |
| **Frontend**        | React, TypeScript, Tailwind CSS, Zustand, React Query |
| **Backend**         | Spring Boot (Java 21), JPA                            |
| **Database**        | MySQL                                                 |
| **Deployment**      | Vercel (Frontend), AWS EC2 (Backend)                  |
| **Version Control** | GitHub Actions, Docker                                |

## 🚀 프로젝트 특징

- React 기반의 SPA 구조로 빠른 사용자 경험 제공
- Spring Boot REST API 기반으로 클린한 백엔드 구조
- MySQL + JPA로 효율적인 데이터 관리
- Vercel 배포 자동화로 프론트엔드 변경 즉시 반영

## 📍 향후 계획

- AI 기반 쿠폰 추천 알고리즘 도입
- 소상공인 마케팅 자동화 도구 개발
- 전북대학교 단대별 제휴 확대 및 운영 자동화

## 🔗 링크

- [GitHub Repository](https://github.com/oneieo/NearDeal)
- [Live Demo](https://near-deal.vercel.app/)
