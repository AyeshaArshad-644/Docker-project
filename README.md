**Recipe Finder App**

This project is a microservices-based web application with three main services: a backend, a MongoDB database, and a frontend. The application is containerized and managed using Docker Compose.

**Services**

1. **Backend**: A Flask application that provides APIs for recipe management.
2. **Database**: A MongoDB instance to store recipe data.
3. **Frontend**: A React/Angular-based user interface for interacting with the application.

## software used

- Docker
- Docker Compose

## Setup and Deployment

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Folder Structure**:
   ```
   project-root/
   ├── backend/
   │   ├── app.py
   │   ├── requirements.txt
   │   ├── Dockerfile
   │   └── ...
   ├── frontend/
   │   ├── Dockerfile
   │   ├── package.json
   │   ├── src/
   │   └── ...
   ├── docker-compose.yml
   ```

3. **Build and Start Services**:
   ```bash
   docker-compose up --build
   ```

4. **Access the Application**:
   - Frontend: `http://localhost:3000`
   - Backend: `http://localhost:5000`
   - MongoDB: `localhost:27017`

## API Endpoints

- **`GET /recipes`**: Fetch all recipes.
- **`POST /recipes`**: Add a new recipe.
- **`GET /external`**: Example external API call.



## Frontend Placeholder

The frontend currently displays a basic interface. Replace it with your desired React/Angular app by modifying the `frontend/` folder.

## Customization

- Update the MongoDB URI or other environment variables in the `docker-compose.yml` file.
- Extend the backend APIs in the `app.py` file.
- Customize the frontend as needed.


