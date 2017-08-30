<p align="center"><a href="https://use.delivery/"><img src="http://i.imgur.com/7KZm8VE.jpg" align="center" width="600" alt="Delivery"></a>

<p align="center"><img src="https://img.shields.io/badge/styled_with-prettier-ff69b4.svg" align="center" alt="styled with prettier"></p>

## Development

    $ git clone git@github.com:fabe/delivery.git
    $ cd delivery
    $ yarn install
    $ yarn run dev

## Credentials

Pass AWS credendials through the environment variables `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY`. Edit the database credentials inside `server/config/index.example.js`, then rename the file to `index.js`. I'm using mLab to host my database, but it should be starightforward to use something else.

## Author
- Fabian Schultz ([@fschultz_](https://twitter.com/fschultz_))
