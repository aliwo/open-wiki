**HOT BJ 조회**
----

    HOT BUV 목록을 조회합니다.
    hot buv 선별 기준: 좋아요 수 (50%) + 하트 준 사람 수 (50%) 로 결정, 일주일 마다 다시 계산합니다.
    

* **URL**

  /user/hotbuv

* **Method:**
  
  |`GET`|
  
*  **URL Params:**
    
    N/A

   **Required:**
 
    N/A

   **Optional:**
 
    N/A

* **Data Params**
    
    N/A

* **Success Response:**
  
  * **Code:** 200 <br />
    **Content:**
    
  ```json
    {
      "okay":true, 
      "users":[
        {
            "id": 1,
            "google_id": 11028437,
            "name": "recordable542",
            "google_picture": "https://lh4.googleusercontent.com/-ufC0a8TTdN4/AAAAAAAAAAI/AAAAAAAABjA/C6tCvQDtOe8/photo.jpg",
            "followers": 10,
            "hearts": 20
        },
        {
            "id": 2,
            "google_id": 91028424,
            "name": "하이",
            "google_picture": "https://lh4.googleusercontent.com/-ufC0a8TTdN4/AAAAAAAAAAI/AAAAAAAABjA/C6tCvQDtOe8/photo.jpg",
            "followers": 20,
            "hearts": 3
        }
      ]
    }
   ```    
 
* **Error Response:**

  N/A

* **Sample Call:**

  N/A
   ```
* **Notes:**

   메모 메모 노트노트
