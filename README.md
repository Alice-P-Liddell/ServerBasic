# ServerBasic
Basic server for useful source
Mobile multi-play tic-tac-toe game

# 서버 사용 방법

## Signup
#### 요청
> [POST] /users/signup

전달값 (Json)
<pre>
{
  'username':'hongildong',
  'password':'hong1234',
  'name':'홍길동'
}
</pre>

#### 결과

성공
<pre>
{
  '_id':'1234567890',
  'username':'hongildong',
  'name':'홍길동'
}
</pre>


실패
<pre>
{
  'message':'400 Bad Request'
}
</pre>

## Signin
#### 요청

#### 결과
