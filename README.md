# KG technical test

## What to deliver

A link to your github (or any similar hub) repo, with a clear Readme file (how to install and run the project).

## What you will be judged on

- Clean code
- Commits logic
- Using React, Node, and Mongodb
- The project architecture
- Sticking to object structures mentionned in the Readme (or justify why you add extra fields)
- UX
- Your understanding of the tasks

## What you will **Not** be judged on

- Fancy styles (it's a nice to have though)

## What to justify

- Using external libraries

## Context

A real estate agency wants to develop a back-office application to view and manage its advertisements, the goal is to be able to view, update, and delete ads.

*Each ad represents a property, so these two terms are interchangeable.*

---

Here's a simplified property object example:

```
{ 
    "id" : 123423423,
    "createdAt" : 2021-01-27T09:48:37.223+0000Z,
    "landlord" : "Thomas Durant",
    "updatedAt" : 2022-02-25T15:30:59.346+0000Z, 
    "floor" : 2,
    "surface" : 70,
    "description" : "Near the market place", 
    "title" : "Superb property",
    "address" : {
        "street" : "120 Rue Alonzo", 
        "city" : "Berlin", 
        "zip" : "34090",
        "country" : "France", 
    },
    "rentPerMonth" : 3000,
    "nbRooms": 2,
}
```
---

## First task

Use React, Node, and Mongodb to achieve the demand of the agency. Extra points if you use Graphql.

- The user should be able to use the interface to add, delete, and update ads informations.

- *Extra: The user is able to select an ad from the list and view its content on a seperate page.*

---

## Second task

Congrats !! The agency has started to use your program, but an important information is missing, and it's whether the property is reserved by someone or not.

Let's add these two fields to the property object (as an example):

```
    "isReserved": true,
    "reservedBy": "Toto Leblanc",
```

- Add the mechanism that allows the agency to manage reservations.

## Third task

- Add a clients table, and link a client id to the `reservedBy` field in property, so when we click on the `reservedBy`field we have access to client info.

Here's a simplified client object example:

```
{ 
    "id" : 23432,
    "firstName": "Toto",
    "lastName": "Leblanc",
    "email": "Toto@leblanc.co",
    "phone": 0612345678
}
```

- **Bonus:** The user can delete, update, or add a client using the interface.

## Author

Majd Bayassi, if you have any question: majd@koliving.fr
