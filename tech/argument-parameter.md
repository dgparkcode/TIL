# Argument, Parameter 의미 차이

별 생각없이 사용하던 args, params 의 차이점이 궁금해 찾아봤다.

## Argument(전달인자)

함수를 호출할 때 전달되는 의미있는 실제 값을 의미한다.   

```
val card = Card()
setCard(card)
```

위의 코드에서 setCard 함수를 호출하는데 전달되는 `card`값은 `argument`가 된다.   

## Parameter(매개변수)

정의된 함수내에서 사용되는 전달받은 값을 의미한다.

```
fun setCard(card: Card) {
...
}
```

위의 함수 코드에서 전달받은 `card`값은 `parameter`가 된다.

## 참고
- http://taewan.kim/tip/argument_parameter/
- https://wayhome25.github.io/etc/2017/12/31/parameter-argument/
- https://m.blog.naver.com/jaysrogers/221557844273