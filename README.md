# dev.transactions Rest-Api

## Functional Requirements

- The user must be able to create a new transaction => **POST /transactions**
- The user must be able to obtain a summary of their account =>  **GET /transactions/summary**
- The user must be able to list all transactins that have already taken place =>  **GET /transactions**
- The user must be able to view a single transaction => **GET /transactions/:id**

## Business Rules

- The transaction can be of the credit type, which will add to the total amount, or of the debit type, which will subtract from the total amount

- Must be able for us identify the user between transactions

- The user can only view transactions he created

## To run

``` 
npm install
npm run dev
```
