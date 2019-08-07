# voila-homepage
A simple homepage for serving notebooks with voila.

[`voila`] is amazing! This project present a single homepage for serving voila and other dashboards (via links).

## Installation

- make a directory where you want to serve your notebooks from, e.g., `~/my_notebooks`
- put your notebooks in that directory
- copy `homepage.ipynb` to that directory
- cd to that directory
- start <kbd>`voila`</kbd>; you will see command line output like

```
17:43 $ voila
[Voila] Using /tmp to store connection files
[Voila] Storing connection files in /tmp/voila_r_kwka3j.
[Voila] Serving static files from /home/user/voila/voila/static.
[Voila] Voila is running at:
http://localhost:8868/
```

- point your browser to `http://localhost:8866/voila/render/homepage.ipynb` and **boom** ... you are greated with a dynamically created Vuetify display of your notebook directory!

![image](https://user-images.githubusercontent.com/16124573/62647088-ca41a280-b91d-11e9-9023-f06273eb09ce.png | width=500)



