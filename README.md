# Blasting Off with the GitHub API :rocket:

We'll be blasting off with the GitHub API in San Francisco, on **September 13<sup>th</sup>**, **2016**, at **[GitHub Universe Training Day](githubuniverse.com/program/#training)**.

Come along and get a head start with our guided tour of the GitHub API.

You'll learn what's possible, and pick up some reusable code you can apply to your own projects, while following best practices.

## Running the lessons

To run the lessons in this repo, navigate to the corresponding lesson sub-directory and run the `lesson` script within (e.g. to run Lesson 08: `cd lesson08 && ./lesson`).

## :rocket: Launch

### Lesson 0
- What is an API?
- Why even API?
- Why use the GitHub API?
- Introduction to the GitHub API

## :earth_americas: Orbit
### Lesson 1
- Making requests
  - Interacting with the API
  
### Lesson 2
- Diving a little deeper
  - More on that command line, though
  - Some example requests with cURL

### Lesson 3
- Rate limits
  - Bummer
- Authentication
  - Sweet

### Lesson 4
- Authentication
  - OAuth
  - Personal access tokens
  
### Lesson 5
- Use a bash script that leverages HTTPie and jq to audit user access to a repository
  - Generate a CSV report

### Lesson 6
- Oktokit!
  - [https://github.com/octokit/octokit.rb](https://github.com/octokit/octokit.rb)

### Lesson 7
- Create a script that creates a daily log of all your GitHub activity
  - dailyships.rb
    - Convert the script into a web app

### Lesson 8
- What is a webhook and why is it not an API?
- Webhooks and GitHub
  - Configure a webhook to call your web app
    - Test it by changing something on GitHub

## :octocat: Flight
### Lesson 9
- Other resources exposed by the GitHub API

### Lesson 10
- Other useful tools for API development
  - httpbin.org
    - https://httpbin.org/
    -HTTP request and response service
  - ngrok 
    - https://ngrok.com/
    - Secure tunnels to localhost
  - Charles
    - https://www.charlesproxy.com/
    - HTTP proxy / HTTP monitor / Reverse proxy to view all HTTP and SSL/HTTPS traffic
