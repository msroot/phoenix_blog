# PhoenixBlog

##Create a new app with a mysql driver 
	mix phoenix.new phoenix_blog --database mysql

##Create the db
	mysql -u root  
	CREATE DATABASE phoenix_blog_dev


##Install dependencies
	 mix deps.get


##Migrate the db
	mix ecto.create && mix ecto.migrate
	
## Install node dependencies
	npm install

##Generate a scaffold
mix phoenix.gen.html Post posts title body:text

## Start Phoenix endpoint with 
	mix phoenix.server


Now you can visit [`localhost:4000`](http://localhost:4000) from your browser		