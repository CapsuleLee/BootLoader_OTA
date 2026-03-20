 
###BootLoader_OTA (Infineon AURIX TC234LP)
##AUTOSAR Layered Architecture 기반의 Infineon AURIX TC23x용 Bootloader 및 OTA(Over-The-Air) 구현 프로젝트

 - 제한된 128KB의 Flash 자원을 관리하기 위해 FeeThreshold 설정을 최적화해 가비지 컬렉션의 실행 시점을 제어
 - UDS 프로토콜 및 메모리 스택 통합한 리프로그래밍 BSW 아키텍처를 설계
 - 업데이트 중 예기치 못한 오류 상황에서 제어기가 불능 상태에 빠지는 것을 차단하기 위해, 링커 스크립트에서 메모리 맵을 획정하고 부트로더와 어플리케이션 영역을 분리
 - 디지털 서명검증(SHA-256)을 통해 데이터의 무결성과 출처를 검증
