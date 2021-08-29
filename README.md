# Alfred-UPbit_MyAssetValue
This Workflow is for Korean UPbit users.  
[업비트](https://upbit.com/home)에서 내 자산 정보를 가져오는 풀 한국어 워크플로우입니다. 실시간 가격 기반이며, 아직 원화마켓만 지원합니다.<br/><br/>
  
----------
## 설치 방법
* 업비트 홈페이지 > 마이페이지 > [Open API 관리](https://upbit.com/mypage/open_api_management?)에서 '자산조회'에 체크한 후 API키를 발급받습니다. (Secret Key는 한 번만 보여주므로 잘 메모해두어야 합니다.)
* "[UPbit My Asset Value.alfredworkflow](https://github.com/custardcream98/Alfred-UPbit_MyAssetValue/raw/main/UPbit%20My%20Asset%20Value.alfredworkflow)"를 다운로드합니다.
* [Releases](https://github.com/custardcream98/Alfred-UPbit_MyAssetValue/releases)에서도 다운받을 수 있습니다.
* 다운로드한 파일을 더블클릭합니다.
<img src ="https://user-images.githubusercontent.com/87423085/131264038-c7fc3359-3610-4700-a064-cde82aa72805.png">
* 'Import Value (editable)'의 UPBIT_API_ACCESS_KEY 와 UPBIT_API_SECRET_KEY 에 앞서 발급받은 API를 채워넣습니다.

<br/><br/>
## 주의! API키 발급시 '자산조회'이외의 항목 (예 : 출금하기) 등에 체크 시 보안상 위험할 수 있습니다.
## API 키 관리에 익숙하지 않다면 자산조회만 가능한 API키를 발급받으시길 권장드립니다.
### 또한, 가능하다면 '특정 IP에서만 실행'을 체크 후 본인의 IP주소에서만 접속 가능하도록 하는 것이 좋습니다. 
<br/><br/>


## 사용법
### 내 전체 자산 조회하기
![image](https://user-images.githubusercontent.com/87423085/131264345-09e5e619-9f56-4426-9a82-54a0b164aa56.png)
* `upmy` : 내 전체 자산 평가가치를 보여줍니다.
* 특정 티커로 이동해 Enter를 누르면 업비트 가격 페이지로 이동합니다.
* 전체 자산 평가가치 부분에서 Enter를 누르면 업비트 홈페이지로 이동합니다.
<br/><br/>
### 내 특정 자산 조회하기
![image](https://user-images.githubusercontent.com/87423085/131264383-013792f2-2137-4da1-84e5-e287c427f39f.png)
* `upmy {Ticker}` : 티커를 입력하면 해당 자산의 평가가치를 보여줍니다.
* Enter를 누르면 업비트 가격 페이지로 이동합니다.
<br/><br/>
### 내 전체 자산 평가 가치만 조회하기
![image](https://user-images.githubusercontent.com/87423085/131264412-84983bef-113c-4560-bda1-ee0e5e6f6939.png)
* `upmy tot` : 티커로 'tot'을 입력하면 전체 자산 평가가치만 보여줍니다.
* Enter를 누르면 업비트 홈페이지로 이동합니다.
<br/><br/>

## Credits
* [Alfred-Workflow](https://github.com/deanishe/alfred-workflow) by denishe
* [PyJWT](https://github.com/jpadilla/pyjwt) by jpadilla
* [requests](https://github.com/psf/requests) by psf
* [urllib3](https://github.com/urllib3/urllib3) by urllib3
* [python-certifi](https://github.com/certifi/python-certifi) by certifi
* [UPbit](https://upbit.com/home)

