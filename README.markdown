# Code TV Puma

This is the Code School Journal application used in the Puma episode of Code TV.

## Setup

Clone the repository:

		$ git clone https://github.com/emachnic/code_tv_puma.git

Go into the directory and run the following:

		$ cd code_tv_puma
		$ bundle install
		$ rake db:setup

After the database is created and seeded, run the server:

		$ puma

In your browser, go to http://localhost:9292 and you should see the `Entries#index`
page

 
