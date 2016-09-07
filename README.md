# This is Chirper application using Rails 4.

This is the Chirper application for the
[Aleksandr Balakiriev](http://www.balakiriev.com/). You can use this reference implementation to help track down errors if you end up having trouble with code in the tutorial. In particular, as a first debugging check I suggest getting the test suite to pass on your local machine:

```
$ cd ~/workspace
$ git clone
$ cd chirper_v2
$ bundle install
$ bundle exec rake db:migrate
$ bundle exec rake test
```

The repository also has chapter-specific branches with the state of the code at the end of each chapter. You can view them as follows:

```
$ git branch --all
  .
  .
  .
  remotes/origin/account-activation-password-reset
  remotes/origin/filling-in-layout
  remotes/origin/following-users
  remotes/origin/log-in-log-out
  remotes/origin/master
  remotes/origin/modeling-users
  remotes/origin/sign-up
  remotes/origin/static-pages
  remotes/origin/updating-users
  remotes/origin/user-microposts
```

To check out one of these chapter-specific branches, just use `git checkout` followed by the name without `remotes/origin/`:

```
$ git checkout log-in-log-out
```
