# datadog

## Why monitoring?
SASS provider need to monitor software systems they run for their customers.
The primary focus of monitoring a software system is to check its health. By keeping track of the health of the software system, we can determine whether the system is available or its health is deteriorating.

A software system running in production has three major components:
- *Application Software:* A software service provider builds applications that will be used by customers or the software is built in-house for internal use.
- *Third-party software:* Existing third-party software such as databases and messaging platforms are used to run application software. These are subscribed to as SaaS services or deployed internally.
- *Infrastructure:* This usually refers to the network, compute, and storage infrastructure used to run the application and third-party software. This could be bare-metal equipment in data centers or services provisioned on a public cloud platform such as AWS, Azure, or GCP.
