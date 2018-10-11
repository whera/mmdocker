FROM nginx:latest

ADD ./melman.local.conf /etc/nginx/conf.d/melman.local.conf
ADD ./tardis.conf /etc/nginx/conf.d/tardis.conf
ADD ./marty.local.conf /etc/nginx/conf.d/marty.local.conf
ADD ./recruta.local.conf /etc/nginx/conf.d/recruta.local.conf
ADD ./ralf.local.conf /etc/nginx/conf.d/ralf.local.conf

ADD ./gabineterson.local.conf /etc/nginx/conf.d/gabineterson.local.conf

CMD ["nginx", "-g", "daemon off;"]
