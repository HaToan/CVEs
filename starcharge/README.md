## CVE-2025-52263 — Buffer Overflow in Web Configuration Module

**Description:**  
An issue in the **Web Configuration module** of *StarCharge Artemis AC Charger 7–22 kW v1.0.4* allows authenticated network-adjacent attackers to upload crafted firmware, leading to **arbitrary code execution**.

| Field | Details |
|-------|----------|
| **Vulnerability Type** | Buffer Overflow |
| **Vendor of Product** | StarCharge |
| **Affected Product Code Base** | Artemis AC Charger 7–22 kW - 1.0.4 |
| **Affected Component** | Web Config Interface |
| **Attack Type** | Remote |
| **Impact (Code Execution)** | True |
| **Attack Vectors** | Adjacent network |
| **Reference** | [https://www.starcharge.com/product/artemis/](https://www.starcharge.com/product/artemis/) |
| **Vendor Acknowledged** | True |
| **Discoverer** | Hà Toàn, Tống Thế Bảo (VinFast) |
| **Fixed in** | 1.6 |

---

## CVE-2025-52264 — Stack Overflow in `download.cgi`

**Description:**  
*StarCharge Artemis AC Charger 7–22 kW v1.0.4* contains a **stack overflow vulnerability** in the `cgiMain` function of `download.cgi`, triggered by using the **Content-Length** value as the buffer size. This can lead to **arbitrary code execution**.

| Field | Details |
|-------|----------|
| **Vulnerability Type** | Buffer Overflow |
| **Vendor of Product** | StarCharge |
| **Affected Product Code Base** | Artemis AC Charger 7–22 kW - 1.0.4 |
| **Affected Component** | CGI Interface |
| **Attack Type** | Remote |
| **Impact (Code Execution)** | True |
| **Attack Vectors** | Network-adjacent |
| **Reference** | [https://www.starcharge.com/product/artemis/](https://www.starcharge.com/product/artemis/) |
| **Vendor Acknowledged** | True |
| **Discoverer** | Hà Toàn, Trần Văn Quắc (VinFast) |
| **Fixed in** | 1.6 |

---

## CVE-2025-52268 — Hardcoded AES Key in Web Configuration Interface

**Description:**  
*StarCharge Artemis AC Charger 7–22 kW v1.0.4* was discovered to contain a **hardcoded AES key**, allowing attackers to **forge or decrypt valid login tokens**, leading to **authentication bypass** and potential **privilege escalation**.

| Field | Details |
|-------|----------|
| **Vulnerability Type** | Hard-coded Cryptographic Key |
| **Vendor of Product** | StarCharge |
| **Affected Product Code Base** | Artemis AC Charger 7–22 kW - 1.0.4 |
| **Affected Component** | WebConfig Interface |
| **Attack Type** | Remote |
| **Impact (Escalation of Privileges)** | True |
| **CVE Impact (Other)** | Authentication bypass |
| **Attack Vectors** | Network-adjacent |
| **Reference** | [https://www.starcharge.com/product/artemis/](https://www.starcharge.com/product/artemis/) |
| **Vendor Acknowledged** | True |
| **Discoverer** | Hà Toàn, Ngọc Hiếu (VinFast) |
| **Fixed in** | 1.6 |
