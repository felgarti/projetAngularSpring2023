
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
   # III. Keycloak
  * [1 Realm](#1-realm)
  * [2 Client](#2-client)
  * [3 Utilisateurs](#3-users)
  * [4 Rôles](#4-roles)
  * [5 Tokens](#4-tokens)
  * [6 Service sécurisé](#5-Service-sécurisé)
  # IV. Kafka :
  * [1 Supplier](#1-supplier)
  * [2 Consumer](#2-Consumer)
  * [3 Kafka streams ](#3-Kafka-streams )


# V. Docker :


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

![image](https://user-images.githubusercontent.com/73041687/206929892-83e8cd20-7442-4873-9e52-eb3154df776a.png)

## 2 Edit products 

![image](https://user-images.githubusercontent.com/73041687/206929756-7052ed34-740d-4058-8793-6f42bd9f5a41.png)

## 3 Delete products 

![image](https://user-images.githubusercontent.com/73041687/206929919-485dfbe1-c754-48fe-b4d7-0374a398b324.png)

![image](https://user-images.githubusercontent.com/73041687/206929937-de44096c-5313-4b19-a75e-f111e5bd5d88.png)


## 4 Search for a product

![image](https://user-images.githubusercontent.com/73041687/206929964-4d5b51b5-e8b5-446b-b81a-c07516b63f4c.png)


## 5 New Product

![image](https://user-images.githubusercontent.com/73041687/206930056-665a96b1-6902-46fe-9770-288308236422.png)

![image](https://user-images.githubusercontent.com/73041687/206930073-1a2a33f3-5b18-47bc-b52e-31487eaea6f4.png)

## Products
## 1 Show all customer

![image](https://user-images.githubusercontent.com/73041687/206930084-b11cfba1-3b0e-47fb-baa3-6048a14d7184.png)



## 2 Edit Customer

![image](https://user-images.githubusercontent.com/73041687/206930096-d2223830-9144-45d2-a92a-10ac9a88bf85.png)


## 3 Delete Customer 

![image](https://user-images.githubusercontent.com/73041687/206930116-4326434c-12c3-4900-a70a-f766b3614462.png)
![image](https://user-images.githubusercontent.com/73041687/206930130-78344fad-71ee-49a0-92ba-43da1760b0f8.png)




## 4 Search Customer 

![image](https://user-images.githubusercontent.com/73041687/206930151-de613158-8fee-417f-bb35-46c8483a2088.png)



## 5 New Customer 

![image](https://user-images.githubusercontent.com/73041687/206930170-202df8be-98b5-48d7-b803-c44c819677ed.png)


![image](https://user-images.githubusercontent.com/73041687/206930187-03b8b8cd-22f4-44e9-8067-e508a471b9e1.png)


## Bills
## Show Bills  

![image](https://user-images.githubusercontent.com/73041687/206930409-7593d23d-fd37-4f3d-a34e-598a04895976.png)

# III. Keycloak :
```To start Keycloak
> ...\bin\standalone.bat
```

## 1. Realm

![image](https://user-images.githubusercontent.com/73041687/219620750-5378152e-a955-45e1-9bd2-699374405d80.png)

## 2. Client

![image](https://user-images.githubusercontent.com/73041687/219620904-dd7f3c62-636a-41c8-b327-106fa3cf47cc.png)

## 3. Utilisateurs

![image](https://user-images.githubusercontent.com/73041687/219620974-3fa8bea4-4be1-43c3-9b89-44841369e2f7.png)

## 4. Rôles
![image](https://user-images.githubusercontent.com/73041687/219621061-6890af29-2d3e-44c1-890a-02e970ca78b8.png)

![image](https://user-images.githubusercontent.com/73041687/219621157-94bd7359-07d2-48e6-91b5-661348334d60.png)

## 5. Tokens

![Capture d’écran 2023-02-09 173815](https://user-images.githubusercontent.com/73041687/219621277-d957395c-559d-402a-a06a-232e1109cccf.jpg)

![Capture d’écran 2023-02-09 173750](https://user-images.githubusercontent.com/73041687/219621287-ef639e50-0db2-4a9c-a805-6510b070b746.jpg)

## 6. Service sécurisé

![image](https://user-images.githubusercontent.com/73041687/219621563-7e6a5211-68be-44be-b764-45867cf51713.png)


# IV. Kafka :
## 1. Supplier

![image](https://user-images.githubusercontent.com/73041687/219654966-8ed99356-f63b-449b-b782-480121de32f6.png)

![image](https://user-images.githubusercontent.com/73041687/219687628-a8c20cbe-a87a-4375-9636-b932406c01ac.png)


## 2. Consumer

![image](https://user-images.githubusercontent.com/73041687/219677290-25fc52df-3a92-4a65-8e3e-dbf559b2f1de.png)

## 3. Kafka streams 

![image](https://user-images.githubusercontent.com/73041687/219668084-72ac27e1-849e-4fe5-bec0-9eb63685b965.png)



# V. Docker :

## Billing service 
![image](https://user-images.githubusercontent.com/73041687/219697077-feed41f4-1a89-45e8-9206-19451d6dc80a.png)
## Inventory service
![image](https://user-images.githubusercontent.com/73041687/219698461-5131e970-68b0-4978-a159-a0c628cdb856.png)

![image](https://user-images.githubusercontent.com/73041687/219706814-b5b679ad-30b0-4848-a57c-743ddd0b2798.png)
## Customer service
![image](https://user-images.githubusercontent.com/73041687/219711327-4aa8d7a0-ce1a-4472-b641-f786e4c21cac.png)
## gateway service
![image](https://user-images.githubusercontent.com/73041687/219712194-4ea37e61-e626-4d56-97eb-b2bbef4cac46.png)
## Eureka discovery
![image](https://user-images.githubusercontent.com/73041687/219712878-4d8b842d-bba9-4029-b066-2008989cbd1c.png)
## Frontend catalog
![image](https://user-images.githubusercontent.com/73041687/219715512-4cac181c-f35b-4870-9df7-e69f328714ce.png)






