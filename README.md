Issue tracker
========
## live demo: [https://issuetrackermjl.herokuapp.com/](https://issuetrackermjl.herokuapp.com/)
#### users:
##### user1, user2, user3, user4
#### password:
##### password


![alt text](show.gif)
##### add new issue
![alt text](show2.gif)
##### status open -> pending -> closed
![alt text](show3.gif)
##### /new as popup and static 
![alt text](show4.gif)

* typescript
* express
* passport
* next.js
* SSR
* react
* mongodb


#run
--------
- run mongodb 
- yarn dev 


#env
--------
MONGODB_URI (default: __mongodb://localhost:27017/issuetracker__ )
PORT (default: __9000__)

#tests
--------

- __yarn test__ 
will run unit tests for components  (pages/*.test.tsx components/*.test.tsx)
[coverage](https://issuetrackermjl.herokuapp.com/static/coverage/index.html)
- __yarn testrest__
will test API (index.test.ts) - *you need to run yarn dev first*


#todo:
--------

- pagination
- some filters ?

---

## Support

If this project saves you time, you can buy me a coffee:

[![Sponsor on GitHub](https://img.shields.io/badge/Sponsor-mi4uu-ec4899?logo=github-sponsors&logoColor=white)](https://github.com/sponsors/mi4uu)
[![PayPal](https://img.shields.io/badge/PayPal-mi4uuuu-00457C?logo=paypal&logoColor=white)](https://www.paypal.com/paypalme/mi4uuuu)

## License

AGPL-3.0-or-later, see [LICENSE](LICENSE).

Need it in a closed-source product, or can't meet the AGPL terms? Commercial licences are available on request: get in touch via [lipinski.work](https://lipinski.work).

By sending a pull request you agree that your contribution may be offered under both the AGPL and a commercial licence.

## Author

Made by [Michał Lipiński](https://lipinski.work) ([GitHub](https://github.com/mi4uu)).
