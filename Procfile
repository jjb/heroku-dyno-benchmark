# returns 200 to everything, needed so heroku sees the app as valid and I can upgrade the dyno type
web: socat TCP-LISTEN:8080,reuseaddr,fork SYSTEM:'echo -e "HTTP/1.1 200 OK\r\nContent-Length: 0\r\n\r\n"'
console: bash
