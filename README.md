# docker-php-cli

This image adds common things that I usually need to run php in command line.

## php-cli

Add this alias to your profile:
    alias bower='docker run -it --rm -v "$PWD:/usr/app/src" nunofrsilva/php-cli gosu php'

Use php in the current directory:

    php --version