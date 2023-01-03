## About The Project

This application is an appointment record service system for veterinary clinics. Admin can manage all pets , user can see the visit history of his pets. 

## Getting Started

### Prerequisites

To run app locally:

* Database setup
  ```
  Set your default db user and db password in application.properties or environment variables.
  ```

* Default server port
    ```
  server.port = 8080
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/czarnycz/Clivet-back (Backend)
   git clone https://github.com/czarnycz/Clivet_React (Frontend)
   ```

2. Run backend server on port 8080. Navigate to frontend folder and start the server. Install missing dependencies.
```
npm start
npm i [missing-dependency-name]
```

## Usage

Users can:
* Login or register
* Check own profile info
* Check own pets info
* Check all appointments of specific pet

Administrator can:
* Edit user data
* Add pets
* Add appointments
* Edit pet data
* Delete pets
* Delete appointments

## Contact

Gluszko Bartlomiej email: gluszko.b@gmail.com
