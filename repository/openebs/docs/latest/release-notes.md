# Release notes 

## latest

- Exposed configuration for livenessProbe and readinessProbe
- User can enable advanced service health checks. Option to choose between a simple port-based check and an advanced producer-consumer check based on a custom heartbeat topic.

## v0.2.0 
July 30th, 2019

- Apache Kafka upgraded to 2.3.0.
- livenessProbe and readinessProbes made less aggressive. 
- Added CPU/Memory limits for the stateful pods
- Updated the default value of Zookeeper URI
- not-allowed plan added to prevent updating storage parameters