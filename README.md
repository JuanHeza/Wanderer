Flask is a minimal Python framework that helps you create a web server. 

Let's take a look at the code we have:

```python
from flask import Flask

app = Flask(__name__)

@app.route("/")
def hello_world():
    return "<h1>Hello, World!</h1>"
```
	
What did that code do?

First we `import` the `Flask` class. An instance of this class will be our WSGI application.

Next we create an instance of this class. The first argument is the name of the application’s module or package. `__name__` is a convenient shortcut for this that is appropriate for most cases. This is needed so that Flask knows where to look for resources such as templates and static files.

We then use the `route()` decorator to tell Flask what URL should trigger our function. In this case we use `/` routh, which is the default route of any website.

The function returns the message we want to display in the user’s browser. The default content type is HTML, so HTML in the string will be rendered by the browser.

To learn more, checkout the [official guide](https://flask.palletsprojects.com/en/2.0.x/quickstart/).

[Juegos PSP en vita](https://www.cheapassgamer.com/topic/281768-complete-list-of-pspminispsone-games-playable-on-vita/)

[Overlay svg on a map](https://stackoverflow.com/questions/28586618/add-custom-svg-layer-on-google-map-api-v3)

[map Bounds](https://developers.google.com/maps/documentation/javascript/examples/control-bounds-restriction)

[Mapa de nuevo leon](https://www.3museos.com/?eventos=la-gran-ciudad-del-nuevo-reino-de-leon)

[styling wizard](https://mapstyle.withgoogle.com/)

[D&D Charactersheet](https://media.wizards.com/2021/dnd/downloads/dnd_blankcharactersheet_es.pdf)
