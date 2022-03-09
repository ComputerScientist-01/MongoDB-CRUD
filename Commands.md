## Exercise 1

### Data to be inserted
```bash
doc1=[{srn:150,sname:"Vedant",degree:"BCA",sem:6,CGPA:7.1},
{srn:151,sname:"Sujay",degree:"BCA",sem:6,CGPA:7.2},
{srn:164,sname:"Sandipan",degree:"BCA",sem:6,CGPA:7.3},
{srn:170,sname:"Swarnabha",degree:"BCA",sem:6,CGPA:7.4},
{srn:186,sname:"Jay",degree:"BCA",sem:6,CGPA:7.5},
{srn:203,sname:"Bedansh",degree:"BCA",sem:6,CGPA:7.6},
{srn:069,sname:"Tanisha",degree:"BCA",sem:6,CGPA:7.7},
{srn:420,sname:"Sudipta",degree:"BCA",sem:6,CGPA:7.8}]
```
## To insert
```
db.studcol1.insert(doc1)
```
## To Delete
```
db.studcol1.deleteOne( { "_id" : ObjectId("563237a41a4d68582c2509da") } );
```
## Exercise 2

### Data to be inserted
```bash
db.studcol1.insert([{eid:001, ename:"Rahul", dept:"prod", desig:"dev", salary:30000, yoj:2015, address:{dno:397, street:2, locality:"rmnagar", city:"bangalore"}},
{eid:002, ename:"Priya", dept:"test", desig:"tester", salary:20000, yoj:2016, address:{dno:323, street:1, locality:"manar", city:"chennai"}},
{eid:003, ename:"Mandeep", dept:"prod", desig:"dev", salary:30000, yoj:2017, address:{dno:317, street:3, locality:"manar", city:"bangalore"}},
{eid:004, ename:"Snehil", dept:"prod", desig:"dev", salary:30000, yoj:2016, address:{dno:127, street:3, locality:"rmnagar", city:"chennai"}},
{eid:005, ename:"Rupa", dept:"test", desig:"tester", salary:20000, yoj:2015, address:{dno:123, street:2, locality:"mahi", city:"bangalore"}},
{eid:006, ename:"Sujay", dept:"customer", desig:"pr", salary:15000, yoj:2013, address:{dno:327, street:2, locality:"kunnor", city:"pune"}},
{eid:007, ename:"Swarnabha", dept:"test", desig:"tester", salary:20000, yoj:2015, address:{dno:343, street:2, locality:"park", city:"bangalore"}},
{eid:008, ename:"Sandip", dept:"customer", desig:"pr", salary:15000, yoj:2016, address:{dno:367, street:3, locality:"potheri", city:"siliguri"}},
{eid:009, ename:"Soumya", dept:"prod", desig:"prod", salary:30000, yoj:2014, address:{dno:497, street:2, locality:"basti", city:"bangalore"}},
{eid:010, ename:"Jai", dept:"test", desig:"test", salary:20000, yoj:2018, address:{dno:337, street:1, locality:"rmnagar", city:"kashmir"}}])
```

## Exercise 3

### Data to be inserted
```bash
db.book.insert([{isbn:"e1", bname:"let us C", author:["yeshanth", "kanaka"], year:2012, publisher:"pearson", price:100},
{isbn:"e2", bname:"Object Oriented Programming", author:["manik", "chanda"], year:2013, publisher:"penguin", price:200},
{isbn:"e3", bname:"AI Simplified", author:["hugh", "lowry"], year:2013, publisher:"penguin", price:400},
{isbn:"e4", bname:"Formal Automata", author:["khemant", "bisht"], year:2014, publisher:"rachana", price:300},
{isbn:"e5", bname:"let us C++", author:["sandy", "pandas"], year:2012, publisher:"pearson", price:200}])
```

## Exercise 4

### Data to be inserted
```bash
db.food.insert([{foodid:1, foodcat:"fastfood", foodname:"burger", chefname:["naveen","reddy"], price:500,ingredients:["cheese","corn"], hotelname:"mcburger", address:{no:31, street:"belroad", locality:"yehelanka", city:"bangalore"}},
{foodid:2, foodcat:"fastfood", foodname:"chicken", chefname:["sujay","pandas"], price:300,ingredients:["soya","corn"], hotelname:"mcchicken", address:{no:32, street:"gaoroad", locality:"tanbaram", city:"chennai"}},
{foodid:3, foodcat:"fastfood", foodname:"pizza", chefname:["jai","rathi"], price:400,ingredients:["cheese","corn"], hotelname:"mcpizza", address:{no:33, street:"macroad", locality:"ktr", city:"madurai"}},
{foodid:4, foodcat:"fastfood", foodname:"paneer", chefname:["swarma","goswami"], price:350,ingredients:["cheese","spices"], hotelname:"mcpaneer", address:{no:34, street:"gandhiroad", locality:"potheri", city:"dehradun"}},
{foodid:5, foodcat:"fastfood", foodname:"dosa", chefname:["bedansh","nitin"], price:150,ingredients:["appam","chini"], hotelname:"mcdosa", address:{no:35, street:"munnaroad", locality:"saltlake", city:"siliguri"}}])
```
