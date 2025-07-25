<<<<<<< HEAD

# Calorie Counter App

In this Website uses can scan the qr code and can get the data of that food item and the total calorie of that Food Item.Users can also add the food items in it and can also update and Delete the existing food items.
## Tech Stack

**Client:** React, TailwindCSS

**Server:** Node, Express

**Database:** Mongodb
## Images

### Home Page
  ![Home Page](./assets/home.png)

  ### Sign Up Page
  ![Sign Up Page](./assets/signup.png)

  ### Add Dish Page
  ![Add Dish Page](./assets/additem.png)

  ### Dish List Page
  ![Dish List Page](./assets/items.png)
    
## Key Features  
1. **User Authentication**:  

    - **Login**: Secure login with validation; incorrect email or password prevents access.

   

2. **Profile Management**:  
   - View personal details.  
   - Log out option for enhanced security.  
   

3. **Dish Management**:  
   - Add new dishes with calorie data (stored in the backend).  
   - Edit or delete existing dishes.  
   - Backend deployed on **Render.com**, ensuring seamless API integration.  

4. **QR Code Integration**:  
   - Each dish generates a QR code.  
   - Scanning the QR displays full dish details, including calories and nutritional content.  


5. **Intuitive Navigation**:  
   - Clean navbar with logo (left), profile (right), and "Add Dish" option in the center.  

---

## Demo  
1. **Sign Up and Login**: Prevents unauthorized access.  
2. **Add Dish**: Stores dish data in the backend, displays it dynamically in the frontend.  
3. **Edit/Delete**: Modify or remove dishes effortlessly.  
4. **QR Code**: Scan to view detailed nutritional data.  

## Group Discussion 

https://drive.google.com/file/d/13zwaNZoTDIPRrzE6fBPDrnKWlpuk-2H7/view?usp=sharing

## Installation

Install 4376-Dish-calorie-scanner with npm

```bash
  npm install 4376-Dish-calorie-scanner
  cd 4376-Dish-calorie-scanner
```

## API Reference

#### Get all items

```http
  GET /api/dishes
```


#### Get item by id

```http
  GET /api/dishes/${id}
```
#### create item

```http
  POST /api/dishes/${id}
```
#### update item

```http
  PUT /api/dishes/${id}
```



## Deployment Link

https://four376-dish-calorie-scanner-frontend.onrender.com/


## Run Locally

Clone the project

```bash
  git clone https://github.com/nileshyadav6702/4376-Dish-calorie-scanner.git
```

Go to the project directory

```bash
  cd 4376-Dish-calorie-scanner
Public

```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```

=======
# food-calaries-backend
>>>>>>> 4539679c83cde9e6cc7b7063aa533365b2af3e5b
