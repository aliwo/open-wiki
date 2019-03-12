Welcome to the Buvstreamer-Server wiki!



* **BASE URL**

    - 관리자 페이지: /console
    - API 서버: /api
    - 관리자 API: /admin

* **Authorization**
    
    HTTP 헤더인 Authorization 을 사용합니다. 타입은 Bearer 입니다.
    토큰은 구글 login 혹은 회원가입 이후로 주어진 토큰을 사용합니다.
    토큰의 유효기간은 1시간이며, 앱 내부적으로 login 을 호출하여 만료 전에 refresh 해주어야 합니다.
    자세한건 **[사용자]로그인** 문서 참조
    
    예시:
    ```
    "Authorization" : "Bearer ya29.Glu8BiFpCmKKHH90rbgLw1HrZJQCZ6KkpFzrCVLkJDMRAO4KdDOp9IPziXN5JDvZrh9tXRAdaaRcLLGe27sSJ-qM8Ok-cB5sxMi0aaoZcZj3a2a_pMQYFKdDZuHj"
    ```
    






