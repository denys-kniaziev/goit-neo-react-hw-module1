# Woolf University. React Course. Homework – Components and Styling

## Overview

This assignment focuses on creating reusable React components, passing data via props, and organizing static data in JSON files.

---

## Task 1 – Profile Component

Create a `<Profile>` component that displays a social network user’s information.

**Props:**

* `name` – user’s name
* `tag` – username without `@`
* `location` – city and country
* `image` – avatar URL
* `stats` – object containing user activity (`followers`, `views`, `likes`)

Move user data into `userData.json` and import it into `App.jsx` to pass as props.

---

## Task 2 – Friend List

Create a `<FriendList>` component that renders a list of friends using data from `friends.json`.

**Components:**

* `<FriendList>` – receives `friends` (array of objects)
* `<FriendListItem>` – renders one friend’s card

**Props for `<FriendListItem>`:**

* `avatar` – image URL
* `name` – friend’s name
* `isOnline` – boolean indicating status

Use conditional styling:

* `Online` – green text
* `Offline` – red text

---

## Task 3 – Transaction History

Create a `<TransactionHistory>` component that displays a table of transactions from `transactions.json`.

**Props:**

* `items` – array of transaction objects with:

  * `id`
  * `type`
  * `amount`
  * `currency`
