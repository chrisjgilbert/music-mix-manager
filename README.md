# Music Mix Manager

A speedily built web app that lets music lovers save and tag their favourite mixes, and once listened, delete.

I approached this app in more of a BDD way - that is writing only integration tests rather than unit tests. The approach was influenced by this awesome (ThoughtBot tutorial)[https://thoughtbot.com/upcase/test-driven-rails].

## How to use
* `git clone` this repo
* `brew install postgresql` if you need postgres installing
* `bundle` to install dependencies
* `rake db:create` to create the database
* `rails s` to run the server

## To run the tests    
* `rake`

## To run the linter   
* `rubocop`

## Screenshots

### Add new mix
![add mix](public/add_mix.png)

### View all saved mixes
![all mixes](public/all_mixes.png)

### View mixes by tag   
![tagged mixes only](public/search_by_tag.png)
