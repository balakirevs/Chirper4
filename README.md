# This is Chirper application using Rails 5.

This is the Chirper application by
[Aleksandr Balakiriev](http://www.balakiriev.com/). 
You can use this reference implementation to help track down errors if you end up having trouble with code in the tutorial. 
In particular, as a first debugging check I suggest getting the test suite to pass on your local machine:

```
$ cd ~/workspace
$ git clone https://github.com/balakirevs/Chirper4.git
$ cd Chirper4
$ git checkout chirper5
$ bundle install --without production
$ bundle exec rails db:migrate
$ bundle exec rails test
$ rails s
```