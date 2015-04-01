# nasu/smalllight

smalllight - https://code.google.com/p/smalllight/

## usage

Using quickly sample images:

```
git clone [repository]
docker build -t nasu/smalllight .
docker run -d -p 80:80 --name smalllight nasu/smalllight
```

You can confirm one resize image by accessing the following.

```
http://[host]/twitter.png
http://[host]/resize/twitter.png
```

Using your images:

```
docker run -d -p 80:80 --name smalllight -v `pwd`/html:/var/www/html nasu/smalllight
``


