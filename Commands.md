## Data to be inserted
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
