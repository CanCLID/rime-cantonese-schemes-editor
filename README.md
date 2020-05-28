# 中州韻粵語分歧拼音系統排版工具

**℞**: `tanxpyox/rime-cantonese-schemes-editor`

依賴於: [`rime-cantonese`](https://github.com/rime/rime-cantonese)

## 說明

* 呢個程式庫嘅schema係用嚟輸入「耶魯」、「教院」、「黃錫凌」、「劉錫祥」等嘅分歧拼音系統嘅工具。
* 只要啓用呢個程式庫入面嘅schema，**輸入正確嘅[粵拼](https://www.lshk.org/jyutping)**，選字框上面就會顯示正確嘅分歧拼音嘞。(用<kbd>Ctrl</kbd> + <kbd> Enter </kbd>就可以將選字框入面嘅字打出嚟）
* 目前支援以下嘅方案

 方案名| 檔名 | 「春眠不覺曉」
-----|------| ------
[IPA（跟機）](https://github.com/rime/rime-cantonese)| `jyut6ping3_ipa.schema.yaml` | t͡sʰɵn˥ miːn˨˩ pɐt̚˥ kɔːk̚˧ hiːu˧˥
[粵拼(1993)](https://github.com/rime/rime-cantonese)| `jyut6ping3.schema.yaml` | ceon¹ min⁴ bat¹ gok³ hiu²
耶魯(1994)| `jyut6ping3_yale_new.schema.yaml`|  cheun¹ min⁴ bat¹ gok³ hiu²
教院(1990)| `jyut6ping3_edu.schema.yaml` |  tsoen¹ min⁴ bat⁷ gok⁸ hiu²
饒秉才(1981)| `jyut6ping3_rao.schema.yaml` | cên¹ min⁴ bed¹ gog³ hiu²
劉錫祥(1977)| `jyut6ping3_lau.schema.yaml` | cheun¹ min⁴ bat¹ gok³ hiu²
耶魯(1973)| `jyut6ping3_yale.schema.yaml` | chēun mìhn bāt gok híu
黃錫凌(1941)| `jyut6ping3_wong.schema.yaml` |  ˈtseun ˌmin ˈbat ˉgok ˊhiu
Meyer-Wempe(1934)| `jyut6ping3_mw.schema.yaml` | ts‘un mīn pat kòk híu
Wisner(1906)| `jyut6ping3_wisner.schema.yaml` | ts‘un mīn pat kòk híu
Dyer-Ball(1883)| `jyut6ping3_db.schema.yaml` | <sub>⊂</sub>ts‘un <sub>⊆</sub>mín pat<sup>⊃</sup> kok° <sup>⊂</sup>híú
Eitel(1877)| `jyut6ping3_eitel.schema.yaml` | <sub>⊂</sub>ts‘un <sub>⊆</sub>mín pat<sup>⊃</sup> kok° <sup>⊂</sup>hiú
Williams(1856)| `jyut6ping3_williams.schema.yaml` | <sub>⊂</sub>ts‘un <sub>⊆</sub>mín pat<sup>⊃</sup> kok <sup>⊂</sup>hiú
[注音（國民政府）](https://github.com/tanxpyox/rime-cantonese-bpmf)| `jyut6ping3_bpmf_ng.schema.yaml` |ㄘ￥ㄣˉ ㄇㄧㄣˊ ㄅㆿㆵ˙ ㄍㄛㆶ ㄏㄧㄨˇ
[注音（人民政府）](https://github.com/tanxpyox/rime-cantonese-bpmf)| `jyut6ping3_bpmf_cpg.schema.yaml` |ㄑㆾㄋˉ ㄇㄧㄋˊ ㄅㆿㆵ˙ ㄍㄛㆻ ㄏㄧㄨˇ
