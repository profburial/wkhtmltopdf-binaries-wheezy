# wkhtmltopdf for Debian Wheezy

[All the binaries for Debian Wheezy from http://wkhtmltopdf.org/downloads.html](http://wkhtmltopdf.org/downloads.html)

## Install

1. Install Composer:

    ```    
    curl -s https://getcomposer.org/installer | php
    ```
    
2. Add to your `composer.json` file:

    ```js
    {
        "require": {
            "profburial/wkhtmltopdf-binaries-wheezy": "1.0"
        }
    }
    ```

3. All the binaries are symlinked to the following paths:

```
vendor/bin/wkhtmltoimage-linux-wheezy-amd64

vendor/bin/wkhtmltoimage-linux-wheezy-i386

vendor/bin/wkhtmltopdf-linux-wheezy-amd64

vendor/bin/wkhtmltopdf-linux-wheezy-i386
```

Enjoy the bin files!