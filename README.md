# service-product

Desarrollo de Curso de #microservicios con #SpringBoot y #SpringCloud 

Tecnologías:
- API Rest
- JPA / HIBERNATE

Herramientas:
- IntelliJ IDEA
- Postman

URLs:
- GET http://localhost:8091/products
- GET http://localhost:8091/products?categoryId=1
- GET http://localhost:8091/products/1
- POST http://localhost:8091/products
/ JSON: {
  "name": "Wallabee",
  "description": "Comfort",
  "stock": 1,
  "price": 30,
  "category": {"id":1,"name":"shoes"}
  }
- PUT http://localhost:8091/products/4 / JSON: {
  "name": "Wallabee",
  "description": "Comfort",
  "stock": 1,
  "price": 35,
  "category": {"id":1,"name":"shoes"}
  }
- GET http://localhost:8091/products/3/stock?quantity=10

From Digital Lab Academy