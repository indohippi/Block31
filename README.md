# Workshop: Backend Fundamentals - Pet Finder

## Introduction

In this workshop, you'll be provided this GitHub repo with details for a full operational CRUD API that uses Express.JS, PostgreSQL, and other technologies that you've been trained on.

## Problems to Solve

Begin this Career Simulation by cloning the GitHub repo, pseudocoding prompts, installing dependencies and solving the problems below.

### Problem 1: GET all pets

The GET route for all pets is currently "under construction". Navigate to `index.js` and find the GET method at `/api/v1/pets` and write the code to get all pets from the database.

### Problem 2: GET pets by name

The GET route for pets by name is currently "under construction". Navigate to `index.js` and find the GET method at `/api/v1/pets/:name` and write the code to get a pet by name from the database.

### Problem 3: GET pet by owner's name with a query string

The GET route for pets by owner's name is currently "under construction". Navigate to `index.js` and find the GET method at `/api/v1/pets/owner` and write the code to get a pet by owner's name from the database.

### STRETCH GOAL: Problem 4: Serve a static index.html file

The GET route for serving a static index.html file is currently "under construction". Navigate to `index.js` and find the GET method at `/` and write the code to serve a static index.html file.

### Endpoints

Port 8080 by default.

| Method | Endpoint           | Description                    |
| ------ | ------------------ | ------------------------------ |
| GET    | /                  | Serve a static index.html file |
| GET    | /api               | Returns 'Hello World!'         |
| GET    | /api/v1/pets       | Get all pets                   |
| GET    | /api/v1/pets/:name | Get a pet by name              |
| GET    | /api/v1/pets/owner | Get a pet by owner's name      |

```
Unit4.PetFinder.Starter
├─ .git
│  ├─ HEAD
│  ├─ config
│  ├─ description
│  ├─ hooks
│  │  ├─ applypatch-msg.sample
│  │  ├─ commit-msg.sample
│  │  ├─ fsmonitor-watchman.sample
│  │  ├─ post-update.sample
│  │  ├─ pre-applypatch.sample
│  │  ├─ pre-commit.sample
│  │  ├─ pre-merge-commit.sample
│  │  ├─ pre-push.sample
│  │  ├─ pre-rebase.sample
│  │  ├─ pre-receive.sample
│  │  ├─ prepare-commit-msg.sample
│  │  ├─ push-to-checkout.sample
│  │  └─ update.sample
│  ├─ index
│  ├─ info
│  │  └─ exclude
│  ├─ logs
│  │  ├─ HEAD
│  │  └─ refs
│  │     ├─ heads
│  │     │  └─ main
│  │     └─ remotes
│  │        └─ origin
│  │           └─ HEAD
│  ├─ objects
│  │  ├─ info
│  │  └─ pack
│  │     ├─ pack-97949ed22df367abbfe36ebd0b85457931eaeb98.idx
│  │     └─ pack-97949ed22df367abbfe36ebd0b85457931eaeb98.pack
│  ├─ packed-refs
│  └─ refs
│     ├─ heads
│     │  └─ main
│     ├─ remotes
│     │  └─ origin
│     │     └─ HEAD
│     └─ tags
├─ .gitignore
├─ README.md
├─ data.js
├─ index.js
├─ index.test.js
├─ package-lock.json
├─ package.json
└─ public
   ├─ index.html
   ├─ script.js
   └─ styles.css

```# Block31
