# BitShares Email Notifier

## About the service and current development

This service monitors your BitShares accoount and notifies you by Email or Telegram regarding the following activity types:
- Transfer
- Fill order

To do's:
- Deposit
- Withdrawal
- Decrease of collateral ratio below 2.0

## For Email-notifications
https://github.com/TrustyFund/notifier - this is fork under development

## For Telegram-notifications
Please visit https://github.com/TrustyFund/notifier - this is fork under development


## Running the service on your own node 
``
cp config.sample.js config.js
``

Then add your credentials including service account brainkey and email options.

You can also set System asset and Price for subscription (default is bts and 0)

Then typicaly start:
``
npm install && npm start
``
