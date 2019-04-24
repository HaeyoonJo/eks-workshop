---
title: "CodePipeline를 통한 CI/CD"
chapter: true
weight: 42
draft: false
---

# CodePipeline를 통한 CI/CD

[지속적인 통합](https://aws.amazon.com/devops/continuous-integration/) (CI) 그리고 [지속적인 전달](https://aws.amazon.com/devops/continuous-delivery/) (CD)
은 신속하고 재빠른 조직들에게 필수적입니다. 개별적으로 변경을 자주 수행하게되고 프로그래밍방식의 변경과 업데이트 전달 및 무중단 배포를 할 수 있을 때, 팀의 생산성은 향상됩니다.

이번 과정에서는, [AWS CodePipeline](https://aws.amazon.com/codepipeline/)을 이용하여 CI/CD 파이프라인을 구축하게 됩니다. 이 CI/CD 파이프라인은 쿠버네티스 샘플서비스를 배포하고, 우리는 Github 저장소를 변경하고 이 변경이 클러스터에 자동으로 전달되었는지 살펴볼 예정입니다.
