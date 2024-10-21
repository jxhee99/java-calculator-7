# java-calculator-precourse
<h1 style="color: #000000; text-align: start;"><b>💾 구현할 기능 목록 정리</b></h1>
<ul style="list-style-type: disc; color: #000000; text-align: start;" data-ke-list-type="disc">
<li>기본 구분자 계산 메서드
<ul style="list-style-type: disc;" data-ke-list-type="disc">
<li>구분자+양수를 입력</li>
<li>쉼표(,) or 콜론(:)을 기준으로 숫자 분리 후 합계 계산</li>
<li>빈 문자열(&ldquo;&rdquo;)을 입력하면 0을 반환</li>
</ul>
</li>
<li>커스텀 구분자 계산 메서드 (쉼표와 콜론 제외)
<ul style="list-style-type: disc;" data-ke-list-type="disc">
<li>// 과 \n 사이에 위치한 커스텀 문자를 기준으로 숫자 분리 후 합계 계산</li>
<li>예외 : 문자열 앞부분이 아닌 다른 곳에 위치할 경우<span>&nbsp;</span>IllegalArgumentException<span>&nbsp;</span>발생 후 애플리케이션 종료</li>
</ul>
</li>
<li>입력값이 비었거나, 잘못된 값인지 점검하는 메서드 생성
<ul style="list-style-type: disc;" data-ke-list-type="disc">
<li>잘못된 값을 입력할 경우&nbsp;IllegalArgumentException메세지 출력</li>
<li>애플리케이션 종료</li>
<li>예외 : 0 이상의 양수 체크 함수(음수 또는 소수점 포함된 숫자 x)</li>
</ul>
</li>
</ul>
