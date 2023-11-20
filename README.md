DESCRIPTION:

    An grocery delivery website built with  stack, and utilizes third party API's. This ecommerce store enable three main different flows or implementations:

      1)Buyers browse the store categories, products and brands
      2)Sellers or Merchants manage their own brand component
      3)Admins manage and control the entire store components
      
FEATURES:

    Node provides the backend environment for this application
    Express middleware is used to handle requests, routes
    Mongoose schemas to model the application data
    React for displaying UI components
    Redux to manage application's state
    Redux Thunk middleware to handle asynchronous redux actions
    
DATABASE SEED:

     The seed command will create an admin user in the database
     The email and password are passed with the command as arguments
     Like below command, replace brackets with email and password.
     For more information, see code here
     npm run seed:db [email-***@****.com] [password-******] // This is just an example.
     
DEMO:

      This application is deployed on Vercel Please check it out:"(https://mern-store-gold.vercel.app)".

     See admin dashboard demo: "(https://mernstore-bucket.s3.us-east-2.amazonaws.com/admin.mp4)"
