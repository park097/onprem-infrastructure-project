# 온프레미스 사내 인프라 구축 프로젝트

## 📌 프로젝트 개요
VirtualBox 기반 가상 환경에서 내부 사내 네트워크를 설계·구축하고,
Ubuntu Server를 운영하며 방화벽 정책 설정 및 장애 대응 실습을 수행한 프로젝트입니다.

---

## 🧱 기술 스택
- VirtualBox
- Ubuntu Server 24.04 LTS
- Netplan
- UFW
- OpenSSH

---

## 🗺 아키텍처 구성


[내 PC]
192.168.56.1
│
│ Host-Only Network
│
[Ubuntu Server]
192.168.56.10 (Static)


---

## 📅 주차별 구성

- Week 1: 내부 네트워크 구성 및 고정 IP 설정
- Week 2: Nginx 웹 서버 구축
- Week 3: 외부 배포 및 포트포워딩
- Week 4: 장애 대응 및 로그 분석

---

## 🎯 수행 내용 (Week 1)
- Host-Only 네트워크 구성
- DHCP → Static IP 전환
- UFW 방화벽 활성화
- SSH 포트 차단/복구 실습
- 네트워크 트러블슈팅 경험

---

## 🧩 프로젝트 목표
> “VirtualBox 기반 온프레미스 환경에서 내부망 구성, 서버 운영,
방화벽 정책 설정 및 장애 대응까지 수행했습니다.”