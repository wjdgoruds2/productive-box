

## Setup

> Step 1

* Public으로 [Gist](https://gist.github.com/)를 생성합니다. 

    - 생성시 입력한 제목과 내용은 어차피 Override 되기 때문에 편하게 Gist를 생성합니다.

    - 그리고 사진 속에 표시된 값을 GIST_ID로 사용해야 하기 때문에 기록해둡니다.
    
![1](https://user-images.githubusercontent.com/18522341/80913341-deb4ad80-8d7e-11ea-9417-49a901680143.jpg)

---

> Step 2

* [Personal access tokens](https://github.com/settings/tokens/new)에서 Token을 생성합니다.

    - Select scopes은 `repo`와 `gist`를 추가합니다.
    
    - 생성 후 Token Key 값을 GH_TOKEN 값으로 사용해야하기 때문에 기록해둡니다.
    
![2](https://user-images.githubusercontent.com/18522341/80913346-e411f800-8d7e-11ea-9f60-f1415a8228db.jpg)

---

> Step 3

* Repository를 Fork 합니다.

* 그리고 Fork한 Repository에서 Actions 탭을 누른 후 활성화 시켜줍니다.

![3](https://user-images.githubusercontent.com/18522341/80913443-9d70cd80-8d7f-11ea-86b6-cb6416c7ad33.jpg)

---

> Step 4

* Repository -> Settings -> Secrets에서 `GIST_ID`와 `GH_TOKEN`를 생성해줍니다.

    - GIST_ID : [Gist](https://gist.github.com/)를 만들고 생긴 Key 값

    - GH_TOKEN : [Personal access tokens](https://github.com/settings/tokens/new)에서 생성한 Token 값
    
    
![4](https://user-images.githubusercontent.com/18522341/80913347-e5dbbb80-8d7e-11ea-820d-e1f09d9a84d9.jpg)

---

> Step 5

* 자신의 Gihub Home에서 생성한 Gist를 Pin으로 등록해줍니다.

![5](https://user-images.githubusercontent.com/18522341/80913348-e70ce880-8d7e-11ea-8823-e13684a85432.jpg)

---

> Step 6

* 정상적으로 노출이 되는지 확인합니다.

![6](https://user-images.githubusercontent.com/18522341/80913421-73b7a680-8d7f-11ea-984c-3824292646f6.jpg)

