# Rendezvous API

API for Rendezvous app built for Cal Hacks 5.0 (2018).

![](45166465_447209502350458_5611679122196529152_n.gif)

![](45367117_1960669977303796_4648128845998718976_n.png)
![](45381700_112069509739822_2209745366528557056_n.jpg)

## Live Deploy [DEACTIVATED]

Deactivated to save money. :/

https://rendezvous-api.herokuapp.com/

See [main.py](/api/views/main.py) for more info on what each endpoint does.

## iOS App Repo

https://github.com/Huw-man/Flaker

## Endpoints

* POST create_user
  * param: code (int)
    * The user generated 6-digit code for their rendezvous group
  * param: lat (float)
    * The user's latitude
  * param: lon (float)
    * The user's longitude
* GET rendezvous, party_size, get_dest
  * param: code (int)
    * The 6-digit code used to identify the user's group
* GET locate_party
  * param: code (int)
    * The 6-digit code used to identify the user's group
  * param: user_id (int)
    * The id of the user who sent the request

## Testing with Postman

Rendezvous 1 tests create_user and rendezvous and Rendezvous 2 tests the remaining endpoints.

Rendezvous 1:
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/56c200022930b337b6b9)

Rendezvous 2:
[![Rendezvous 2](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/dbbf472e9a17d0e46eb9)

## Built With

* [Flask](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Heroku](http://flask.pocoo.org/) - Deployment
* [Flask Boilerplate](https://github.com/tko22/flask-boilerplate) - Boilerplate used

## Authors

* **Avneesh Mehta**
* **Woojin Ko**
* **Bayan Alizadeh**
* **Newman Hu**

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* All members of the team
* Inspiration
* Cal Hacks 5.0 sponsors and mentors
