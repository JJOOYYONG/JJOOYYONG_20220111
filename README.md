# JJOOYYONG_20220111
1분코딩예제
.world{
            display: flex;
            align-items: center;
            justify-content: center;
            width: 100vw;
            height: 100vh;
            perspective: 500px;  -> 500px 만큼 투영점 지정 하며 자식요소까지만 영향을 끼침
        }
        
 .poster{
            position: relative;
            width: 200px;
            height: 250px;
            border-radius: 10px;
            background-color: yellow;
            animation: poster-ani 1.6s infinite linear alternate;
            transform-style: preserve-3d; -> poster의 자식요소는 world의 3D 효과를 받지 못하기때문에 지정함
        }       
