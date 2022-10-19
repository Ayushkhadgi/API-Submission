// Page1

# List of Category
Local > http://localhost:2500/category
Live  > https://ayushak.herokuapp.com/category
# List of Items
Local > http://localhost:2500/items
Live  > https://ayushak.herokuapp.com/items

//Page2

# List of Items wrt Category
Local > http://localhost:2500/products?categoryid=2
Live  > https://ayushak.herokuapp.com/products?categoryid=2
# List of Items wrt Brand
Local > http://localhost:2500/brand?brandid=1
Live  > https://ayushak.herokuapp.com/brand?brandid=1
# Items wrt cost & Brand
Local > http://localhost:2500/filter/2?lcost=1200&hcost=2000
Live  > https://ayushak.herokuapp.com/filter/2?lcost=1200&hcost=2000
# Sort on basis of cost
Local > http://localhost:2500/filter/1?lcost=599&hcost=20000&sort=-1
Live  > https://ayushak.herokuapp.com/filter/1?lcost=599&hcost=20000&sort=-1

//Page3

# Details of the product
Local > http://localhost:2500/details/7
Live  > https://ayushak.herokuapp.com/details/7

//Page 4

# Item Details(Post)
Local > http://localhost:2500/Itemdetails
[
    {
        "_id": "634ddcdf6c0e044b3ff312b8",
        "id": 2,
        "name": "Vincent Chase",
        "category_id": 1,
        "brand_id": 2,
        "product_id": 7,
        "image": "https://i.ibb.co/sPxzQkD/vincent-chase-vc-e14036-c2-eyeglasses-26-nov-vc-female-theme19876-148491.jpg",
        "info": "The design of Vincent chase eyeglasses for Eyeglasses for men are quite study yet elegant.",
        "cost": 1299
    },
    {
        "_id": "634ddcdf6c0e044b3ff312c7",
        "id": 7,
        "name": "Camerii",
        "category_id": 2,
        "product_id": 55,
        "image": "https://i.ibb.co/dLt8sdm/camerii.jpg",
        "info": "These coloured sunglasses from the house of camerii will never let you down in terms of style. These half-rim sunglasses are lightweight and long lasting. These uv-protected sunglasses will protect your eyes from the harmful sunrays and pollution. Team these with your casual attire to look stunning.",
        "cost": 2699
    },
    {
        "_id": "634ddcdf6c0e044b3ff312cb",
        "id": 1,
        "name": "Prospek",
        "category_id": 3,
        "product_id": 44,
        "image": "https://i.ibb.co/cy3hYrh/prospek.jpg",
        "info": "Redirects blue light away from eyes.Very lightweight lenses includes a protective case and cleaning cloth.",
        "cost": 1299
    },
    {
        "_id": "634ddcdf6c0e044b3ff312e0",
        "id": 2,
        "name": "Grey Jack",
        "category_id": 5,
        "product_id": 44,
        "image": "https://i.ibb.co/RjGYzKK/grey-jack.jpg",
        "info": "When you want to shield your eyes, you can also enjoy peace of mind that the photochromic lenses will block out 100% of both UVA and UVB rays from the sun.",
        "cost": 1489
    }
]
Live  > https://ayushak.herokuapp.com/Itemdetails
# Place Order (POST)
Local > http://localhost:2500/placeOrder
{
    "orderid" : 2,
    "Name" : "Kajal",
    "email": "kajal123@gmail.com",
    "address": "Tandapeth,Nagpur",
    "phone": 8862077489,
    "cost" : 3999,
    "Item" : "Titan Eye Plus"
}
Live  > https://ayushak.herokuapp.com/placeOrder

//Page 5

# List of orders
Local > http://localhost:2500/orders
Live  > https://ayushak.herokuapp.com/orders
# List of order wrt to email
Local > http://localhost:2500/orders?email=kajal123@gmail.com
Live  > https://ayushak.herokuapp.com/orders?email=kajal123@gmail.com
# Update Payment Details (PUT)
Local > http://localhost:2500/updateOrder/2
{
    "status":"Pending",
    "bank_name":"CBI",
    "date":"17/10/2022"
}
Live  > https://ayushak.herokuapp.com/updateOrder/2

# Delete Order (Delete)
Local > http://localhost:2500/deleteOrder/634dc6080cb179bb20d0ec7c
Live  > https://ayushak.herokuapp.com/deleteOrder/634dc6080cb179bb20d0ec7c