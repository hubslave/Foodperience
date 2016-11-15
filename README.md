# SWR >> Codefest 2016 Foodperience

User erstellen in einer Challenge aus vorgegebenen Zutaten kreative Rezepte und geben dabei anderen Inspiration.

## Jekyll & Bootstrap

* [Jekyll](http://jekyllrb.com/)
* [Bootstrap](http://getbootstrap.com) (3.3.1)
* [jQuery](http://jquery.com/) (2.1.3)

## Requirements

* Ruby (including headers)
* [Jekyll](http://jekyllrb.com/docs/installation/)

## Setup

```
# http://jekyllrb.com/docs/quickstart/
$ bundle install
$ jekyll serve
```

Open [http://localhost:4000](http://localhost:4000).

## Build

To build the site with scripts/stylesheets concatenated and compressed.

```
$ rake build
$ cd _dist
$ ruby -run -e httpd . -p5000

Or (in one line)

$ rake; cd _dist; ruby -run -e httpd . -p5000; cd ..
```

Open [http://localhost:5000](http://localhost:5000) to verify.
