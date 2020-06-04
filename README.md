###  Deploy a high-availability web app using CloudFormation
There will be two parts to this project:
You'll first develop a diagram that you can present as part of your portfolio and as a visual aid to understand the CloudFormation script.
The second part is to interpret the instructions as well as your own diagram and create a matching CloudFormation script.



### Features
* Create Stack with
  * VPC
  * Internet gateway
  * 4 subnet 2 private and 2 public
  * 2 availability zones
  * Nat gateway 
  * Routing Table

* create server
  * load balancer
  * AutoScaling Group
  * Launch Configuration

### How to Run?
* run infrastructure
```
 ./create.sh stackname infrastructure .yaml infrastructure-params.json
```
* run server
 ```
./update.sh stackname server.yaml server-parameters.json
```
