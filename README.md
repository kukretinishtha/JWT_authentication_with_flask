# JWT_authentication_with_flask
Project to implement JWT authentication on flask app.

****************************************************************
To run the project follow:
1. pip install requirements.txt
2. on python terminal run 
        from app import db
        db.create_all()
        ***** database.db will be created in your folder directory.

3. on another terminal run
        python3 app.py
4. To test your api on postman 
    hit http://127.0.0.1:5000/signup   // for signing up
    hit http://127.0.0.1:5000/login   // for login

5. Export the postman collection. I have attached it with modifications. 
        Find the attached collection flaskAuthentication.json