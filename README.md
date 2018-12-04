# 2018-02-OSSP-Fire-Recognition-System-with-YOLO
2018-2학기 공개SW프로젝트 2조 - YOLO기반 화재인식 시스템 

김선우 2014112616

조민제 2014111704

조예찬 2015111730

-------------------------------------------------------

# 2018.12.02

GUI와 화재 인식 메시지 전송 연동 완료.

YOLO에 클라이언트 소스코드 이식하여 window 서버로 메세지 전송 확인 완료.

YOLO에서 특정% 이상의 화재인식 시 서버로 '화재인식메세지'를 전송하는 방법 해결중..

인식률을 높이기 위한 데이터 트레이닝 진행중

Added Data files

--------------------------------------------------------

# .cfg 파일 수정

resolution 차이를 위한 처리

height, width 수정

Dataset anchors recalculation

subdivision = 16 -> 32 수정

learning rate 수정

