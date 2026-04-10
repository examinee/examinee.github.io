---
title: "블로그를 시작하며"
date: 2026-04-10
draft: false
tags: ["일상"]
categories: ["일상"]
---

## 이 블로그의 목적

리버스 엔지니어링과 악성코드 분석을 공부하면서 배운 것들을 기록합니다.

분석만 하는 것이 아니라, 분석에서 발견한 기법을 직접 구현하고, 구현한 것을 다시 분석하는 과정을 통해 깊이 있는 이해를 추구합니다.

## 앞으로 다룰 주제

- **Red Team Engineering** — Windows internals 기반 기법 구현 (Process Hollowing, API Hashing, Shellcode Loader 등)
- **Malware Analysis** — 실제 악성코드 분석 과정과 사고 흐름
- **Notes** — 짧은 메모, 삽질 기록, 도구 팁

## 첫 번째 시리즈

첫 시리즈는 **Process Hollowing in C** 입니다. FormBook 악성코드 분석 중 발견한 인젝션 기법을 직접 C로 구현하면서, 각 단계의 Windows API가 왜 필요한지, 어디서 막히는지, 어떻게 변형할 수 있는지를 기록할 예정입니다.
