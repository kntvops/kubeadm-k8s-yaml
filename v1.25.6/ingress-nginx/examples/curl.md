curl -u 'foo:foo'  http://192.168.1.211 -H 'Host: nginx.linux.io'

while true;do curl -s -H "canary: never" http://myapp.linux.io;sleep 1;done


