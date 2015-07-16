# [jamesroyal.info](http://jamesroyal.info)

The source for jamesroyal.info

Based heavily [on the theme from ddbullfrog](https://github.com/ddbullfrog/iCard-Resume)

## Get it up and running

#### Install nginx
`docker run -d -p 80:80 -v /var/run/docker.sock:/tmp/docker.sock -t jwilder/nginx-proxy`

#### Use Jekyll to serve it
`docker run -e VIRTUAL_HOST=jamesroyal.info -d -v "$PWD:/src" -p 4000:4000 grahamc/jekyll serve -H 0.0.0.0`
