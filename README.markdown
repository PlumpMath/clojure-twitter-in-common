# twitter-social-graph

This is a small sample project using Clojure twitter, oAuth and Midje.  It contains functions to find the followers in common between two twitter usernames

## Usage

To use, you need to set up a Twitter Application http://twitter.com/apps/new.
Once you have your oauth-access-token and your oauth-access-token-secret, you can put them in the core.clj file to connect up to Twitter.

See the test file for the example of the main  (followers-in-common "username1" "username2")

##Installation
Install Leiningen https://github.com/technomancy/leiningen
lein deps
lein test


## License

Copyright (C) 2011 Gigasquid Software LLC

Distributed under the Eclipse Public License, the same as Clojure.
