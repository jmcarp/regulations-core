web: python manage.py syncdb --migrate --settings=regcore.settings.cf && python manage.py rebuild_index --settings=regcore.settings.cf --noinput --remove && waitress-serve --port=$VCAP_APP_PORT regcore.settings.wsgi_cf:application
