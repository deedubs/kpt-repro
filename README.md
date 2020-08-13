# kpt-repro

Example of kpt flow and outputs

1. > kpt pkg init --name kpt-repro-steps .
2. > kpt pkg sync set https://github.com/kubernetes/ingress-nginx.git/deploy/static/provider/baremetal@controller-0.31.1 ingress-nginx
   > kpt pkg sync .
3. > kpt pkg update ingress-nginx@controller-0.32.0