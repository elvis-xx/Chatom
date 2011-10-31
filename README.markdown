a small forum for friends

#Install
  * You need to install *Ruby 1.9.2*, *Rubygems* and *Rails 3.1* first.
  * Install *MongoDb*
  Install thought this commands:    

    ```
    cp config/config.yml.default config/config.yml
    cp config/mongoid.yml.default config/mongoid.yml
    cp config/redis.yml.default config/redis.yml
    bundle install
    bundle update rails
    rails s
    ```