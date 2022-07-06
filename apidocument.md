// page 1 : jewllery page //To get all the jwellery available

(Get) https://tanishqapi1.herokuapp.com/jewellery (live link) 
(Get) http://localhost:11001/jwellery
(localhost link)
  
 //To get jewllery on basis  price filter(decreasing)
  (Get) https://tanishqapi1.herokuapp.com/category_and_filter/?lcost=20000&hcost=50000 (live link)
   (Get)http://localhost:11001/category_and_filter/?lcost=20000&hcost=50000 (localhost link) 
  //
  //To get jewellery on basis of jwellerytype
   (Get) https://tanishqapi1.herokuapp.com/jewellery/2 or https://tanishqapi1.herokuapp.com/jewellery_type/?jewel_type=Ring (live link) 
     (Get) http://localhost:11001/jewellery/2  or http://localhost:11001/jewellery_type/?jewel_type=Ring (localhost link) 
 

//page 2 : listing page //To get jewllery details

(Get)https://tanishqapi1.herokuapp.com/details/23 (live link)
 (get) http://localhost:11001/details/34(localhost link)

 
  

//page 3 : orderplaced page //To get orderplaced data


 //To place order 
 (Post) https://tanishqapi1.herokuapp.com/placeorder   (live link)
  (Post) http://localhost:11001/placeorder (localhost link) 
  //to cancel orders 
  (Delete)  (live link) 
  (Delete) http://localhost:11001/deleteOrder/62bb3c841c80f91631b4c0e8 (localhost link)


> List of order placed 
(Get)https://tanishqapi1.herokuapp.com/order (live link)
>>(Get) http://localhost:11001/order (localhost link)
> List of order placed of particular user
>>(Get)https://tanishqapi1.herokuapp.com/order/?email=Rohan@gmail.com(live link)
 (Get) http://localhost:11001/order/?email=Rohan@gmail.com(localhost link)
