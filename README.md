# YBZServer
Get /api/signup?UserName=YBZ&Password=YBZ123
response:  
  application/json:  
  {
    "UserId":123321
  }
  
Get /api/login?UserName=YBZ&Password=YBZ123
response:  
  application/json:  
  {
    "UserId":123321
  }
  
Get /api/item/list
response:  
  application/json:  
  {
    "ItemList": [
        {
          "ItemId": 12331222,
          "ItemName": "商品名称",
          "ItemDescription": "商品描述"
        }
    ]
  }
  
Get /api/cart/add?item
response:  
  application/json:  
  {
    "ItemList": [
        {
          "ItemId": 12331222,
          "ItemName": "商品名称",
          "ItemDescription": "商品描述"
        }
    ]
  }
