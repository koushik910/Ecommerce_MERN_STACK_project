project 
    backend:
        open cmd
            ->npm init
            ->npm i express mongoose cors nodemon dotenv
            ->npm i bcryptjs jsonwebtoken
        open package.json file
            in scripts add this line ---  "start":"nodemon index.js"
        
        create files in backend
            config
                db.js
                jwt.js
            middleware
                authmiddleware.js
            models
                user.js
            routes
                auth.js
            index.js
            