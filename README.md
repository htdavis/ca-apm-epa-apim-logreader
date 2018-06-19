# CA APM Log Monitor for CA API Gateway Integration through CA Precision API Monitoring

# Description
This is a log monitor reports the number of HTTP 4xx and 5xx events by Gateway and Service.

## Short Description
Log Monitor for HTTP events.

## APM version
Tested with CA APM 10.5+.

## Supported third party versions
n/a
## Limitations
Works on any Linux/UNIX or Windows system running Perl 5.22 or higher.

## License
[Apache License 2.0](LICENSE)

# Installation Instructions

## Prerequisites
* CA APM 10.x Environment Peformance Agent (EPAgent) or Infrastructure Agent (APMIA)
* Java Runtime Environment 8 or higher for the agent
* Perl 5.22 or higher

## Dependencies
n/a

## Installation
### EPAgent
Copy **ssgLogReader.pl** and **ssgLogReader.cfg** to ***\<agent_home\>\/epaplugins\/apim***.  
Copy **LogReader.pm** to ***\<agent_home\>\/epaplugins\/lib\/perl\/Wily***.  
The Perl module has been customized to allow for multiple values to be tokenized from the log message.

### Infrastructure Agent
TBD

## Configuration
Log readers are stateful plugins; programs that run continuously at the start of the monitor agent.  
At least one plugin must be configured per logfile to be monitored.


# Usage Instructions

## TBD



## Debugging and Troubleshooting
Check the log file written by the individual scripts.

## Future work
Anybody can contribute to this project over GitHub, e.g. changing a property in a configuration file on every EM, backup/copy configuration or data files, restarting a process, ...

## Support
This document and associated tools are made available from CA Technologies as examples and provided at no charge as a courtesy to the CA APM Community at large. This resource may require modification for use in your environment. However, please note that this resource is not supported by CA Technologies, and inclusion in this site should not be construed to be an endorsement or recommendation by CA Technologies. These utilities are not covered by the CA Technologies software license agreement and there is no explicit or implied warranty from CA Technologies. They can be used and distributed freely amongst the CA APM Community, but not sold. As such, they are unsupported software, provided as is without warranty of any kind, express or implied, including but not limited to warranties of merchantability and fitness for a particular purpose. CA Technologies does not warrant that this resource will meet your requirements or that the operation of the resource will be uninterrupted or error free or that any defects will be corrected. The use of this resource implies that you understand and agree to the terms listed herein.

Although these utilities are unsupported, please let us know if you have any problems or questions by adding a comment to the CA APM Community Site area where the resource is located, so that the Author(s) may attempt to address the issue or question.

Unless explicitly stated otherwise this extension is only supported on the same platforms as the APM core agent. See [APM Compatibility Guide](http://www.ca.com/us/support/ca-support-online/product-content/status/compatibility-matrix/application-performance-management-compatibility-guide.aspx).

### Support URL
https://github.com/htdavis/ca-apm-epa-apim-logreader

# Contributing
The [CA APM Community](https://communities.ca.com/community/ca-apm) is the primary means of interfacing with other users and with the CA APM product team.  The [developer subcommunity](https://communities.ca.com/community/ca-apm/ca-developer-apm) is where you can learn more about building APM-based assets, find code examples, and ask questions of other developers and the CA APM product team.

If you wish to contribute to this or any other project, please refer to [easy instructions](https://communities.ca.com/docs/DOC-231150910) available on the CA APM Developer Community.

## Categories

CA APM Integration


# Change log
Changes for each version of the extension.

Version | Author | Comment
--------|--------|--------
1.0 | Hiko Davis | First version of the extension.
