# School Management System

This system is an open-source application that was developed by using [Ruby On Rails](http://rubyonrails.org) Framework. It can apply to anykind of school.

## Getting Started

[Ruby On Rails](http://rubyonrails.org) is a web development framework that has the giant community in the world. Let's start installing some prerequisites before running the project.

### Prerequisites

Install Ruby Programming

```
sudo apt-get install ruby-full
```

Install Bundler

```
gem install bundler
```

Install Rails

```
gem install rails
```

Install PostgreSQL and Create an Owner Database

```
sudo apt-get install postgresql postgresql-contrib libpq-dev
sudo -u postgres createuser $USER
```

### Installing

Before running the project, you have to run some command to install third library gems which are from [RubyGems](https://rubygems.org), and create database.

Install Third Party Library Gems
```
bundle install
```

Create Database and Tables
```
rails db:migrate
```

## Running the tests

Running or hosting the system by this command:
```
rails s
```
