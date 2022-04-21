//page1

 Course categories= https://edutech-app1.herokuapp.com/category
  localhost:9500/category 

  Course level = https://edutech-app1.herokuapp.com/level
   localhost:9500/level

//page2 

level based categoryid= https://edutech-app1.herokuapp.com/level?categoryid=1
localhost:9500/level?categoryid=1



details of level based on  category id = https://edutech-app1.herokuapp.com/details?categoryid=2
 localhost:9500/details?categoryid=1

on levelid => // https://edutech-app1.herokuapp.com/details?levelid=1
 localhost:9500/details?levelid=1



//page3 BookCourse
 (post)=  localhost:9500/BookCourse (body) > {
  
{  "_id": {    "$oid": "625f8b000e3c32cdcf8ffec7"  },  "name": "cat",  "email": "cat123@",  "address": "c1 sector",  "phone": 78578644,  "cost": 2499,  "status": "pending",  "bank_name": ""}
}

//page4 See all order place=
 Get Order on basis of emailId : https://edutech-app1.herokuapp.com/viewCourse?email=cat123@

localhost:9500/viewCourse?email=cat123@

//page5 update order (put)=
 https://edutech-app1.herokuapp.com/updateOrder/625f8b000e3c32cdcf8ffec7
  (body) { "status":"In Transit", "bankName":"" }

localhost:9500/updateCourse/625f8b000e3c32cdcf8ffec7 (body) { "status":"In Transit", "bankName":"" }