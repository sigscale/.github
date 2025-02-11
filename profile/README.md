## About
[SigScale](http://www.sigscale.com) is an open source company developing software solutions for communications service providers (CSP). Our RTU license free solutions are backed by commercial subscription support services.

## Solutions
Our software solutions are used in service provider networks for critical functions in service delivery and revenue management. Built for resilience with distribution across lightweight nodes, our solutions scale from private enterprise to national.

### SigScale OCS
An *Online Charging System* (OCS) performs real-time rating and charging of service usage and prepay balance management. The [ocs](https://github.com/sigscale/ocs) project provides the 3GPP OCS function as well as PCRF (*Policy and Charging Rules Function*) and *3GPP AAA Server* function for *non-3GPP* access authentication.

### SigScale CSE
A *Custom Service Environment* (CSE) hosts a CSP's custom service logic programs (SLP) in a framework for distributed, massively concurrent execution. The [cse](https://github.com/sigscale/cse) project enables custom SLPs with protocol stacks for CAMEL, INAP, DIAMETER, RADIUS and REST Open APIs. Complete SLPs are provided for prepaid charging of CS, PS, IMS, SMS, MMS with an external OCS.
 
### SigScale CGF
A *Charging Gateway Funcion* (CGF) performs collection and mediaion of charging data records (CDR). The [cgf](https://github.com/sigscale/cgf) project provides the 3GPP CGF function with all the 3GPP ASN.1 and GSMA TAP3 CODECSs. The Bx interface to the billing domain supports a normalized JSON format. A hardeneded and jailed SFTP server with configurable handlers provides automatic pipeline processing. 
 
## Protocol Stacks
SigScale software solutions are developed in the Erlang programming language for the OTP runtime environment. Our protocol stack application and CODEC library projects include [m3ua](https://github.com/sigscale/m3ua), [sccp](https://github.com/sigscale/sccp), [tcap](https://github.com/sigscale/tcap), [map](https://github.com/sigscale/map), [cap](https://github.com/sigscale/cse), [inap](https://github.com/sigscale/inap), [radius](https://github.com/sigscale/radierl) and [ngap](https://github.com/sigscale/5g-ngap).

