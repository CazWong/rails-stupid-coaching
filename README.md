# README

A very simple Ruby on Rails app created as part of Le Wagon's web development bootcamp curriculum. This project was built for learning purposes.

The **Stupid Coach** takes a question as input and returns a hard coded response to encourage you to go to work!


## Features

- Plain text interface
- Simple form to submit your question
- Quirky, hardcoded logic to simulate a “coach-like” response

## Prerequisites

Make sure the following tools are installed:

- **Ruby** 3.2.2 (use [rbenv](https://github.com/rbenv/rbenv) to manage Ruby versions)
- **Rails** 6.1.6
- **SQLite3**
- **Bundler** (to manage and install gem dependencies)

## Getting Started

1. **Clone the repository**
git clone https://github.com/your-username/rails-stupid-coaching.git
cd rails-stupid-coaching

2. **Install dependencies**
bundle install 

3. **Run server**
rails server

4. **Open app on web browser**
Go to http://localhost:3000/ask 

## How app works

Ask a question, and the coach will respond with one of three hardcoded replies based on your input:

If your input ends with a "?", the coach responds: "Silly question, get dressed and go to work!"

If you type "I am going to work", the coach replies: "Great!"

For any other statement, the coach says: "I don't care, get dressed and go to work!"
