# Jsoup examples

This repository contains the examples from [jhy/jsoup](https://github.com/jhy/jsoup/).

## Running the examples

In order to run the examples, first build the project and create launcher scripts:

    ./gradlew clean install

Afterwards you can run the scripts located in `build/install/jsoup-examples/bin/`:

    jsoup-example-html-to-plaintext
    jsoup-example-html-to-plaintext.bat
    jsoup-example-list-links
    jsoup-example-list-links.bat
    jsoup-example-wikipedia
    jsoup-example-wikipedia.bat

For example, run this on Unix:

    ./build/install/jsoup-examples/bin/jsoup-example-wikipedia

On Windows:

    ./build/install/jsoup-examples/bin/jsoup-example-wikipedia.bat

Similarly, for the link extraction example:

    ./build/install/jsoup-examples/bin/jsoup-example-list-links http://news.ycombinator.com

Or for the HTML to plain-text conversion:

    ./build/install/jsoup-examples/bin/jsoup-example-html-to-plaintext http://news.ycombinator.com

## License

As jsoup itself, this project is distributed under the liberal [MIT license](https://jsoup.org/license).
