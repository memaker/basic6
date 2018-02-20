# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

	Tutorial
	https://docs.docker.com/compose/rails/#restart-the-application

* Database creation

	$ docker-compose run web rake db:create

* Database initialization

* How to run the test suite

	$ docker-compose up/down

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

	In order to start the application, just execute the commands in order:

	$ docker-compose run web rake db:create
	$ docker-compose up

	re-start the application

	$ docker-compose run web bundle install
	$ docker-compose up --build

	database modifications? if yes, in other terminal
	
	$ docker-compose run web rake db:create
	$ docker-compose run web rake db:migrate RAILS_ENV=development

