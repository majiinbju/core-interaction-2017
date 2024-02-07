# `📖` Create a JSON file
> **[Core Interaction Lab](https://github.com/majiinbju/core-interaction-2017)**<br>
> *Parsons School of Design<br>
> Communication Design<br>
> Spring 2018 &nbsp;&middot;&nbsp;
> Wednesday / 9:00 – 11:40 am*
> 
---
## `🎯` Objective
> - this .json file will contain information about you. Read carefully to make sure content is structured uniformly. The top level will contain 4 keys: `“name” “home” “url” “favorites”:`
> - `“name”` should be an array with strings. Put as many names as you like, in the order you prefer. Mine looks like this: `[“Robby”, “Kraft”]`
> - “home” should be an object with 2 keys, `latitude` and `longitude`, each value is a number. This is the location you come from or where were you born. Whatever you call your first home.
---
## `🧪` Results
```json
{
    "name": ["vivek", "bajaj"],
    "home":
    {
        "latitude": 39.1377573,
        "longitude": -84.5055621
    },
    "url": "https://bajju.info",
    "favorites":
    {
        "colour": "#fdff3c",
        "books":
        {
            "title": "kafka on the shore",
            "author": "Haruki Murakami"
        },
        "tool": "Sublime",
        "temperature": 59
    }
}
```
<!-- ![Vivek.JSON](code-snap.png) -->
---
## `✅` Requirements
> - `“url”` should be a string, a url to some kind of website of yours: a portfolio, if you have one, a social media page, or a github page.
> - `“favorites”` should be an object with these keys and values:
> - `“color”`, a string: a 6-digit hex value (what’s your favorite color right now)
> - `“book”`, an object with keys “title” and “author”, both values are strings
> - `“tool”`, a string: your favorite tool for creating (brush, camera, Photoshop,...)
> - `“temperature”`, a number: your ideal outdoor temperature. in celsius (Google search can convert from Fahrenheit)
---
> [viv1.info](https://www.bajju.info) &nbsp;&middot;&nbsp;
> [@majiinbju](https://github.com/majiinbju) &nbsp;&middot;&nbsp;
> [linkedin](https://www.linkedin.com/in/vivek-bajaj/)
---
