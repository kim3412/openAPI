# Open API 활용 예제
국회의원 정보제공 서비스 API를 이용해서 당선횟수별 국회의원 목록을 조회하고 csv 파일로 저장

요청 메시지  
numOfRows: 한 페이지 결과 수  
pageNo: 페이지 번호  
reele_gbn_cd: 당선횟수코드(초선 105001, 재선 105002, 3선 105003, 4선 105004, 5선 105005, 6선 105006, 7선 105007)  

응답 메시지 명세  
deptCd: 부서코드  
empNm: 한글이름  
engNm: 영문이름  
hjNm: 한자이름  
jpgLink: 의원사진파일 다운로드 경로  
origNm: 선거구  
reeleGbnNm: 당선횟수  
