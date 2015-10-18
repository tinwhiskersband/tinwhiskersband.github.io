# Posters

To create a thumbnail for a poster:

    sips -Z 500 2015-04-26.png --out 2015-04-26-thumb.png

To embed a poster in a post:

    <a href="{{ '/assets/img/posters/2015-04-26.png' | prepend: site.baseurl }}"><img src="{{ '/assets/img/posters/2015-04-26-thumb.png' | prepend: site.baseurl }}" alt=""></a>
