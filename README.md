A Fake json-server DB that powers the JugsApp prototype - a sport analytics and tracking app for 
touch and tag rugby tournaments.

# Development Instruction

To run this app locally on a macbook / laptop do the followings.

Clone this repository to an appropriate location on your machine:

```
git clone https://github.com/Atlas7/jugs-db
```

Install NPM dependencies:

```
npm install
```

Navigate to the project:

```
cd jugs-db
```

Start `json-server` where a fake API is served. Essentially an entire toy database (that I created) in one `db.json`.

```
npm run start-api
```

This will start a fake API at [http://localhost:3000](http://localhost:3000).