# RottenPotatoes demo app: getting started

This app is associated with the free [online
course](http://www.saas-class.org) and (non-free)
[ebook](http://www.saasbook.info) Engineering Software as a Service.

To get started:

0. Setup a Linux development environment for the course.

0. Create your instance of this repo by clicking on the link the instructor provided to you, then in your terminal, type something similar to the following command to clone your fork to your development workspace (your specific URL will be slightly different):

  `git clone git@github.com:your_github_username/rottenpotatoes-rails-intro.git`

0. Then `cd rottenpotatoes-rails-intro` to change to the app's
directory.

0. Run the command `bundle install --without production` to make sure all the gems
(libraries) used by the app are in place.

0. Run `bundle exec rake db:setup` to create the initial database.

0. Run `rails server -p $PORT -b $IP` to start the app.  The command will showing the URL to visit in your browser to interact with
the running app.
