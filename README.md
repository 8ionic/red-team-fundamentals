# Red-Team Fundamentals

### Red-Team Learning Path:

- [https://tryhackme.com/room/jrsecanalystintrouxo](https://tryhackme.com/room/jrsecanalystintrouxo)
- [https://tryhackme.com/paths](https://tryhackme.com/paths)
- [https://tryhackme.com/room/commonattacks](https://tryhackme.com/room/commonattacks)
- [https://tryhackme.com/room/wazuhct](https://tryhackme.com/room/wazuhct)

# Red-Team

- real thread actor

## What they do?

- Vulnerability Assessment
- detecting
- responding
- simulate real attack techniques to test the reaction capabilities of a defending team (blue team)
- do everything they can to achieve the goals while remaining undetected and evading any existing security mechanisms like firewalls, antivirus, EDR, IPS
- emulating a real threat actor's **Tactics, Techniques and Procedures (TTPs)**
- simulate enough TTPs for the blue team to learn to react to a real ongoing threat adequately
- eventually help improve their detection capabilities

## How?

- start with defining clear goals (crown jewels or flags)
- range: from compromising a given critical host to stealing some sensitive information from the target
- do not inform blue-team about the exercise to pretend normal behavior

## **ATT&CK-Framework**

[MITRE ATT&CK®](https://attack.mitre.org/)

- **Tactics** are the tactical goals a threat may use during an operation.
- **Techniques** describe the actions threats take to achieve their objectives.
- **Procedures** are the technical steps required to perform the action.

## Threats

- **Technical Infrastructure:** Like in a regular penetration test, a red team will try to uncover technical vulnerabilities, with a much higher emphasis on stealth and evasion.
- **Social Engineering:** Targeting people through phishing campaigns, phone calls or social media to trick them into revealing information that should be private.
- **Physical Intrusion:** Using techniques like lockpicking, RFID cloning, exploiting weaknesses in electronic access control devices to access restricted areas of facilities.

### Multiple-ways

- **Full Engagement:** Simulate an attacker's full workflow, from initial compromise until final goals have been achieved.
- **Assumed Breach:** Start by assuming the attacker has already gained control over some assets, and try to achieve the goals from there. As an example, the red team could receive access to some user's credentials or even a workstation in the internal network.
- **Table-top Exercise:** An over the table simulation where scenarios are discussed between the red and blue teams to evaluate how they would theoretically respond to certain threats. Ideal for situations where doing live simulations might be complicated.

### Keywords

**APT:** **A**dvancend **P**ersistent **T**hreat

- persistent because the operations of these groups can remain undetected for long periods

**C2 or C&C: C**ommand and **C**ontroll

- remote code execution

### Definitions:

[Red Team Development and Operations](https://redteam.guide/docs/definitions/)

## Repos

[https://github.com/8ionic/red-team-engagement/](https://github.com/8ionic/red-team-engagement/)

## Links

[TryHackMe | Red Team Fundamentals](https://tryhackme.com/room/redteamfundamentals)

[TryHackMe | Cyber Security Training](https://tryhackme.com/jr/redteamrecon)

[Red-Team Engagement-Information](https://www.notion.so/Red-Team-Engagement-Information-2b2eb9e380144e71bf9b3dc1494e8f46)
