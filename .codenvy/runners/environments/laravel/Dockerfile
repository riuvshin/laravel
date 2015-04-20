FROM eivantsov/laravel
VOLUME ["/home/user/app"]
ENV CODENVY_APP_BIND_DIR /home/user/app
CMD cd /home/user/app && php artisan serve --port=8080 --host=0.0.0.0 2>&1