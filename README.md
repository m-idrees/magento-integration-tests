# magento-integration-tests

## How to run cypress tests

### Prerequisites:

* Magento 2 with sample data should be installed on publically accessible URL
* Cypress should be installed
* For subscription test, "Push It Messenger Bag" product should be configured as subscription product

### Information: 

* These tests are for only Credit Card, Klarna DKK, and AltaPay subscription (Credit Card for subscription)
* In case, you don't want to test any of the above-mentioned payment methods, please leave it blank in the config file. i.e "CC_TERMINAL_NAME":""

### Steps:

* Install dependencies `npm i`
* Update "cypress/fixtures/config.json" 
* Execute `./node_modules/.bin/cypress run` in the terminal to run all the tests