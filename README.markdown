rupakganguly.com
================

Middleman based blog site, developed using the Cloud9 IDE.

## Development

1. Install the middleman gem

    ``` $ gem install middleman```

2. Install the middleman blog extension gem

    ``` $ gem install middleman-blog```

3. Create a new blog site

    ``` middleman init rgblog --template=blog ```

4. Start adding articles

    ``` middleman article <article_name>```
    
    See [Middleman help on blog sites](https://middlemanapp.com/basics/blogging/) for details.

## Preview site

Run the middleman server

``` $ middleman server -h $IP -p $PORT ```

Access the site by pointing the browser to ```https://<workspace>-<username>.c9.io/``` .