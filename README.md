# Monitoring

## Questions to ask before monitoring
- What should we monitor
- What resources will we monitor
- How often should we monitor
- What tools are we going to use to perform these tasks
- Who will perform these tasks
- Who should be notified in an emergency if something goes wrong

## 4 Golden signals of monitoring
- Latency: is the time that it takes to service a request
- Traffic: is the amount of activity in the application
- Errors: are the rate of requests that are failing
- Saturation: is how "full" your service is

## Automate the process
- Application Load Balancer (ALB)
- Autoscaling Group
- Launch template config - how many instances at all times
- 2 instances - Min=2 abd Max=3
- Policices of scaling out - and scaling in to Min=2 instances

Scaling on Demand
Scaling up vs Scaling out
Scaling up: increasing the size of your instance
Scaling out = adding more of the same components in parallel to spread out a load. Scaling up = making a component bigger or faster so that it can handle more load.