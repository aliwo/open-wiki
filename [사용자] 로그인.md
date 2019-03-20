**로그인**
----

    Oauth 로그인

* **URL**

  /auth/login

* **Method:**
  
  |`GET`|
  
*  **URL Params:**
    
    N/A

   **Required:**
 
    N/A

   **Optional:**
 
    N/A

* **Data Params**



* **Success Response:**
  
  * **Code:** 302(추정) <br />
    **Content:** `auth/login_callback` 으로 리다이렉트 되며, 성공시 아래 response 를 받습니다.
    
  ```json
      {"ok": true, "access_token": "<access token 값>"}
   ```    
 
* **Error Response:**

  N/A

* **Sample Call:**

  N/A
   ```
* **Notes:**

   로그인시 유저 썸네일이 업데이트 됩니다!
