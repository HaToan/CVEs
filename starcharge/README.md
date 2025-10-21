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
Hà Toàn, Tống Thế  Bảo of VinFast

Use CVE-2025-52263.

------------------------------------------


[Suggested description]
StarCharge Artemis AC Charger 7–22 kW v1.0.4 contains a stack overflow vulnerability in the cgiMain function of download.cgi, triggered by using the Content-Length value as the buffer size.

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
Hà Toàn, Trần Văn Quắc of VinFast

Use CVE-2025-52264.

------------------------------------------

[Suggested description] StarCharge Artemis AC Charger 7-22 kW v1.0.4 was discovered to contain a hardcoded AES key which allows attackers to forge or decrypt valid login tokens. [VulnerabilityType Other] Hard-coded Cryptographic Key

[Vendor of Product] StarCharge

[Affected Product Code Base] Artemis AC Charger 7-22 kW - 1.0.4b1.0.4

[Affected Component] Webconfig Interface

[Attack Type] Remote

[Impact Escalation of Privileges] true

[CVE Impact Other] Bypass authentication

[Attack Vectors] Network-adjacent

[Reference] https://www.starcharge.com/product/artemis/

[Has vendor confirmed or acknowledged the vulnerability?] true

[Discoverer] Ha Toan, Ngoc Hieu of VinFast

Use CVE-2025-52268.

