## 소개
이 저장소는 Kubernetes 환경에서 Argo CD를 사용한 GitOps 방식 배포를 위해

애플리케이션 매니페스트를 관리하는 레포지토리입니다.

애플리케이션 코드와 배포 정의를 분리하여 선언적 배포, 변경 이력 관리, 자동 동기화를 목적으로 합니다.

## 목적
Kubernetes 애플리케이션 배포 정의 관리

Argo CD 기반 GitOps 배포

애플리케이션 코드와 배포 설정 분리

## 사용 기술
Kubernetes

Argo CD

YAML

Docker Image Registry

## 배포 흐름
애플리케이션 이미지 빌드 및 Registry Push

이미지 태그 변경 또는 매니페스트 수정

Git 저장소에 커밋

Argo CD가 변경 감지

Kubernetes 클러스터에 자동 동기화

## 작성자
GitHub: OhseungKeun
