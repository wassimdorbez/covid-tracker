
# **Corona website**


![https://i.ytimg.com/vi/Nv33sHscfLk/maxresdefault.jpg](https://i.ytimg.com/vi/Nv33sHscfLk/maxresdefault.jpg "click to link")
---
## Date: 18/05/2022 - 31/05/2022
---
<br>
<br>
<br>

|  Name |  Email GitHub|
|-----|-----|
| wassim dorbez | wassimdorbez@outlook.com |

#### Tools:
* Node  /express/
* JWT 
* google cloud 

```diff
@@ TERM OF REFERNCES: @@
# have functions and tools to build response full stuck website...
```
<br>
<br>

---
# **Frontend:**

>React

```javascript
import react from "react" 
```

<br>

### __installed :__ 

+ ## [chartjs](https://www.chartjs.org/ "click to link")
    + npm install chart.js-2
    +  _exemple statistic:_
      DEATH RECOVERED NEW CASES ...
      <br>

    + simulate multiple curves at same time (red,blue,green)



+ ## [Material Ui](https://mui.com/ "click to link")
    * npm install @mui/material @emotion/react @emotion/styled
    *  _exemple collect components and elements:_
    CARDS / CARDS CONTENTS / GRID

    <br>
+ ## CountUp:
     animation for counting the numbers of cases ...
    https://inorganik.github.io/countUp.js/
<br>
<br>
<br>
---
# **Backend:**

>Bcrypte

```javascript
const bcrypt = require('bcrypt');
const saltRounds = 10;
const Password = 's0/\/\P4$$w0rD';
```

### __functions used:__
1. **hash**: sytem to convert
```javascript
bcrypt.hash(Password, saltRounds, function(err, hash) {
    // salt or pepper
});
```
2. to hash it
```````js
const salt = bcrypt.genSaltSync(saltRounds);
const hash = bcrypt.hashSync(password, salt);
````````
3. ###  add salt:

___gensalt___ : generate random text for hash its addition password added at end of each password to makes more secure password against the hacking.

<br>

```diff

! rounds=8 : ~40 hashes/sec

! rounds=9 : ~20 hashes/sec

! rounds=10: ~10 hashes/sec

! rounds=11: ~5  hashes/sec

! rounds=12: 2-3 hashes/sec

! rounds=13: ~1 sec/hash

```

<br>

```diff
! Token
# give delay to the sign in user and then sign him out
```
<br>

![https://miro.medium.com/max/900/1*b0TtGI6gWFLltL1QkRxVdg.png](https://miro.medium.com/max/900/1*b0TtGI6gWFLltL1QkRxVdg.png "title")



>Mongoose


***_SET UP MONGOOSE CONNECTION_***


```````javascript
const mongoose = require('mongoose');
mongoose.connect('mongodb://localhost:27017/test');

//use unified topology :30 seconds 'beats' = Fail
//use new url to avoid parser error
````````
<br>

---
|FX|RULES|
|---|---|
|isActive|its running "isRunning" till stop else if not start|
|multer.disk storage|full cotrol of storing files|
|callBack|exemple complete time stamp so stop till task end|
|DB URL|DB database process.env URL environement path valid|
|Url Parser|BackUP|
|findbyidandupdate|to find document and update the arg|
|find one|to find document critere|
|pretty|display cursor clearly|
|populate|data inside references|
|await|to return promise|
|bcrypt|build password|
|next|return object with two proprietes done and value|
|cookies|app between server and client|

---
***
---


    
- [x] MongoDB
- [x] React
- [ ] Bcrypt
    - [ ] JWT
    - [ ] Notifications
    - [ ] authentification
- [ ] Google Cloud
    - [ ] Google Map
    - [ ] Firebase

---
***
---

<br>


## **SERVERS**:

```diff
+ server say work perfect:
```

100-information

101-switching protocol

200-success

201-created
<div style="color:yellow"> 204-no content </div>
<br>

300-redirected

301-moved permentley

302-found

304-not modify

<br>

```diff
- server say you have problem:
```

400-errors

400-bad request

403-forbidden

415-unsupported media type

500-server error

502-bad gateway

504-gateaway timeout

---

