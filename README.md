# datadog

## Why monitoring?
SASS provider need to monitor software systems they run for their customers.
The primary focus of monitoring a software system is to check its health. By keeping track of the health of the software system, we can determine whether the system is available or its health is deteriorating.

A software system running in production has three major components:

- **Application Software:** A software service provider builds applications that will be used by customers or the software is built in-house for internal use.
- **Third-party software:** Existing third-party software such as databases and messaging platforms are used to run application software. These are subscribed to as SaaS services or deployed internally.
- **Infrastructure:** This usually refers to the network, compute, and storage infrastructure used to run the application and third-party software. This could be bare-metal equipment in data centers or services provisioned on a public cloud platform such as AWS, Azure, or GCP.

## Proactive Monitoring
- An issue in production impacts the business continuity of the customers and, usually, there would be a financial cost associated with it.
- Unscheduled downtime of a software service would leave a negative impression on the users about the software service and its providers.
- Unplanned downtime usually creates chaos at the business level and triaging and resolving such issues can be stressful for everyone involved and expensive to the businesses impacted by it.
  
One of the mitigating steps taken in response to a production issue is adding some monitoring so the same issue will be caught and reported to the operations team.

Proactive monitoring refers to rolling out monitoring solutions for a software system to report on issues with the components of the software system, and the infrastructure the system runs on.

The key aspects of a proactive monitoring strategy are as follows:

### 