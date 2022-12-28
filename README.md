# Laravel API with Sanctum
Tutorial from [Traversy Media](https://www.youtube.com/watch?v=MT-GJQIY3EU)

- Get or index all product
  ```
  http://laravel-sanctum-api.test/api/products
  ```
  
- Get or show product by id
  ```
  http://laravel-sanctum-api.test/api/products/1
  ```

- Post  or create product
  
  with header 
  - key = Accept 
  - value = application/json
  
  and the requirement
  - name = required
  - slug = required|unique:products
  - price = required|numeric|min:1
  - description = optional

  ```
  http://laravel-sanctum-api.test/api/products
  ```

- Put or update product by id
  
  with header 
  - key = Accept 
  - value = application/json
  
  and the requirement
  - name = required
  - slug = required|unique:products
  - price = required|numeric|min:1
  - description = optional
  
  ```
  http://laravel-sanctum-api.test/api/products/7
  ```

- Delete product by id
  ```
  http://laravel-sanctum-api.test/api/products/7
  ```

- Search or get product by name
  ```
  http://laravel-sanctum-api.test/api/products/search/productname
  ```
