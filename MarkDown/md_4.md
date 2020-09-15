## image 태그 

md 에서는 이미지도 만들수있다.

쉽게생각해서 img의 링크로 만드는거같다.

링크처럼 두가지 스타일이 있으며

1. 인라인 (inline)이미지 링크
```
    느낌표(!)를 입력하고 대체 텍스트를 대괄호([])로 묶은다음 링크를 소괄호(())로 묶습니다.
```
예를 들어서

http://octodex.github.com/images/bannekat.png 에 대한 이미지링크를 만들고
Benjamin Bannekat이라는 대체 텍스트를 만들려면

```
![Benjamin Bannekat](http://octodex.github.com/images/bannekat.png)
```
결과

![Benjamin Bannekat](http://octodex.github.com/images/bannekat.png)

실제로 실행해본 결과

대체 텍스트  : alt 태그 속성값이라는것을 알수있엇다.

2. 참조 (reference)이미지 링크
```
    ![alt 텍스트][이름/명칭]

    하단에서
    [이름/명칭]:이미지 src  <---띄어쓰기 조심할것
```

결과

![The foundin father][Father]



[Father]:http://octodex.github.com/images/founding-father.jpg
