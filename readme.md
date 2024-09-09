# Using HTMX v2 with FastAPI

> A simple todo web app built using HTMX v2 with FastAPI.

This is the companion source code to this tutorial on TestDriven.io: <https://testdriven.io/blog/fastapi-htmx/>

I briefly wrote about it on my personal blog: <https://paul.af/testdriven-fastapi-htmx>

A hosted instance is available on Render: <https://fastapi-htmx-todo.onrender.com>

After cloning:

```sh
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

To run the app locally:

```sh
fastapi dev main.py
```

If you want to deploy this:

```sh
fastapi run main.py
```

If you're using Render, you can specify the port to bind to:

```sh
fastapi run main.py --port $PORT
```

## License

[MIT](https://pinjasaur.mit-license.org/@2024).
