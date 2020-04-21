# Hounders

Our mission is to enable dog seekers to find their ideal pet. You can use our site to list a dog of your own, or as a buyer you can browse all of the dogs that have currently been listed. We also show you the 20 latest dogs to hit the PetFinder site for adoption. If you have any questions or concerns, please feel free to contact us. We hope you find your next best friend here, and thanks for choosing Hounders!

Deployed website url: https://doghounders.herokuapp.com

---

### **NPM Dependencies**

* @petfinder/petfinder-js
* dotenv
* express
* express-handlebars
* mysql
* mysql2
* sequelize

### **API Used**

* PetFinder

---

### **Initial Setup**
If you want to set this app up locally, navigate to the folder in your terminal, and install all the necessary dependencies with:

```
npm i
```

Next, go to the developer page of the PetFinder website, create an account, which will generate your API keys.

https://www.petfinder.com/developers/

Then, create a file named `.env`, add the following to it, replacing the values with your API keys (no quotes):

```js
apiKey=your-petfinder-api-key
secret=your-petfinder-secret

```

Next, navigate to the models folder, and run the schema file in your MySQL Workbench, or your preferred GUI client.

Finally, in the config.json file, change the development username and password to your login information.

---

### **How To Utilize Hounders**

Run the following code in your terminal:

```
node server
```

This will initiate a website running on http://localhost:3000/