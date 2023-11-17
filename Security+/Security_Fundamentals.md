# General Security Concepts
1. There is an inverse correlation between security and convenience 

2. Know the difference between information security and information system security.

| Information Security | Information **System** Security |
| -------------------- | ------------------------------- |
| The concept of protecting Data | The concept of protecting The **devices** that hold the data|

3. The C.I.A. triad
   - consists of:
      - **C**onfidentiality
      - **I**ntegrity
      - **A**vailability

| Confidentiality | Integrity | Availability |
| --------------- | --------- | ------------ |
| Ensures information is only accessible to those with authorization | Ensures data remains accurate and unaltered | Ensures data or information can be reached |
| Ex. encrypted files only approved people can decrypt and read | Ex. ensuring data is not corrupted or altered when going across the wire | Ex. Ensuring a website is up and accessible to the public | 

4. Non-repudiation
    - guarantees an event that took place can be attributed 100% to a specific person and cannot be denied.
    - Ex: a signed email can not be disputed who sent it

#### note 
5. AAA of Security
   | Authentication | Authorization | Accounting | 
   | --------------| ---------------| ----------|
   | The act of verifying a person | Defines what actions or resources a user can take | The act of tracking or logging user activities |
   | Ex. presenting username and password | Ex. having permissions to create accounts but not delete accounts | browser logs |

6. Security Controls
   - Measures or Mechanisms put in place to mitigate risks and protect the confidentiality, integrity, and availability of information systems and data
   - Categories of security controls
      - Technical
      - managerial
      - operational
      - physical
   - Types of security controls
      - preventative
      - detective
      - compensating
      - deterrent
      - corrective
      - directive
   ` | Technical | Managerial | Operational | Physical | `

7. Zero Trust
   - a principle that no one should be trusted by default, verification is required by everyone regardless of position.
   - Zero trust relies on a control plane and data plane 
