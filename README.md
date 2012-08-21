# Learn Boostrap

Just a simple little way to learn Bootstrap that I'm using with my students.

This uses the `config.ru` Rack configuration file from: https://github.com/raul/rack-static-boilerplate

It also uses Twitter Bootstrap, v. 2.1.0:

To run with rack, install Ruby if you've not, and then run

    $ gem install rack
  
Clone this repository, change into its directory, and fire up rack like so:

    $ cd learn-bootstrap
    $ rackup -p 8888
    [2012-08-21 15:00:50] INFO  WEBrick 1.3.1
    [2012-08-21 15:00:50] INFO  ruby 1.9.3 (2012-04-20) [x86_64-linux]
    [2012-08-21 15:00:50] INFO  WEBrick::HTTPServer#start: pid=18438 port=8888

Point your favorite browser at http://localhost:8888/ and start hacking at the `public/index.html` file, which is itself just the simple template provided by Bootstrap.
 

