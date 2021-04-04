# 키프레임 사각형 좌표변경 로딩 애니메이션

- index.html

- style.css

animation: loading 2s infinite;
끊김을 나타내기 위해 linear를 사용 안함

left : calc(100% - 10px);
top : calc(100% - 10px);

100%로 이동할 때
부모요소 바깥으로 나오기 때문에
자기자신 너비(left), 높이(top) 빼주기 위한 함수
calc를 사용
