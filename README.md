# flint-ocp-s2i


oc patch bc/ets-backend -p '{"spec":{"strategy":{"sourceStrategy":{"scripts": "https://raw.githubusercontent.com/dmvolod/ets-ocp-s2i/master/backend/s2i/bin/"}}}}'

