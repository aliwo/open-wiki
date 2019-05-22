**클립 업로드용 access_token 받기**
----
  
  클립을 업로드용 token 을 받습니다.

* **URL**

  /cow/clip

* **Method:**
  
  | `GET` |
  
*  **URL Params**

   **Required:**
 
   N/A
   
   **Optional:**
 
   N/A

* **Data Params**

    N/A
    
    **Optional:**
    
    N/A

* **Success Response:**
  
  * **Code:** 200 <br />
    **Content:** 
    ```json
        {
            "okay": true,
            "access_token": "ya29.GlsIB-H6uaU9vBqNM5JidVfl0Eog5gHmLwrZQSL0gPRwUDBJp9LCgiXM6BwfmOEt4icQpJN-X1oWNtdJR0-oCYQwNBL-DHnNlBfa2CXzfRj7I_cN-NmyOwUEXXPN"
        }
    ```
 
* **Error Response:**

  * **Code:** HTTP_503_SERVICE_UNAVAILABLE <br />
    **Content:** `{"okay": false}, `
    **Reason:** `SW가 아직 cow 등록을 안했습니다! 개발자에게 문의하세요`
    
    

* **Sample Call:**


* **Notes:**

