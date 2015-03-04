sc-search
============

sc-search is an custom element to generic searches based in a preset model.


Usage
======

The sc-search uses the core-ajax component to search. The sc-search also requires
that your model have something similar the fields below. It's expected by default
the fields:

```
{
    "thumbnail": "http://api.randomuser.me/portraits/thumb/men/70.jpg",
    "short_header": "raggedann",
    "description": "Lorem ipsum dolor sit amet, consectetur adipiscing elit.
    Etiam commodo nisl in accumsan consequat. Donec vitae lectus tempor.",
    "type_content": {
        "name": "mural",
        "icon_img": "http://lorempixel.com/16/16/",
        "icon_html": "<i class='fb-iconfb-heart'>"
    },
    "dated": "21/03/2015 18h21"
}
```
