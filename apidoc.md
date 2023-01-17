
    
List Of Category
http://localhost:9500/Category

List of Products
http://localhost:9500/Products

page 1
Products wrt CategoryId 
http://localhost:9500/Products?CategoryId=1

page 2 //filter categories

http://localhost:9500/Products?category=Mens%20Fashion

filter by price
http://localhost:9500/FilterPrice/1?LowCost=100&HighCost=500

filter by brand



page 3 //Detail page   //fetch products

//by ObjectId
http://localhost:9500/details/63c41b682356be2e77e07a87

//by ProductId
http://localhost:9500/details/5

page 4 //order summery page///fetch products
//Place order
localhost:9500/placeOrder

//view order
localhost:9500/viewOrder

page 2 //Payment gate way //paytm