| [简体中文](https://github.com/NobyDa/ND-AD/blob/master/README.md) | [English](https://github.com/NobyDa/ND-AD/blob/master/README_en_US.md) | 
| - | - |

## File related instructions：

| File name              | Include projects                               | Synopsis                          | Surge grammar |
| ---------------------- | -----------------------------------------------|-----------------------------------|---------------|
| **AD_Block.txt**       | [@ACL4SSR](https://github.com/ACL4SSR/ACL4SSR) [@anti-AD](https://github.com/privacy-protection-tools/anti-AD) [@ConnersHua](https://github.com/ConnersHua) [@lhie1](https://github.com/lhie1/Rules) [@Scomper](https://github.com/scomper) |More than 40K ad rules. Block common application ads, privacy tracking, behavior analysis, data statistics, flow statistics, web page hijacking                                                                                | DOMAIN-SET    |
| **AD_Block_Add.txt**   | [@ACL4SSR](https://github.com/ACL4SSR/ACL4SSR) [@Scomper](https://github.com/scomper) [@ConnersHua](https://github.com/ConnersHua) [@lhie1](https://github.com/lhie1/Rules)   |Ad alliance keywords and IP-CIDR blocking, it recommended to use with "AD_Block.txt".  but "AD_Block.txt" in QX format already contains this rule                       | RULE-SET      |
| **AD_Block_Plus.txt**  | Unknown                                        | More than 60K domestic and foreign ad rules. Can be used with "AD_Block.txt", **but there may be some normal URL blocked, please use with caution.**              | DOMAIN-SET    |

### Rule remarks :

* **QX users: Only recommended to use this project rule in QX 1.0.8 (273) and above, if lower than this version, it may crash due to too many rules**
* **Surge users: DOMAIN-SET Ruleset is only available in Surge 4.2.2 and above.**
* **Loon users: The Quantumult X format rules for this project can be used directly on Loon.**
* **Among them, "AD_Block.txt" is China's ad rules. overseas users may not applicable**
* **These rules only include ads. Please choose REJECT for the policy**
* **Self-use only, Update depend on mood, if you have any questions, please submit a Issues or pull request.**

---

### Special thanks：
* [@ACL4SSR](https://github.com/ACL4SSR/ACL4SSR)
* [@anti-AD](https://github.com/privacy-protection-tools/anti-AD)
* [@ConnersHua](https://github.com/ConnersHua)
* [@lhie1](https://github.com/lhie1/Rules)
* [@neohosts](https://github.com/neoFelhz/neohosts)
* [@Scomper](https://github.com/scomper)
* [@yhosts](https://github.com/vokins/yhosts)