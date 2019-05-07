# ![LOGO](logo.png) Seldon **flow**ground Connector

## Description

A generated **flow**ground connector for the Seldon API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/rummblelabs.com/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:56+03:00

## API Description

Seldon is an Open Predictive Platform that currently allows item recommendations and general predictive models to be deployed based on structured historical data.

## Authorization

This API does not require authorization.

## Actions

### post new action between a user and an item

*Tags:* `oauth actions`

#### Input Parameters
* `oauth_token` - _optional_ - oauth token

### get items

*Tags:* `oauth items`

#### Input Parameters
* `oauth_token` - _optional_ - oauth token
* `full` - _optional_ - get all attributes for item
* `name` - _optional_ - keywords to match
* `dimension` - _optional_ - limit items to a particular dimension
* `type` - _optional_ - limit items to a particular type
* `limit` - _optional_ - limit number of items returned

### post new item

*Tags:* `oauth items`

#### Input Parameters
* `oauth_token` - _optional_ - oauth token

### update item

*Tags:* `oauth items`

#### Input Parameters
* `oauth_token` - _optional_ - oauth token

### get item type

*Tags:* `oauth items`

#### Input Parameters
* `oauth_token` - _optional_ - oauth token

### get item

*Tags:* `oauth items`

#### Input Parameters
* `oauth_token` - _optional_ - oauth token
* `itemId` - _required_ - the item id to get
* `full` - _optional_ - get all attributes for item

### Add a user interaction

*Tags:* `js actions`

#### Input Parameters
* `consumer_key` - _required_ - consumer key
* `user` - _required_ - user id
* `item` - _required_ - item id
* `type` - _required_ - type
* `jsonpCallback` - _required_ - JSONP callback
* `timestamp` - _optional_ - time

### Get recommendations for a user

*Tags:* `js recommendations`

#### Input Parameters
* `consumer_key` - _required_ - consumer key
* `user` - _required_ - user id
* `item` - _optional_ - currently viewed item id
* `limit` - _optional_ - max number of recommendations to return
* `dimension` - _optional_ - get recommendations for a particular item dimension (e.g., just sports articles)
* `attributes` - _optional_ - the fields to return
* `algorithms` - _optional_ - override default algorithms with specified algorithms
* `jsonpCallback` - _required_ - JSONP callback

### get token

*Tags:* `token`

#### Input Parameters
* `consumer_key` - _required_ - consumer key
* `consumer_secret` - _required_ - consumer secret

### get users

*Tags:* `oauth users`

#### Input Parameters
* `oauth_token` - _optional_ - oauth token
* `full` - _optional_ - get all attributes for user
* `name` - _optional_ - keywords to match
* `limit` - _optional_ - limit number of users returned

### post new user

*Tags:* `oauth users`

#### Input Parameters
* `oauth_token` - _optional_ - oauth token

### update user

*Tags:* `oauth users`

#### Input Parameters
* `oauth_token` - _optional_ - oauth token

### get a user

*Tags:* `oauth users`

#### Input Parameters
* `oauth_token` - _optional_ - oauth token
* `userId` - _required_ - the user id to get
* `full` - _optional_ - get all attributes for user

### get a user's recent actions

*Tags:* `oauth users` `oauth actions`

#### Input Parameters
* `oauth_token` - _optional_ - oauth token
* `userId` - _required_ - the user id to get
* `full` - _optional_ - get all attributes for user
* `limit` - _optional_ - limit number of actions returned

### get recommendations for a user

*Tags:* `oauth users` `oauth recommendations`

#### Input Parameters
* `oauth_token` - _optional_ - oauth token
* `userId` - _required_ - the user id to get
* `full` - _optional_ - get all attributes for user
* `limit` - _optional_ - limit number of actions returned
* `dimension` - _optional_ - get recommendations for a particular item dimension (e.g., just sports articles)
* `algorithms` - _optional_ - override default algorithms with specified algorithms

## License

**flow**ground :- Telekom iPaaS / rummblelabs-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
