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

The key aspects of a proactive monitoring strategy are as follows.

### Implementing a comprehensive monitoring solution

Traditionally, the focus of monitoring has been the infrastructure components – compute, storage, and network. As you will see later in this chapter, there are more aspects of monitoring that would make the list complete. All relevant types of monitoring have to be implemented for a software system so issues with any

### Setting up alerts to warn of impending issues

The monitoring solution must be designed to warn of impending issues with the software system. This is easy with infrastructure components as it is easy to track metrics such as memory usage, CPU utilization, and disk space, and alert on any usage over the limits. However, such a requirement would be tricky at the application level. Sometimes applications can fail on perfectly configured infrastructure. To mitigate that, software applications should provide insights into what is going under the hood. In monitoring jargon, it is called observability these days and we will see later in the book how that can be implemented in Datadog.

### Monitoring terminology and processes

**Host**

A host used to refer to a physical server housed in a data center. In the monitoring world, it refers to a device with an IP address. The first generation of monitoring tools, were tried to the host. This is no longer the case with tools such as datadog.

**Agent**

An agent is a service that runs alongside the application software system to help with monitoring. It runs various tasks for the monitoring tools and reports information back to the monitoring backend. The agents are installed on the hosts where the application system runs. It could be a simple process running directly on the operating system or a microservice.
