Database Order by 속도 이슈에 대한 고찰

1개 DB CPU에 리소스는 한정적이지만 를

Server는 여러개로 다중화하여 처리할 수 있기 때문에 서버에서 처리하는게 좋지 않을까





Order By 없이 결과만 추출

![image-20230815183059295](/Users/don/Library/Application Support/typora-user-images/image-20230815183059295.png)



Order By 있이 결과 추출

![image-20230815183150364](/Users/don/Library/Application Support/typora-user-images/image-20230815183150364.png)



같은 결과라도 정렬을 하고 않하고에 차이는 2배이상 분명했다.



보통 1개 서비스를 구축하게 되면 RDBMS를 이용한다는 전제하에



