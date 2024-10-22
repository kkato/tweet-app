# Tweet App

Tweet App is a simple social networking app where users can post, view, and delete short messages (tweets). Built with Ruby on Rails, it supports user authentication and basic CRUD operations for tweets.

## Features

- User authentication (Sign up, log in, log out)
- Post, view, edit, and delete tweets
- View tweets per user
- Display a timeline with tweets from all users

## Requirements

- Ruby: 3.1.6
- Rails: 7.0

### Database initialization

```
bundle exec rake db:create
bundle exec rake db:setup
```

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/username/tweet-app.git
   cd tweet-app
   ```

2. Install dependencies:
   ```
   bundle install
   ```

3. Set up the database:
   ```
   rails db:create
   rails db:migrate
   ```

4. Start the Rails server:
   ```
   rails server
   ```

5. Visit `http://localhost:3000` in your browser to view the app.

## Usage

- Sign up for an account.
- Create a new tweet from the homepage.
- View all tweets on the timeline.
- Edit or delete your own tweets as needed.


## Running Tests

To run the test suite, use the following command:
```
rails test
```
