## what is a attack
any malicious attempt to gain unauthorized access to a computer, computing system or computer network with the intent to cause damage. manly apprroach to do a cyber attack
has three terms.

- tactics
- techniques
- procedures

these three is use in miter arrack
  
 [MITRE ATT&CK](https://attack.mitre.org/)
 
`MITRE` : massachusetts institute of technology research and engineering

`ATT&CK` : Adversarial Tactics, Techniques, and Common Knowledga

- miter attack frmewowrk work in three feild ->> Enterprise ,ICS and mobile

- this is based on `TTPs` (tactics ,techniques and procedure)

- it's ceraetd by Miter ,in 2013 for know how a hacker is approaching on terget

> Miter has 14 tectics and every tectics has some tacnics and every tecnics has procedures

## tactics
the overall goal or technical objective behind attack


### 14 tactics of Miter attack
| Tactic                | Attacker(s) Objective                                       |
|-----------------------|-------------------------------------------------------------|
| 1. Reconnaissance      | Gather information they can use to plan future operations  |
| 2. Resource Development| Establish resources they can use to support operations     |
| 3. Initial Access      | Get into your network                                      |
| 4. Execution           | Run malicious code                                         |
| 5. Persistence         | Maintain their foothold                                    |
| 6. Privilege Escalation| Gain higher-level permissions                              |
| 7. Defense Evasion     | Avoid being detected                                       |
| 8. Credential Access    | Steal account names and passwords                         |
| 9. Discovery           | Figure out your environment                                |
| 10. Lateral Movement    | Move through your environment                             |
| 11. Collection         | Gather data of interest to their goal                      |
| 12. Command and Control | Communicate with compromised systems to control them      |
| 13. Exfiltration       | Steal data                                                 |
| 14. Impact             | Manipulate, interrupt, or destroy your systems and data    |


![image](https://github.com/rishabh727/cyber-security-basics/assets/143151167/e258dd66-6ea4-4758-ab16-f0b7bf62b56a)

#### how to use miter attack 
there is 14 tactics and every tactics has multiple techniques and every techniques has multiple procedures

examle: [reconnaissance](https://attack.mitre.org/tactics/TA0043) has 10 tacnics , one os them is [gather victim host information](https://attack.mitre.org/techniques/T1592) and inside it's procedures

![Screenshot 2024-03-04 090657](https://github.com/rishabh727/cyber-security-basics/assets/143151167/4061ac06-0873-46c4-9eff-9003e59dd9fb)
### Benifits of miter attack
* Intelligence,MITRE ATT&CK provides a common, standardised “language” so security personnel can understand and even predict adversary behaviors. They can then take action to defend the enterprise, and prevent attack.
* Red teamers and cyber defenders can understand adversaries, classify attacks, and assess and strengthen their organisation’s risk posture.
* The framework illustrates the actions an attacker may have taken to attack the organisation, so security teams can take immediate and relevant action to minimise the damage.
* Threat hunters can understand the various adversary techniques, proactively hunt for threats, and gauge their environment’s visibility level against targeted attacks.

[MITRE ATT&CK® Navigator](https://mitre-attack.github.io/attack-navigator/)

basically it is use to know about tectics , techniques and procedure of attacker groups (ex. APT1, APT12 ,ALLANITE) those are present.
and we can find common no. of tactics in these attacker group .



### Pyramid of pain

pyramid of pain demonstrates that some indicators of compromise are more torbing to adversaries than other
in simple words for ahacker what thing is hard to change or easy

**Hash value** : SHA1, MD5 - easy to change.

**IP Address** : asthe name suggests , but also includes netblocks - easy to change

**Domain Name** : Domain name itseif, or sub domain - simle to change

**Network Artifacts** :URL pattern - Annoying

**Host Artifacts** : file key/path - challenging

**tools**: sherlock ,Malware : too challenging

**Tactics, Techniques and Procedure** : Tough to change


![image](https://github.com/rishabh727/cyber-security-basics/assets/143151167/f4443fda-0b37-45d7-9be4-f39c23a37a22)



















  

  
  

