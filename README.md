# Easy-Generator-Full-Stack-Task

Getting Started:
    Frontend:
        git clone https://github.com/HossamElAnsary/Easy-Generator-Full-Stack-Task-Frontend.git
        cd Easy-Generator-Full-Stack-Task-Frontend
        
        Running the frontend:
            docker-compose up --build or npm run dev
            App will start running on http://localhost:3000/

        TODO:
            Create Reusable Components (e.g. Input, Button, FormField, etc..)
            use Single API handler and use it with React-Query.
            Performance Optimization: Lazy Loading, Code Spliting, Local State vs Global State.

    backend:
        git clone https://github.com/HossamElAnsary/Easy-Generator-Full-Stack-Task-Backend.git
        cd Easy-Generator-Full-Stack-Task-Backend

        Running the backend:
            docker-compose up --build
            App will start running on http://localhost:5001/api/v1
            MongoDB: http://localhost:27017/
            Mongo-Express: http://localhost:8081/
            API Documentation using Swagger: http://localhost:5001/api/v1/docs
        
        TODO:
            use refreshToken.
            Implement Repository Pattern as your Data-Access-Layer.
            Implement Unit-Testing.
            Use Reverse Proxy or handle Direct HTTPS Server

Pointing to latest commit:
    frontend:
        git submodule update --remote frontend
        git add frontend
        git commit -m "Bump frontend submodule to latest"
        git push
    backend:
        git submodule update --remote backend
        git add backend
        git commit -m "Bump backend submodule to latest"
        git push
