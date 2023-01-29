# book-record-management

This is an application called book record management/API

## Endpoints

## /users
POST: Create a new user
GET: Get all list of users

## /usres/{id}
GET: Get a user by their id
PUT: Update a user by id
DELETE: Delete a user bt their id (Check if the user still has an issued book && is there any fine to be collected from the user)

## /users/subscription-details/{id}
GET: Get user subscription details
1. Date of Subscription
2. Valid till ??
3. Fine if any ??

## /books
GET: Get all books
POST: Add a new book

## /books/{id}
GET: Get a book by id
PUT: Update a book by id

## /books/issued
GET: Get all issued books here

## /books/issued/withFine
GET: Get all issued books with fine

## Subscription Types
Basic (3 months)
Standard (6 months)
Premium (12 months)

If user has an issued book and the issued book is to be returned at 09-12-22
If user missed the date to return, then user gets a fine if Rs. 50/-

If user has an issued book and the issued book is to be returned at 09-12-22
If user missed the date to return, and the users subscription also got expired,then user need to pay a fine of 150/- (100+50)


