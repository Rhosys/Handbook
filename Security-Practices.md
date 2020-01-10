## Best Practices

These practices have been created by evaluating sources of security control frameworks (such as SOC2) as well as community standards. Combined with our cloud provider we implement the following.

### Access Controls

User access to production data is authorized by approved federated authentication providers only. This helps to provent potential data abuse and theft or unauthorized removal of data. The approved authentication providers include controls for multifactor. On the service side, authenticity of application access tokens are verified using the federated providers via JWEs (RFC 7516, 7519).

Administrative access to data is restricted to service account clients or cloud admin. Access to encrytion keys is logged and reported.

### Availability

Our services ensure maximum uptime via our Service Level Agreement (SLA). This level is established internally, and published for external facing software service programmatic interfaces. Monitoring of service reliability is done through alerting on cloud infrastructure problems as well as application issues via CloudWatch and other monitoring tools. In the case of a widespread disruption, backups of critical data are stored separate from possibly affected systems.

### Monitoring and alerting

#### Cloud assets and intrusion detection

Using AWS services CloudTrail, CloudWatch, Config, S3, and SNS, we monitor and alert to unexpected activity. We use AWS's services to inform us of any anomolies.

#### Application level initiatives

* All data is encrypted in transit.
* Encryption keys are also encrypted and only useable by authorized services and administrative users.
* Identifying data is encrypted at rest.
* Access to cloud resources is always done via cloud native roles and never by keys.
* Plain text keys are read once at creation time and never directly accessed or stored in an unencrypted format.
* Services always verify the authentication and authorization of the calling credentials before allowing access to application resources.

### Response

Security is a key importance of our team, and as every issue with our services, we provide a proportional response given risk and impact.