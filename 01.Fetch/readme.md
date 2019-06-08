## intro

### pre-requisite: a basic understanding of Ajax and es6 promise(async/await)

- Web-Programming의 HTTP request에는, 크게 get과 post가 있다.
- get: 어떤 정보를 가져와도 될까요?
- post: 당신에게 어떤 정보를 보내도될까요?
- fetch() API 는 위 두 요청을 다 수행할 수 있도록 기능을 제공한다.

### outline

1. call fetch function (path)
2. write down response () as part of a promise
   (response is a stream of data which could be text or blob(img) or JSON )
3. complete data stream (grap body of the response)
4. make an <img> element with the above data
5. handle error

Reference lists:
https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API
https://www.youtube.com/watch?v=tc8DU14qX6I
