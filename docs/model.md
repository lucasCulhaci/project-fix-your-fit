# Model
## User
- (ID)
- Username
- E-mail
- Country
- DeliveryFullName (nullable?) -> This only needs to be filled in if an item bought or sold
- DeliveryAddress (nullable?) -> This only needs to be filled in if an item bought or sold

## Clothing
- Type
- Brand
- Color
- Description
- Size

## Bundle
- (ID)
- ClothingID []
  - ! TODO : Come back to this
- Price

## Order
- (ID)
- OrderDate
- UserID
- OrderProduct [ ]
  - ProductId
  - Price
  - Quantity