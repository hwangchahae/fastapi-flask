# isntall
```
pip install fastapi uvicorn sqlalchemy
```
# Fast API 실행 - main.py가 있는 api폴더에서 진행
```
cd api
uvicorn main:app --reload  
```
# API 테스트
```
http://localhost:8000/docs
http://127.0.0.1:8000/docs
```

# Flaks 설정
```
pip install flask
```
# Flask 실행
```
새 터미널 - cd frontend 
python app.py
```
# 주요 에러
```
CROS
pydantic으로 API서버에서 데이터정의를 했기때문에 타입에 맞게 데이터를 넘겨줘야함
```


# API서버
```
-사용자
    -회원가입(/api/register)
    -로그인(/api/login)
    -사용자 정보 조회(/api/user/{user_id})

-상품관련
    -전체 상품 조회(/api/products)
    -상품상세조회(/api/products/{product_id})
    -상품등록(/api/products)
    -상품수정(/api/products/{product_id})
    -상품삭제(/api/products/{product_id})
-장바구니
    -담기(/api/cart)
    -조회(/api/cart)
    -수량수정(/api/cart/{cart_id})
    -상품삭제(/api/cart/{cart_id})
- 주문 
    - 주문하기(/api/order)
    - 주문목록 조회(/api/order)
    - 주문 상세 조회(/api/order/{order_id})
    - 주문 상태 변경(/api/order/{order_id}/status)
```

# 2.웹서버
```
-메인페이지(/)
-로그인페이지(/login)
-회원가입페이지(/register)
-상품목록페이지(/products)
-장바구니페이지(/cart)
-주문내역페이지(/orders)
```