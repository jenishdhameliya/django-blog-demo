
To set it up as a working repository (with django 1.6):

    mkvirtualenv django-blog-demo --no-site-packages
    workon django-blog-demo
    cdvirtualenv
    pip install django
    git clone https:// blog_examples
    cd blog_examples
    pip install -r requirements.txt
    python manage.py syncdb
    python manage.py migrate
    python manage.py runserver
