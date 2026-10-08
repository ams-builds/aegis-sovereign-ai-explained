# Jargon Buster

Simple meanings of the technical words in this project. The README uses these words only when necessary. This file explains each word exactly.

**Attestation**
A signed statement from a machine about its own state. For example, a TPM chip can sign a statement that the software on the machine is the approved software.

**Audit paradox**
The source project uses this name for a problem. If you keep raw prompts for an audit, you also keep personal data. If you do not keep them, you cannot show what occurred.

**Batch and purge**
A method in the source project. The system checks a group of prompts or outputs, makes one proof for the group, and then deletes the raw text.

**Data residency**
A rule that data must stay in a specified country or region.

**Evidence bundle**
A signed file that shows what the system checked and the result. An auditor can read it without the raw data. The source project makes it in a JSON format.

**Geofence**
A border on a map. A geofence policy permits a workload only inside the border.

**Hardware-rooted trust**
Trust that starts from a chip in the machine, not from software or from the network. Software can lie about its location. The chip is more difficult to change.

**IP address**
The network address of a machine. A service can guess a location from it. A VPN can change it, so it is not proof of location.

**Jurisdiction**
The law of a country or region that applies to data or to a company.

**Keylime**
An open-source tool that checks the TPM statements of a machine. The source project uses it to find a machine that is not in its approved state.

**Personal data (PII)**
Information that identifies a person. For example, a name, an address, or a location.

**Sovereignty**
In this guide: your control over where your data goes, which law applies to it, and your proof of these facts.

**SPIFFE and SPIRE**
Open standards and software that give each workload an identity. The source project ties this identity to the TPM chip and to the location of the machine.

**TEE (trusted execution environment)**
An area of a processor that keeps data encrypted while a program uses it. Administrators of the machine cannot read it.

**TPM (Trusted Platform Module)**
A small security chip in many computers. It keeps keys and can sign statements about the state of the machine.

**VPN (virtual private network)**
A service that sends network traffic through a different machine. It can make a machine look like it is in a different country.

**Zero-knowledge proof (ZKP)**
A proof that a statement is true without the data behind it. For example, a proof that a machine is inside a border, without its exact location.
