project
    backend
        config
            jwt.js -- generateToken, validateToken
            db.js -- mongoose connection
        routes
            auth.js -- users
            adminAuth.js -- adminAuth
            projects.js -- add,delete,get
        controllers 
            auth, adminauth, product routes logic rasthamu
        models
            user schema(name, email, password, mobile, role(user,admin)-->user)
            product schema (productname, productprice, productdescription, productimage)
        middleware
            token authenticate
            admin/user authenticate
        index.js
            all the above mentioned files will be connected, urlencoded
    client
        App.jsx -- routes
        Home
        Login
        Register
        Navigation
        Cart
        Payment
        Orders

