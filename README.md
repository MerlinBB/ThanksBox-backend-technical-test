# Mo Backend Technical Test

The central part of Mo's tech stack is its API. This repository contains a simplified version, using the same technologies. The API is built in Ruby, with Sinatra, tests are written in RSpec and we use MongoDB as our database.


## Test Process

1. Clone this repo `git clone git@github.com:ThanksBox/backend-technical-test.git`
2. Move into folder `cd backend-technical-test`
3. Remove git history `rm -rf !$/.git`
4. Initialise a fresh repo `git init`
5. Make a first commit `git add . && git commit -m "start test"`
6. Solve the below tasks, committing as you go
7. Bundle the end result, and submit this via email (awesome-dev-jobs@mo.work) `git bundle create <yourname>.bundle master`


## Setup

To run tests: `docker-compose run web rspec`

To run application: `docker-compose run web`


## Tasks

There are some failing tests 😭

Try to fix all or as many as you can within two hours. Aim to demonstrate your knowledge of Ruby, Sinatra and MongoDB.

1. Scopes: Modify the `User.by_email` scope to allow wildcard search.
2. Data: Complete the method `Thank.stats_messages_sent` which should return all sent messages grouped by a group value.
3. API: Post a message to another user. (User authentication is simplified.)
