# style에서 사용되는 표현식
- first-child : 첫번째 줄의 태그를 나타내는 식(h1:first-child : h1의 첫번째줄)
- nth-child(n) : n번째 줄의 태그를 나타내는 식(h1:nth-child(3))
- h1:nth-child(2) > u : 태그안에 자식으로 감싸져있는 경우 style이 먹히지 않아 자식까지 들어가서 표현해줘야함.
- h1:last-child : 마지막 번째 태그 값을 나타내는 식
- h1:nth-of-type(2) : h1태그의 두번째로 사용된 곳을 나타내는 식