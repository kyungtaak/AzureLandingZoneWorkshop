---
type: workshop
title: Azure Landing Zone Workshop with Azure Virtual WAN
description: Azure Virtual WAN, Application Gateway WAF, Azure Firewall을 사용해 기본 Landing Zone 네트워크를 구성하는 포털 실습
level: intermediate
authors: [HyeonYeong Seo, Anna Jeong]
contacts: ["@HyeonYeong-Rose", "@Anna-Jeong-MS"]
duration_minutes:
tags: [azure-landing-zone, virtual-wan, application-gateway, azure-firewall]
language: ko
execution: [portal]
status: active
source: original
original_content_date: 2025-04-17
last_updated: 2026-10-11
validated_on:
---

# Azure Landing Zone Workshop with Azure Virtual WAN

![Azure Landing Zone 네트워크 구성](assets/azure-landing-zone.png)

## 개요와 학습 목표

Azure Virtual WAN을 사용해 Azure Landing Zone의 기본 네트워크를 구성하는 워크샵입니다. Azure Virtual WAN, Application Gateway WAF, Azure Firewall을 배포한 뒤 허브와 스포크 네트워크의 연결을 확인합니다.

이 워크샵을 마치면 다음 작업을 수행할 수 있습니다.

- Azure Virtual WAN과 가상 허브 구성
- 허브·스포크 가상 네트워크와 보안 리소스 배포
- Application Gateway와 Azure Firewall 규칙 구성
- 테스트 시스템을 사용한 네트워크 연결 확인

## 사전 요구사항

<!-- TODO: Azure 구독, 필요한 권한, 예상 비용과 포털 접근 조건을 저자가 확인해 작성 -->

## 소요 시간

<!-- TODO: 실제 실습 기준으로 전체 소요 시간과 랩별 소요 시간을 확인 -->

## 학습 경로

| 순서 | 랩 | 내용 | 소요 시간 |
|---|---|---|---|
| 1 | [네트워크 리소스 배포](01-network-resource-deployment/README.md) | 리소스 그룹, Azure Virtual WAN, 허브·스포크 네트워크 구성 | TODO |
| 2 | [보안 리소스 배포](02-security-resource-deployment/README.md) | Application Gateway WAF와 Azure Firewall 배포 | TODO |
| 3 | [테스트 시스템 배포](03-test-system-deployment/README.md) | 백엔드 가상 머신과 Nginx 구성 | TODO |
| 4 | [네트워크 연결 확인](04-network-connectivity-check/README.md) | 연결, 방화벽 규칙, 경로 테이블 구성과 테스트 | TODO |

[첫 랩 시작](01-network-resource-deployment/README.md)

## 실행 방법

이 워크샵은 Azure Portal에서 진행합니다. 위 학습 경로를 순서대로 완료합니다.

## 검증

마지막 랩에서 Application Gateway의 공용 IP로 접속해 Nginx 기본 페이지가 표시되는지 확인합니다. `validated_on`은 저자가 전체 실습을 처음부터 끝까지 완료한 뒤 기록합니다.

## 정리 (Clean-up)

<!-- TODO: 생성한 Azure 리소스와 리소스 그룹의 삭제 순서, 비용 발생 중단 확인 방법을 저자가 작성 -->

## 트러블슈팅

<!-- TODO: 실제 E2E 검증에서 확인한 오류와 해결 방법을 저자가 작성 -->

## 라이선스

이 워크샵의 코드와 문서는 [MIT License](LICENSE)를 따릅니다.
