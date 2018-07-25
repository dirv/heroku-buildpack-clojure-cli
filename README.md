# heroku-buildpack-clojure-cli

Use this package if you want to run Clojure applications using the built-in Clojure CLI, without having to use Leiningen or Boot.

# For it to work

`deps.edn` must be present in the project root.

# Still outstanding

 * Should cache .cpcache directory too
 * No environment variable support yet
 * `bin/release` should have some default targets if `Procfile` is not present
 * No ability to build a JAR during compile

