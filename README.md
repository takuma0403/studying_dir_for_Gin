# studying_dir_for_Gin

### 実行テスト
- ```
  curl http://localhost:8080/albums
  ```
- ```
  curl http://localhost:8080/albums \
    --header "Content-Type: application/json" \
    --request "GET"
  ```
- ```
  curl http://localhost:8080/albums \
    --include \
    --header "Content-Type: application/json" \
    --request "POST" \
    --data '{"id": "4","title": "The Modern Sound of Betty Carter","artist": "Betty Carter","price": 49.99}'
  ```
- ```
  curl http://localhost:8080/albums/<id>
  ```

### 参考サイト
https://go.dev/doc/tutorial/web-service-gin