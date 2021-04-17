# Ecommerce Catalog

This data has been collected from various sources to serve as a resource for seeding and testing.

# Disclaimer
Don't use this data / link for production, this is strictly for dev / practice environments.

## Features

* JSON data
* Categories
  * Name
  * Image
  * Subcategory
* Items
  * Item Title
  * Item Description
  * Brand (37% available)
  * Inventory availability
  * Image S3 Url (88% available)
  * Price
  * `google_product_category` (90% accurate)
  * `google_product_type`
  * Category

## Structure

### Category Structure
```json
{
    "name": "Mobiles & Tablets",
    "image": "https://s2smyshop.s3.ap-south-1.amazonaws.com/aKJh2iFzZO7zuwhNpcAAocWM9C4VePM6.png",
    "sub_category": [
        {
            "name": "Mobiles Accessories",
            "image": "https://s2smyshop.s3.ap-south-1.amazonaws.com/9mHO15jAewvIS1xRuZvjzv0ow7KYfosY.png"
        },
        {
            "name": "Tablets Accessories",
            "image": "https://s2smyshop.s3.ap-south-1.amazonaws.com/89KcBT6SsWSohhtS79fxEhO3NduLfVqo.png"
        },
        {
            "name": "Mobiles Cases",
            "image": "https://s2smyshop.s3.ap-south-1.amazonaws.com/v0YiLKD8wsdgQGSg7ktkQmM26hjD4Bmd.png"
        },
        {
            "name": "Mobiles",
            "image": "https://s2smyshop.s3.ap-south-1.amazonaws.com/ilu6olqt4N9252hhqWHU1dRBCNd640fg.png"
        },
        {
            "name": "Tablets",
            "image": "https://s2smyshop.s3.ap-south-1.amazonaws.com/1QXhq1zMX3ODDsQVgKtN7h9sGmsfG4ry.png"
        }
    ]
}
```

### Item Structure
```json
{
    "title": "Apple iPhone 7 With FaceTime - 32GB, 4G LTE, Gold",
    "description": "With all the fanfare surrounding the launch of apple iphone 7 the phone has finally made it to the market once again staying true to all the hype and expectations. the iphone 7 rose gold comes with the best battery life ever seen on an iphone and it will last two hours longer than the iphone 6s. apple iphone 7 features a new a10 fusion processor which is about 40 percent faster than previous models.",
    "brand": "Apple",
    "inventory": 4,
    "image": "https://s2smyshop.s3.ap-south-1.amazonaws.com/uEBNJDjSYLVgoZLT8vZ9FXCbuL59INu5.png",
    "price": 500,
    "google_product_category": 267,
    "google_product_type": "Consumer Electronic > Mobiles & Accessories > Mobiles",
    "category": "Mobiles"
}
```
### Contact
[rehan_manzoor@outlook.com](mailto:rehan_manzoor@outlook.com)