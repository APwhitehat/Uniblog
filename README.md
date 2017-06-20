# UniBlog

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ git clone https://github.com/APwhitehat/Uniblog.git
$ cd UniBlog
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```


## License

All source code is available jointly under the MIT License and the Beerware License. See [LICENSE.md](LICENSE.md) for details.

For more information, see the
[*Ruby on Rails Tutorial* book](http://www.railstutorial.org/book).