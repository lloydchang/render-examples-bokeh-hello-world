# README

This is the [Bokeh](https://bokeh.org/) [first stieps](https://docs.bokeh.org/en/latest/docs/first_steps.html) example for [Render](https://render.com).

The app in this repo isn't deployed at [https://bokeh.onrender.com](https://bokeh.onrender.com).

## Deployment

For now, mostly follow the guide at https://render.com/docs/deploy-flask.

Please change **Start Command** as follows:

**Change from:**

> **Start Command** `gunicorn app:app`

**Change to:**

> **Start Command**	`bokeh serve --show myapp.py --port 8000`
