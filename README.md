# flint-ocp-s2i


oc patch bc/flint-ui-node -p '{"spec":{"strategy":{"sourceStrategy":{"scripts": "https://raw.githubusercontent.com/craq2017/flint-ocp-s2i/master/frontend/nodejs/s2i/bin"}}}}'

