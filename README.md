# yacht-test
test example to show yacht functionality

All your base yamls for each env will go inside

`base/`  directory.

Each env specific yamls will reside in `[env]/` directory.

To Run this with Yacht, first download yacht via go-get:

`go get -u github.com/nfons/yacht`

clone this repo:

`git clone https://github.com/nfons/yacht-test`


cd into this repo, and then run yacht:

`yacht -e dev -f base/deployment.yaml`


You will see a deployment with the values specified in dev.conf.

if you want to do a "prod" deployment:

`yacht -e prod -f base/deployment`


