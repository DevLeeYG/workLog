# workLog


<details>
    <summary>2022-11-09</summary>

<!-- summary 아래 한칸 공백 두고 내용 삽입 -->

<h1> 내역서 다운로드 횟수 표시 </h1>

<div>CoopStatementFIle.popup 에서 다운로드 클릭 하면 다운로드와 동시에
백엔드로 post 요청을 보내야한다. 
백엔드에서 요청을 받아 아이디를 확인한후 컬럼에 입력을 해서 다운로드 횟수를 적용한다

그와 동시에 공고목록 표시에서 해당 투찰건의 내역서 다운로드 표시를 나타내준다.
</div>

<div>
BID_ID와 COID 넘버로 내역서 확인을 한다음 DW_FILE_ctn 의 카운트를 올려야할듯
TB_COOP_BID 에 칼럼을 추가합시다
 
</div>
 
</details>
