# SHOP HAIR PROJET: Website for hair sales.

## `BACKEND`
### In the project directory, run this command to initialize the project and install dependencies:
- `python3 -m venv shophair_env`
- `python3 -m pip install --upgrade pip`
- `pip install django rasa`
- `rasa init`

### Command to run the project:
- Rasa chatbot  `rasa run`  `rasa run actions`  `rasa run --enable-api`
- Backend:  `python manage.py runserver`

### Environment variables:
- Default port server: `(PORT = "XXXX")`
- Default url api: `(API_URL = "XXXX")`
- MongoDB: `(MONGO_IP = "XXXX"; MONGO_PORT = "XXXX"; MONGO_DATABASE = "XXXX")`
- Url RASA Chatbot: `(RASA_URL = "XXXX")`


## `FRONTEND`
### In the project directory, run this command to initialize the project and install dependencies:
- `npx create-react-app .`
- `npm redux react-redux redux-thunk bootstrap axios`

### Command to run the project:
- Frontend:  `npm start`
