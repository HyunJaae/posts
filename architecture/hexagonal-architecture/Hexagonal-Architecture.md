# Hexagonal Architecture, Ports and Adapters

헥사고날 아키텍처에서 애플리케이션은 비즈니스 관심사를 다루는 내부(inside)와 기술적인 관심사를 다루는 외부(outside)로 분해됩니다. 여기서 외부에 포함된 기술적인 컴포넌트를 어댑터(adapter)라 부르고, 어댑터가 내부와 상호작용하는 접점을 포트(port)라고 부릅니다. 헥사고날 아키텍처를 포트와 어댑터 패턴이라고 하는 이유가 이 때문입니다.

## Table of Contents
### 01. 계층형(Layered) 아키텍처의 문제는 무엇일까? (What’s Wrong with Layers?)
### 02. 의존성 역전하기 (Inverting Dependencies)
### 03. 코드 구성하기 (Organizing Code)
### 04. 유스케이스 구현하기 (Implementing a Use Case)
### 05. 웹 어댑터 구현하기 (Implementing a Web Adapter)
### 06. 영속성 어댑터 구현하기 (Implementing a Persistence Adapter)
### 07. 아키텍처 요소 테스트하기 (Testing Architecture Elements)
### 08. 경계 간 매핑하기 (Mapping Between Boundaries)
### 09. 애플리케이션 조립하기 (Assembling the Application)
### 10. 아키텍처 경계 강제하기 (Enforcing Architecture Boundaries)
### 11. 의식적으로 지름길 사용하기 (Taking Shortcuts Consciously)
### 12. 아키텍처 스타일 정하기 (Deciding on an Architecture Style)