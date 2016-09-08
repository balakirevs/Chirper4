# This is Chirper application using Rails 4.

This is the Chirper application by
[Aleksandr Balakiriev](http://www.balakiriev.com/). 
You can use this reference implementation to help track down errors if you end up having trouble with code in the tutorial. 
In particular, as a first debugging check I suggest getting the test suite to pass on your local machine:

```
$ cd ~/workspace
$ git clone https://github.com/balakirevs/Chirper4.git
$ cd chirper4
$ git checkout chirper4_v2
$ bundle install
$ bundle exec rake db:migrate
$ bundle exec rake test
```
