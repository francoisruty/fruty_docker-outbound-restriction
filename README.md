https://fruty.io/2021/02/15/how-to-restrict-outbound-traffic-on-a-docker-infrastructure/

Only one thing to do to:

sudo docker-compoe up -d

sudo docker-compose exec protected-container /bin/bash

curl https://stackoverflow.com/
--> does not work

curl google.com
--> works

