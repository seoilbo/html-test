차고지 설정 안내

1) garage.kml의 각 차고지는 Point Placemark로 등록합니다. Placemark 이름은 depot/index.json의 placemark와 일치시킵니다.
2) 운수사를 KML 설명에 추가할 때는 다음 형식을 사용합니다.
   운수사: 북부운수, 대원 계열사, 메트로버스
3) depot/index.json의 operators와 KML 설명의 운수사 목록은 합쳐서 표시됩니다.
4) routes 배열에는 해당 차고지에서 운행할 KML 파일명을 적습니다. 모든 노선을 허용하려면 ["*"]를 사용합니다.
5) 현재 2416.kml은 시작 좌표가 중랑차고지 인근이라 중랑차고지에 연결했습니다.
