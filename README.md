# 👩‍💻 KG Technical Test

Heya! Welcome to the tech test, don't panic and try to enjoy it.
Consider it an opportunity to do things your own way. 

![qs](https://media1.giphy.com/media/8xgqLTTgWqHWU/giphy.gif)

## 📦 What to deliver

A link to your github (or any similar hub) repo, with a clear README.md file on how to install and run the project, feel free to also explain some technical choices you made.

## 🔧 The tools you will be using
- React Native
- TypeScript
- GraphQL
- MongoDB
- Docker
- Any other tool or superset of these tools you think would help you have a cleaner code/architecture

## 🎯 What you will be judged on

- The project architecture
- Clean code
- Your understanding of the tasks
- Your ingenuity and out-of-the-box thinking
- Commits logic

## ❌ What you will **NOT** be judged on

- User interface & styles (*note that the way you **technicaly** apply styling could be judged, but the way it actually looks will not*)

## 🤔 What to justify

- Using external libraries

## 💭 Context

A real estate agency wants to develop a back-office application to view and manage its properties, the goal is to be able to view, update, and delete ads.

**An ad is anything that is (or can be) rented out. (A flatsharing room, an entire castle, <del>your backyard</del>)** (<=> rental unit)

A property has **at least** the following fields:
- Title
- Address
- Rooms
- Surface
- Pictures

A Room has **at least** the following fields:
- Title
- Surface
- Pictures

Something that is rented out (rental unit) has **at least** the following fields:
- Tenant
- Rent Price

A tenant has **at least** the following fields:
- First Name
- Last Name
- Email

## 1️⃣ First task

- Add an Ads page, where the user should be able to use the interface to add, delete, and update ads.

- *Extra: The user is able to select an ad from the list and view its content on a seperate page.*

## 2️⃣ Second task

Congrats !! The agency has started to use your program, but an important information is missing, and it's whether the ad is rented by someone or not.

- Create a Tenants page, where the tenants are listed with information about the ad they are renting out (no need to make them editable)
- Add the feature to view and update who is renting out an ad on the Ads page

## 3️⃣ Third task

- On the Ads page add a filtering feature which allows to filter ads based on:
  - Title
  - Date Created
  - Email of the tenant renting
- Add a sorting feature which allows to sort ads based on:
  - Rent Price
  - Date Created

How are you doing with 10k+ properties in your database?

## ✏ Author

Alexandre Daubricourt <alexandre.daubricourt@koliving.fr>
