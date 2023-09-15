모델 폴더를 생성해두었습니다. ipynb와 모델 파일은 해당 폴더에 업로드를 합니다. 개인별 폴더는 생성하지 않았습니다.

![](https://i.imgur.com/h0PcRvK.png)

<br>

1. 파일 명의 규칙을 설정해 두었습니다. `(이름)_(날짜)_(순번).ipynb`
예) 같은 날짜에 1번째 업로드 시 : `최준혁_916_1.ipynb`
같은 날짜에 2번째 업로드 시 : `최준혁_916_2.ipynb`
다음 날짜에 1번째 업로드 시 : `최준혁_917_1.ipynb`

![](https://i.imgur.com/CRtGDGb.png)

<br>
2. 모델 commit 시 `git commit -m "이름, RMSE, R2Score"` 를 작성합니다. RMSE, R2는 소숫점 5번째 자리까지만  작성합니다.  
예) git commit -m "최준혁 RMSE: 0.10571 R2 : 0.98786"

![](https://i.imgur.com/AVYsPzI.png)

<br>

3. comment 작성 시 제목에 `이름, RMSE, R2Score`를 작성합니다. 가독성을 위해 `소숫점 5번째` 자리까지만 작성합니다. 추가적인 사항이 있다면 Write에 comment를 남겨둡니다.

![](https://i.imgur.com/7YBAvqm.png)

<br>

4. 커밋 내역은 repo의 메인페이지의 기록을 보면 확인할 수 있습니다.
![](https://i.imgur.com/VlChT1X.png)
![](https://i.imgur.com/Jawp4mc.png)
