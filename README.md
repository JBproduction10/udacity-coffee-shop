# Coffee Shop Full Stack

<h1 align:'center', font-size=500> Udacity Final Project</h1>
<p align:"center">Fullstack Coffee Shop</p>

## Full Stack Nano - IAM Final Project

<p>Udacity has decided to open a new digitally enabled cafe for students to order drinks, socialize, and study hard. But they need help setting up their menu experience.
</p>
<p> You have been called on to demonstrate your newly learned skills to create a full stack drink menu application. The application must:</p>
<ul>
<li>Display graphics representing the ratios of ingredients in each drink.</li>
<li> Allow public users to view drink names and graphics.</li>
<li>Allow the shop barista to see the recipe information</li>
<li> Allow the shop manager to create new drinks and edit existing drinks.</li>
</ul>

## Tasks

There are `@TODO` comments throughout the project. We recommend tackling the sections in order. Start by reading the READMEs in:

1. [`./backend/`](./backend/README.md)
2. [`./frontend/`](./frontend/README.md)

## About the Stack

We started the full stack application for you. It is designed with some key functional areas:

### Backend

The `./backend` directory contains a partially completed Flask server with a pre-written SQLAlchemy module to simplify your data needs. You will need to complete the required endpoints, configure, and integrate Auth0 for authentication.

[View the README.md within ./backend for more details.](./backend/README.md)

Few modifications have been made to model.py

### Frontend

The `./frontend` directory contains a complete Ionic frontend to consume the data from the Flask server. You will only need to update the environment variables found within (./frontend/src/environment/environment.ts) to reflect the Auth0 configuration details set up for the backend app.

[View the README.md within ./frontend for more details.](./frontend/README.md)

### Resources

### Auth0 account

```
AUTH0_DOMAIN = 'fullstack-dev-world.us.auth0.com'
ALGORITHMS = ['RS256]
API_AUDIENCE ='drinks'

```

### Dummy accounts

### Manger account

```
User: coffeeshop_manager@udacity.com
password: manager@Udacity-coffee-shop
token expires every 36000 seconds
```

`eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6Imo5ZUczTEpJeG1HYjd6MjdJSVBIMSJ9.eyJpc3MiOiJodHRwczovL2Z1bGxzdGFjay1kZXYtd29ybGQudXMuYXV0aDAuY29tLyIsInN1YiI6ImF1dGgwfDYzMGM4MThhYjcwOTUzOWYyMDI3OGQ4NyIsImF1ZCI6ImRyaW5rcyIsImlhdCI6MTY2MTg2NDA4NywiZXhwIjoxNjYxODcxMjg3LCJhenAiOiJCSnhnMUpGajUwRlROeTJ5MXhMbkpQYVM5T1VnYXJTeCIsInNjb3BlIjoiIiwicGVybWlzc2lvbnMiOlsiZGVsZXRlOmRyaW5rcyIsImdldDpkcmlua3MiLCJnZXQ6ZHJpbmtzLWRldGFpbCIsInBhdGNoOmRyaW5rcyIsInBvc3Q6ZHJpbmtzIl19.SAaGY_vgKS2QchYqJ2jFXNhRKTU-NWNMEH2vEILTwybwZcolkroRVi4sxUJlCjLNLkg1J0MwS5YuhsS1Fy8i7I6yeMSg_O07iZqraPtLP4w67t26_RRX5TQ2vTA5FXUd_Pr9-EkL_7EfTNM_g0OcAgnLwubQ1zmcEDZUyY2ky4D2u-D-9nPLFPc7iyHGsHNxkaufmH8-l7trmeHftfdOPFgKtg6vCltfs9efSz2EcxoHGkCAEWdRtYOOW5k_eI4rIrZ1J6vyAm7ycO8tr74Sk8HApU8oSn6geCKsqffpAOe7j2h8wFU-DYJsNuW-pLDZnLJsqVzPQVdY3AuB5YboLQ`

### Barista account

User: coffeeshop_barista@udacity.com
password: barista@Udacity-coffee-shop
token expires every 7200 seconds

`eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6Imo5ZUczTEpJeG1HYjd6MjdJSVBIMSJ9.eyJpc3MiOiJodHRwczovL2Z1bGxzdGFjay1kZXYtd29ybGQudXMuYXV0aDAuY29tLyIsInN1YiI6ImF1dGgwfDYzMGNiNGY4NTJhODVlMzc3Njk0M2FkNiIsImF1ZCI6ImRyaW5rcyIsImlhdCI6MTY2MTg2MzUyMywiZXhwIjoxNjYxODcwNzIzLCJhenAiOiJCSnhnMUpGajUwRlROeTJ5MXhMbkpQYVM5T1VnYXJTeCIsInNjb3BlIjoiIiwicGVybWlzc2lvbnMiOlsiZ2V0OmRyaW5rcyIsImdldDpkcmlua3MtZGV0YWlsIl19.s-lY8L0xJ3rFm0gnBspwQnGSbGRuZhMWym4JDxQQEgZIZfeAHZ1jA8tAx2YD0ADr9Icxyr2pDGj-Ca8DOL6Pc5VUF0HXKaHoUDaCJMZd_wdOPoB91SXIVWWh5c1n5KPHZjGBSNzAnHgbAoIbVx2G8gFUE0h4YVMV68IxQG-_I5T_P7LbdiRmXpWhLooPVwJx8HqK6sOvAAg3nD3bIajXHt2u4WjHfw-mH_AiKtNSlgt8qN4bfHaWevSiRVTjONvflEIuvpxdueR1sqxgWO93lRxjja08kp1ClfL2D-e0aAKsBCpbULHRvPb1AaKQLOE0oW3ckbTDOusiZj7B1CkkUA`

### POSTMAN COLLECTIONS

Export collections can be found at : `/backend/Udacity-coffee-shop.postman_collection.json`

### .gitignore

**pycache**
coffeevenv

