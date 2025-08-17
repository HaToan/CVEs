[Suggested description]
An issue in the Web Configuration module of Startcharge Artemis AC
Charger 7-22 kW v1.0.4 allows authenticated network-adjacent attackers
to upload crafted firmware, leading to arbitrary code execution.

[Vulnerability Type]
Buffer Overflow

[Vendor of Product]
Startcharge

[Affected Product Code Base]
Artemis AC Charger 7-22 kW - 1.0.4

[Affected Component]
Web config Interface

[Attack Type]
Remote

[Impact Code execution]
true

[Attack Vectors]
Adjacent network

[Reference]
https://www.starcharge.com/product/artemis/

[Has vendor confirmed or acknowledged the vulnerability?]
true

[Discoverer]
Ha Toan of VinFast

Use CVE-2025-52263.

------------------------------------------


[Suggested description]
StarCharge Artemis AC Charger 7-22 kW v1.0.4 was discovered to contain
a stack overflow via the cgiMain function at download.cgi.

[Vulnerability Type]
Buffer Overflow

[Vendor of Product]
StarCharge

[Affected Product Code Base]
Artemis AC Charger 7-22 kW - 1.0.4b1.0.4

[Affected Component]
CGI Interface

[Attack Type]
Remote

[Impact Code execution]
true

[Attack Vectors]
Network-adjacent

[Reference]
https://www.starcharge.com/product/artemis/

[Has vendor confirmed or acknowledged the vulnerability?]
true

[Discoverer]
Ha Toan of VinFast

Use CVE-2025-52264.

------------------------------------------

[Suggested description]
A stack overflow in StarCharge Artemis AC Charger 7-22 kW v1.0.4 allows
attackers to cause a Denial of Service (DoS) via sending a crafted OCPP
configuration request.

[Vulnerability Type]
Buffer Overflow

[Vendor of Product]
Startcharge

[Affected Product Code Base]
Artemis AC Charger 7-22 kW - 1.0.4b1.0.4

[Affected Component]
Webconfig Interface

[Attack Type]
Remote

[Impact Code execution]
true

[Attack Vectors]
Network-adjacent

[Reference]
https://www.starcharge.com/product/artemis/

[Has vendor confirmed or acknowledged the vulnerability?]
true

[Discoverer]
Ha Toan of VinFast

Use CVE-2025-52266.

------------------------------------------

[Suggested description]
This vulnerability allows network-adjacent attackers to execute
arbitrary code on affected devices through the Web Configuration
interface. Authentication is not required to exploit this
vulnerability.
The specific flaw exists within the processing of JSON input handled by
the Web Configuration module. The vulnerability arises due to a failure
to properly validate the length of user-supplied data before copying it
into a fixed-size stack buffer. By sending a specially crafted HTTP
request containing an oversized JSON field, an attacker can trigger a
stack-based buffer overflow. This may result in a crash of the service
and, under certain conditions, lead to arbitrary code execution in the
context of the affected process   " potentially allowing full device
compromise.

[Vulnerability Type]
Buffer Overflow

[Vendor of Product]
Startcharge

[Affected Product Code Base]
Artemis AC Charger 7-22 kW - 1.0.4b1.0.4

[Affected Component]
Webconfig Interface

[Attack Type]
Remote

[Impact Code execution]
true

[Attack Vectors]
Network-adjacent

[Reference]
https://www.starcharge.com/product/artemis/

[Has vendor confirmed or acknowledged the vulnerability?]
true

[Discoverer]
Ha Toan of VinFast

Duplicate of CVE-2025-52266

------------------------------------------
[Suggested description]
StarCharge Artemis AC Charger 7-22 kW v1.0.4 was discovered to contain
a hardcoded AES key which allows attackers to forge or decrypt valid
login tokens.
[VulnerabilityType Other]
Hard-coded Cryptographic Key

[Vendor of Product]
StarCharge

[Affected Product Code Base]
Artemis AC Charger 7-22 kW - 1.0.4b1.0.4

[Affected Component]
Webconfig Interface

[Attack Type]
Remote

[Impact Escalation of Privileges]
true

[CVE Impact Other]
Bypass authentication

[Attack Vectors]
Network-adjacent

[Reference]
https://www.starcharge.com/product/artemis/

[Has vendor confirmed or acknowledged the vulnerability?]
true

[Discoverer]
Ha Toan, Ngoc Hieu of VinFast

Use CVE-2025-52268.

------------------------------------------
[Suggested description]
This vulnerability allows network-adjacent attackers to execute
arbitrary code on affected devices through the Web Configuration
interface. Authentication is not required to exploit this
vulnerability.
The specific flaw exists within the processing of encrypted tokens in
the Web Configuration module. The vulnerability is due to insufficient
validation of the length of user-supplied data during token decryption
and parsing.
When handling a specially crafted token, the system copies decrypted
data into a fixed-size stack buffer without proper bounds checking.
This can trigger a stack-based buffer overflow, potentially overwriting
critical control structures on the stack.
An attacker can exploit this vulnerability by sending a malicious token
to the configuration endpoint, which could result in a service crash
or, under specific conditions, arbitrary code execution in the context
of the affected process   " potentially leading to full device
compromise.

[Additional Information]
https://www.starcharge.com/product/artemis/

[Vulnerability Type]
Buffer Overflow

[Vendor of Product]
Startcharge

[Affected Product Code Base]
Artemis AC Charger 7-22 kW - 1.0.4b1.0.4

[Affected Component]
Webconfig Interface

[Attack Type]
Remote

[Impact Code execution]
true

[Attack Vectors]
Network-adjacent

[Has vendor confirmed or acknowledged the vulnerability?]
true

[Discoverer]
Ha Toan of VinFast

[Reference]
http://artemis.com
http://startcharge.com
https://www.starcharge.com/product/artemis/

Duplicate of CVE-2025-52266