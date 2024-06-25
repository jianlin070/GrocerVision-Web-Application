# GrocerVision Web Admin Panel

## Summary

The **GrocerVision Web Admin Panel** is designed to provide administrators with powerful tools to manage the grocery store efficiently. Key features include:

- **Product Management:** Add, edit, and delete products
- **Order Management:** View all orders placed by customers
- **Dashboard:** Get an overview of the latest products and orders

The admin panel ensures that managing an online grocery store is streamlined and intuitive.

## IDE

**Name and version of the IDE:**  
Android Studio Giraffe | 2022.3.1 Patch 3

## APIs and Third-Party Libraries

1. **Firebase**

   - **Authentication:** For admin login
   - **Firestore:** For managing product and order data
   - **Storage:** For storing product images

2. **Provider**

   - For state management in Flutter applications

3. **Flutter Icons (Iconly)**

   - For using a variety of icons throughout the application

4. **Fluttertoast**
   - For displaying toast messages

## Additional Steps to Run the Program

1. **Clone the Repository**

   ```sh
   git clone <repository_url>
   ```

2. **Set Up Firebase**

- Create a Firebase Project:

  1. Go to the Firebase Console
  2. Click on "Add project" and follow the setup instructions

- Register Your App with Firebase:

  1. In the Firebase Console, click on "Add app" and select the Android icon
  2. Follow the steps to register your app with Firebase
  3. Copy the Firebase configuration and add it to your web app

- Register Your App with Firebase:

1.  Open the index.html file in the web directory and add the following Firebase SDK scripts inside the <head> tag:

```sh
    <!-- Firebase App (the core Firebase SDK) -->
    <script src="https://www.gstatic.com/firebasejs/8.6.8/firebase-app.js"></script>
    <!-- Add Firebase products that you want to use -->
    <script src="https://www.gstatic.com/firebasejs/8.6.8/firebase-auth.js"></script>
    <script src="https://www.gstatic.com/firebasejs/8.6.8/firebase-firestore.js"></script>
    <script src="https://www.gstatic.com/firebasejs/8.6.8/firebase-storage.js"></script>
```

3. **Install Dependencies**
 ```sh
 flutter pub get
 ```

 4. **Run the Web Admin Panel**
 - Ensure you have Flutter installed for web development
 - Run the admin web panel by navigating to the project directory and running:
 ```sh
 flutter run -d chrome --web-renderer html
 ```


