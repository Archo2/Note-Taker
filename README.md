# Note Taker

A note-taking web app with an Express.js back end that lets you write, save and delete notes.

**Demo video:** https://watch.screencastify.com/v/xAqsj8HDT5aQJ3fwrIQe

## Features

- Write a note with a title and text
- Save notes and see them listed on the left
- Click a saved note to view it
- Delete notes you no longer need
- Notes are stored in `db/db.json`

## Built With

Node.js · Express.js · HTML · CSS · JavaScript

## API Routes

| Method | Route | Description |
|---|---|---|
| GET | `/notes` | Notes page |
| GET | `/api/notes` | Get all saved notes |
| POST | `/api/notes` | Save a new note |
| DELETE | `/api/notes/:id` | Delete a note by id |

## Getting Started

**Prerequisites:** Node.js

```bash
git clone https://github.com/Archo2/Note-Taker.git
cd Note-Taker
npm install
npm start
```

Then open http://localhost:3001.

## Author

**Archils Oburu**
- GitHub: [@Archo2](https://github.com/Archo2)
- Email: oburuarchils@gmail.com
