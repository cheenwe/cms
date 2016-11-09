# README

For Rails5

* Create your rails project

  ```
  rails new cms
  ```
* Add the gem in your Gemfile

  ```
	gem "camaleon_cms", github: 'cheenwe/camaleon-cms', branch: 'chinese-support' # current development version
	gem 'activemodel-serializers-xml', git: 'https://github.com/rails/activemodel-serializers-xml'
	gem 'draper', github: 'audionerd/draper', branch: 'rails5'
  ```

* Install the CMS (before this, you can change defaut configuration in config/system.json)
  ```
  rails generate camaleon_cms:install
  ```
  
* Create database structure

  ```
  rake db:migrate
  ```
* Start your server

  ```
  rails server # and then go to your browser http://localhost:3000/
  ```