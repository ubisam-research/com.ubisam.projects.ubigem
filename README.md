# com.ubisam.projects.ubigem

## 📚 소스 빌더 & 배포
1. 빌드
    1) UbiGEM 기본 버전은 basic repository에서 빌드
    2) UbiGEM Pemtron 고객사 용은 pemtron repository에서 빌드
    3) UbiCOM은 basic repository에서 README.md에 따라 빌드
    
2. 배포
    1) UbiGEM은 dist 폴더 내 UbiGEM_20211221.zip 화일을 고객에게 제공함
    2) UbiCOM은 dist 폴더 내 UbiCOM_20250515.zip 화일을 고객에게 제공함

3. Key Lock 관련
    1) 고객은 3시간동안 키락없이 사용할 수 있음 (3시간 지나면 연결 단절됨)
    2) Key Lock은 고객이 구매하면, 제공받은 고객은 usb를 pc에 꼽고 체크함
    3) Program Files\UbiSam\UbiGEM\BIN 폴더에 있는 UbiSam.Net.KeyLock.Checker.exe를 실행하며,
       버전 2.0은 동글 타입이어서 자동으로 인식함
    4) 키락은 장부장님께서 키락 생성 후 제공함
    5) 키락 1,0도 장석주부장님께서 키락 생성 후 제공 가능함

4. 추가 확인 사항
    1) 키락 생셩 소스 구미팀에 확인 필요
    2) UbiGEM.PAC 소스 & 빌더는 구미팀에 추가 확인 필요

## 📚 UbiCOM & UbiGEM 관련 문서
1. SEMI 문서
    1) SEMI 장비 통신 표준 문서 (SEMI Equipment Communications Standard)
        - [SEMI E5](./docs/SEMI/KE005-00-0813.pdf)
        - [SEMI E30](./docs/SEMI/KE30-00-0611.pdf)
        - [SEMI E37](./docs/SEMI/KE37-00-0413.pdf)