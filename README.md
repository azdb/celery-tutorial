# celery-tutorial

chose this one the first time https://tests4geeks.com/blog/python-celery-rabbitmq-tutorial/
- tried to replicate and gave up with PATH issues, moved to this tutorial https://suzannewang.com/celery-rabbitmq-tutorial/
- had issues until I fixed PATH 
 - appended venv path `export PATH=$PATH:/Users/az/Library/Python/3.8/bin` which indirectly writes to `~/.zprofile` PATH https://docs.python-guide.org/dev/virtualenvs/, https://techpp.com/2021/09/08/set-path-variable-in-macos-guide/
  - paste link here
  - this? https://stackoverflow.com/questions/45909256/setting-up-django-celery-location-for-celery-path
- When I picked this up I should've gone way back into my bash history
