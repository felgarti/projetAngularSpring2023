#                                                         Spring cloud Microservices and Angular front-end

# I. Backend :
  * [1. use case](#1-use-case)
  * [2 Inventory service - get all products](#2-inventory-service---get-all-products)
  * [3 Inventory service - get product by ID](#3-inventory-service---get-product-by-id)
  * [4 Customer Service - get All Customers](#4-customer-service---get-all-customers)
  * [5 Customer Service - get Customer by ID](#5-customer-service---get-customer-by-id)
  * [6 Bill Service - get bills](#6-bill-service---get-bills)
  * [7 Bill Service - get bill by id](#7-bill-service---get-bill-by-id)
  * [8 Eureka Service](#8-eureka-service)
# II. Frontend Angular Client :
  * [Login screen](#login-screen)
  ## Products
  * [1 Show all products](#1-show-all-products)
  * [2 Edit products](#2-edit-products)
  * [3 Delete products](#3-delete-products)
  * [4 Search for a product](#4-search-for-a-product)
  * [5 New Product](#5-new-product)
  ## Customers
  * [1 Show all customer](#1-show-all-customer)
  * [2 Edit Customer](#2-edit-customer)
  * [3 Delete Customer](#3-delete-customer)
  * [4 Search Customer](#4-search-customer)
  * [5 New Customer](#5-new-customer)
  ## Bills
  * [Show Bills](#show-bills)

# I. Backend :
## 1. use case

![image](https://user-images.githubusercontent.com/62290643/206123723-0f5d7345-b23d-4ecb-84cb-83346104a73d.png)

## 2 Inventory service - get all products
```http
GET /localhost:8888/PRODUCT-SERVICE/products
```

![image](https://user-images.githubusercontent.com/73041687/206929318-b672dbec-141f-4846-9e07-470e7a08334c.png)



## 3 Inventory service - get product by ID 
```http
GET /localhost:8888/PRODUCT-SERVICE/products/{id}
```

![image](https://user-images.githubusercontent.com/73041687/206929288-ab855f6a-12ae-47e4-9e8a-886c3527f016.png)



## 4 Customer Service - get All Customers
```http
GET /localhost:8888/CUSTOMER-SERVICE/customers
```

![image](https://user-images.githubusercontent.com/73041687/206929347-cf40fc1f-0e02-427e-a08a-72b46ae5d758.png)


## 5 Customer Service - get Customer by ID
```http
GET /localhost:8888/CUSTOMER-SERVICE/customers/{id}
```

![image](https://user-images.githubusercontent.com/73041687/206929369-0a75f580-5f7d-4d90-97cf-ce6ec9975bfa.png)


## 6 Bill Service - get bills
```http
GET /localhost:8888/BILLING-SERVICE/bills
```

![image](https://user-images.githubusercontent.com/73041687/206929423-264ef24f-0adb-4efb-a0f9-dee57243e4d4.png)


## 7 Bill Service - get bill by id
```http
GET /localhost:8888/BILLING-SERVICE/bills/{id}
```

![image](https://user-images.githubusercontent.com/73041687/206929439-146e7068-33c7-4396-9771-5acfdf2cbf83.png)


## 8 Eureka Service 
```http
GET /localhost:8761/
```

![image](https://user-images.githubusercontent.com/73041687/206929524-ac240628-ffa6-4c75-89ce-e0190e1b0f3b.png)

# II. Frontend Angular Client :
## Login screen 

![image](https://user-images.githubusercontent.com/101510983/206923607-8e842b94-d208-4dc6-8cbe-fb68db9037ec.png)

## Products
## 1 Show all products 

![image](https://user-images.githubusercontent.com/55364638/206925608-0b8e8b90-f8cf-45af-987a-550ffeb810e3.png)

## 2 Edit products 

![image](https://user-images.githubusercontent.com/101510983/206923795-26a19423-e941-4acd-878e-8a0ce1e3df11.png)

## 3 Delete products 

![image](https://user-images.githubusercontent.com/55364638/206925748-42a715d1-4713-45a3-889a-ccb3ca042ca5.png)

![image](https://user-images.githubusercontent.com/55364638/206925764-23a250e5-8a39-4293-b96c-575a22dfe68b.png)


## 4 Search for a product

![image](https://user-images.githubusercontent.com/55364638/206925802-0b184999-ccb0-4a54-9fc9-dcf419205f83.png)


## 5 New Product

![image](https://user-images.githubusercontent.com/55364638/206925875-db2771c4-e4b0-4970-8f5d-e7c699a9b4ee.png)

![image](https://user-images.githubusercontent.com/55364638/206925899-ebcd1e02-dfbe-43f0-b0ca-e52d264c84a9.png)

## Products
## 1 Show all customer

![image](https://user-images.githubusercontent.com/55364638/206925644-39d57c48-dd68-4d57-a563-a76e20dabe65.png)



## 2 Edit Customer

![image](https://user-images.githubusercontent.com/101510983/206924228-151e1ed2-e1d6-406d-8849-34da1dc34937.png)


## 3 Delete Customer 

![image](https://user-images.githubusercontent.com/55364638/206926221-6b3c8033-4f51-420a-89eb-9634b8322d2b.png)



## 4 Search Customer 

![image](https://user-images.githubusercontent.com/55364638/206926003-7e101bb2-764a-4083-8270-739fa6e95709.png)



## 5 New Customer 

![image](https://user-images.githubusercontent.com/55364638/206925953-153464e1-a35e-470b-ad44-9cf09874aa25.png)


![image](https://user-images.githubusercontent.com/55364638/206925982-3003c687-4601-4ee2-b88c-f0b2b58dcf3e.png)


## Bills
## Show Bills  

![image](https://user-images.githubusercontent.com/55364638/206925572-719bdaa5-0195-46e8-b4e2-7a190a300df9.png)


