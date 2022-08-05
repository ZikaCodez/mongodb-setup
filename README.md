## How to setup MongoDB <img src="https://github.com/mongodb-js/leaf/blob/master/mongodb-leaf.svg" height="20" width="20">
- Head to [MongoDB.com](https://cloud.mongodb.com/v2#/preferences/organizations)
### Start by creating an organization
- Create a new organization

![](https://capy-cdn.xyz/KbvyC0q5B0On.png)

- Give it a cool name

![](https://capy-cdn.xyz/T1ohKBQA8HhJ.png)

- Choose `MongoDB Atlas`

![](https://capy-cdn.xyz/pWcsnR2HYAEH.png)

- Then, hit `Next` and `Create Organization`!

Now you've made a MongoDB organization, what's next?

### Create a project
- Click on `New Project`

![](https://capy-cdn.xyz/ePfajTWumRPy.png)

- Name it, then hit `Next`!

![](https://capy-cdn.xyz/XcVlHlun1hZ9.png)

- Click `Create Project`

![](https://capy-cdn.xyz/MCnlBZsYK9BE.png)

### Setup your database
- Now, build a new database!

![](https://capy-cdn.xyz/EZsjzJ4tm6E8.png)

- Pick the free option on the right
- Choose these options:

![](https://capy-cdn.xyz/sxRoWWfwppvO.png)

![](https://capy-cdn.xyz/67bUQKcxYh9c.png)

- Create your new cluster!

![](https://capy-cdn.xyz/HuLpAk3NjDgJ.png)

- After creating your cluster, you'll find yourself on this page. Enter a username and a secure password that will be used for authorization in the bot's code, then hit `create user`.

![](https://capy-cdn.xyz/YjKnIcPIszja.png)

- Your cluster will take a few moments to create, wait until these buttons turn white.

![](https://capy-cdn.xyz/pHhehjxc2b1N.png)

- After they turned white, click on `connect`, and perform these steps:

![](https://capy-cdn.xyz/UmCtH39AJ0mz.png)

![](https://capy-cdn.xyz/dEirY25B4UYD.png)

![](https://capy-cdn.xyz/gX7kZZ3bfoEP.png)

![](https://capy-cdn.xyz/4AFBD5eqijqo.png)

![](https://capy-cdn.xyz/81GPo5Rgsm23.png)

![](https://capy-cdn.xyz/aIbvjbCZGXTF.png)

![](https://capy-cdn.xyz/siIgU0Bz9hb7.png)

![](https://capy-cdn.xyz/IemvMHZsJFho.png)

![](https://capy-cdn.xyz/s2UpEBUvuMsv.png)

![](https://capy-cdn.xyz/rMJJoHuMqdGA.png)

***Names can be changed to your liking.***

![](https://capy-cdn.xyz/5f1zRwcJR6ed.png)

![](https://capy-cdn.xyz/Dagdlg3pfyQ4.png)

### After successfully setting up MongoDB, go ahead and use it in your code!

```py
import pymongo
from pymongo import MongoClient

client = MongoClient("the connection string you copied (MAKE SURE YOU CHANGE <PASSWORD> WITH YOUR USER'S PASSWORD!)")

db = client["MainDB"]
threads = db["threads"]
closed_threads = db["closed_threads"]
```
