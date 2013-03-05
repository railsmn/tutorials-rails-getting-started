tutorials-rails-getting-started
===============================
Making your first Rails applicaiton  

### Intro  
We’re going to follow the basic flow of the [Rails Getting Started Guide]
(http://guides.rubyonrails.org/getting_started.html), highlighting the important parts and the 
commands you need to run to create your first Rails Appplication. We’ll assume you have, (1) Rails environment setup, 
and (2) Sqlite or Postgresql (Sqlite is fine, but using Postgresql will enable you to 
deploy it to Heroku fast and easily). This means you can do this in the terminal,  
    
    ruby -v  
    rails -v  
    psql -v  

### Big Picture  
Rails is built using Model-View-Controller components. Not sure what these are? Read this. http://guides.rubyonrails.org/getting_started.html#the-mvc-architecture.  

### Step 1 - Creating a Rails application  
+ [http://guides.rubyonrails.org/getting_started.html#creating-a-new-rails-project](http://guides.rubyonrails.org/getting_started.html#creating-a-new-rails-project)  
+ use postgresql if you have Postgresql installed and want to deploy to Heroku  

### Step 2 - Viewing the Rails application in your browser  
+ [http://guides.rubyonrails.org/getting_started.html#hello-rails](http://guides.rubyonrails.org/getting_started.html#hello-rails)  

### Step 3 - Creating objects in the database and in the browser.
+ [http://guides.rubyonrails.org/getting_started.html#getting-up-and-running-quickly-with-scaffolding](p://guides.rubyonrails.org/getting_started.html#getting-up-and-running-quickly-with-scaffolding)  
+ Using Rails’ templating system, “generators”. We’ll use these at first, but teach you what they do so that you’ll be free of use generic components.  

### Step 4 - Deploying to Heroku after Step 7 (for those who used Postgresql)  
+ Follow these steps. [https://devcenter.heroku.com/articles/quickstart](https://devcenter.heroku.com/articles/quickstart)  
+ Follow these steps. [https://devcenter.heroku.com/articles/rails3](https://devcenter.heroku.com/articles/rails3)  
