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
