# fire-relief

This is the project repo for our fire-relief project, aimed at helping those impacted by the [2025 LA Wildfires](https://en.wikipedia.org/wiki/January_2025_Southern_California_wildfires) in understanding and filling out home insurance claims forms. Leads: Khush Parikh, Kevin Lu, Claire Li. Special shoutout to Sneha Agarwal and Yash Agarwal (no, they're not siblings) for thugging out 3AM late nights too

<br>
<br>
<br>

domain: fire.bruinai.org
Useful commands for backend
```
celery -A tasks.celery worker --loglevel=info
gunicorn --bind 0.0.0.0:5000 wsgi:app
```
