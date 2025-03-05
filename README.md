# CompanyAPI

A REST API for managing company data with JWT authentication.

## Setup
1. Clone the repository.
2. Open the project in Visual Studio.
3. Restore NuGet packages.
4. Run the project.

## Testing
Use Postman to test the API. Include the JWT token in the `Authorization` header for secured endpoints.

## Endpoints
- **POST `/api/auth/login`**: Authenticate and get a JWT token.
- **POST `/api/companies`**: Add a new company.
- **GET `/api/companies`**: Get all companies.
- **GET `/api/companies/{companyCode}`**: Get a company by code.
- **PUT `/api/companies/{companyCode}`**: Update a company.
- **DELETE `/api/companies/{companyCode}`**: Delete a company.
