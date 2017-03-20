# Ruby on Rails Tutorial sample application

This is the sample application for 
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](http://railstutorial.org/)
by [Michael Hartl]

## License
All Source code yaddayadddaydaddd

## Getting started

To get started with the app, clone the repo and then install the needed gems:
---
$ bundle install --without production
---

Next, migrate the database:
---
$ rails db:migrate
---

Finally, run the test suite to verify that everything is working correctly:
---
$rails test
---

If the test suite passes, you'll be ready to run the app in a local server:
---
$rails server
---
