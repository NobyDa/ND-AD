| [简体中文](https://github.com/NobyDa/ND-AD/blob/master/README.md) | [English](https://github.com/NobyDa/ND-AD/blob/master/README_en_US.md) | 
| - | - |

## 说明：

|  规则文件名                 | 包括的开源项目                                   | 简介                              | Surge语法      |
| ---------------------- | -----------------------------------------------|-----------------------------------|---------------|
| **AD_Block.txt**       | [@ACL4SSR](https://github.com/ACL4SSR/ACL4SSR) [@anti-AD](https://github.com/privacy-protection-tools/anti-AD) [@ConnersHua](https://github.com/ConnersHua) [@lhie1](https://github.com/lhie1/Rules) [@Scomper](https://github.com/scomper) |超过4万条广告规则, 阻止常见的APP广告/隐私/行为/数据/流量/劫持的统计和追踪.                                  | DOMAIN-SET    |
| **AD_Block_Add.txt**   | [@ACL4SSR](https://github.com/ACL4SSR/ACL4SSR) [@Scomper](https://github.com/scomper) [@ConnersHua](https://github.com/ConnersHua) [@lhie1](https://github.com/lhie1/Rules)        | 阻止广告联盟关键字和IP段, 建议和"AD_Block.txt"一起使用.  QX格式"AD_Block.txt"已包含该规则.                                                                   | RULE-SET      |
| **AD_Block_Plus.txt**  | 未知                                            | 超过6万条国内外广告规则, 可以与"AD_Block.txt"一起使用, **注: 可能有一些误杀, 请谨慎使用.**                                                                                 | DOMAIN-SET    |

### 补充 :

* **QX 注: 仅建议在QX 1.0.8(273)及以上版本使用, 低于此版本可能会规则过多导致崩溃.**
* **Surge 注: 仅Surge(4.2.2)及以上版本可用DOMAIN-SET规则集.**
* **Loon 注: 本项目QX格式规则兼容Loon, 直接使用即可.**
* **其中"AD_Block.txt"内, 大部分为中国广告规则, 海外用户可能不适用.**
* **该类规则仅包含去广告规则。 请为策略选择REJECT.**
* **自用，佛系更新，如果规则有任何问题与误杀，欢迎提交issues或pull request.**

---

### 鸣谢：
* [@ACL4SSR](https://github.com/ACL4SSR/ACL4SSR)
* [@anti-AD](https://github.com/privacy-protection-tools/anti-AD)
* [@ConnersHua](https://github.com/ConnersHua)
* [@lhie1](https://github.com/lhie1/Rules)
* [@neohosts](https://github.com/neoFelhz/neohosts)
* [@Scomper](https://github.com/scomper)
* [@yhosts](https://github.com/vokins/yhosts)