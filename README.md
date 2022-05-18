# **Corona website**
![https://i.ytimg.com/vi/Nv33sHscfLk/maxresdefault.jpg](https://i.ytimg.com/vi/Nv33sHscfLk/maxresdefault.jpg "title")
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
* Node 
* JWT 
* google cloud 

##### this term of references:
###### have functions and tools to build these
<br>
<br>

>React

```javascript
import react from "react" 
```

<br>

### __installed :__ 

+ ## [chartjs](https://www.chartjs.org/ "click to link")
    + curve
    + ## statistic:
      DEATH RECOVERED NEW CASES ...
      <br>

    + simulate multiple curves at same time (red,blue,green)



+ ## [Material Ui](https://mui.com/ "click to link")
    * new update 2022 
    * ### collect components and elements:
    CARDS / CARDS CONTENTS / GRID
    <br>
+ ## CountUp:
     animation for counting the numbers of cases ...
    https://inorganik.github.io/countUp.js/
<br>
<br>
<br>

>Bcrypte

```javascript
const bcrypt = require('bcrypt');
const saltRounds = 10;
const Password = 's0/\/\P4$$w0rD';
```

### __functions used:__
1. hash
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

___salt___ : generate random addition password at end of each password to more secure because of hacking.
<br>
<br>
-
<p> 
rounds=8 : ~40 hashes/sec
rounds=9 : ~20 hashes/sec
rounds=10: ~10 hashes/sec
rounds=11: ~5  hashes/sec
rounds=12: 2-3 hashes/sec
rounds=13: ~1 sec/hash
......

</p> 

<br>

![https://miro.medium.com/max/900/1*b0TtGI6gWFLltL1QkRxVdg.png](https://miro.medium.com/max/900/1*b0TtGI6gWFLltL1QkRxVdg.png "title")


>Mongoose
```````javascript
const mongoose = require('mongoose');
mongoose.connect('mongodb://localhost:27017/test');
````````
<br>

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


