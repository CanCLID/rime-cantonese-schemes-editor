# 中州韻粵語分歧拼音系統排版工具

**℞**: `tanxpyox/rime-cantonese-schemes-editor`

依賴於: [`rime-cantonese`](https://github.com/rime/rime-cantonese)

## 使用說明

* 呢個程式庫嘅schema係用嚟輸入「耶魯」、「教院」、「黃錫凌」、「劉錫祥」等嘅分歧拼音系統嘅工具。
* 只要啓用呢個程式庫入面嘅schema，**輸入正確嘅[粵拼](https://www.lshk.org/jyutping)**，選字框上面就會顯示正確嘅分歧拼音。
* 跟住用<kbd>Ctrl</kbd> + <kbd> Enter </kbd>就可以將選字框入面嘅字打出嚟嘞。

## 方案列表

 方案名| `jyut6ping3_#######.schema.yaml` | 「春眠不覺曉」
-----|------| ------
[IPA（跟機）](https://github.com/rime/rime-cantonese)| `ipa` | t͡sʰɵn˥ miːn˨˩ pɐt̚˥ kɔːk̚˧ hiːu˧˥
[粵拼(1993)](https://github.com/rime/rime-cantonese)| N/A | ceon¹ min⁴ bat¹ gok³ hiu²
耶魯(1994)| `yale_new`|  cheun¹ min⁴ bat¹ gok³ hiu²
教院(1990)| `edu` |  tsoen¹ min⁴ bat⁷ gok⁸ hiu²
饒秉才(1981)| `rao` | cên¹ min⁴ bed¹ gog³ hiu²
劉錫祥(1977)| `lau` | cheun¹ min⁴ bat¹ gok³ hiu²
耶魯(1973)| `yale` | chēun mìhn bāt gok híu
黃錫凌(1941)| `wong` |  ˈtseun ˌmin ˈbat ˉgok ˊhiu
Meyer-Wempe(1934)\*| `mw` | ts‘un mīn pat kòk híu
Wisner(1906)\*| `wisner` | ts‘un mīn pat kòk híu
Dyer-Ball(1883)\*| `db` | <sub>⊂</sub>ts‘un <sub>⊆</sub>mín pat<sup>⊃</sup> kok° <sup>⊂</sup>híú
Eitel(1877)\*| `eitel` | <sub>⊂</sub>ts‘un <sub>⊆</sub>mín pat<sup>⊃</sup> kok° <sup>⊂</sup>hiú
Williams(1856)\*| `williams` | <sub>⊂</sub>ts‘un <sub>⊆</sub>mín pat<sup>⊃</sup> kok <sup>⊂</sup>hiú
Chalmers(1855)\*| `chalmers` | ts‘un meen put kok hew （唔標調）
Bridgman(1841)\*| `bridgman` | <sub>⊂</sub>ts‘un <sub>⊆</sub>mín pat<sup>⊃</sup> kok <sup>⊂</sup>híú
Morrison(1828)\*| `morrison` | tsyn meen păt kok hew （唔標調）
[注音（國民政府）](https://github.com/tanxpyox/rime-cantonese-bpmf)| `bpmf_ng` |ㄘ￥ㄣˉ ㄇㄧㄣˊ ㄅㆿㆵ˙ ㄍㄛㆶ ㄏㄧㄨˇ
[注音（人民政府）](https://github.com/tanxpyox/rime-cantonese-bpmf)| `bpmf_cpg` |ㄑㆾㄋˉ ㄇㄧㄋˊ ㄅㆿㆵ˙ ㄍㄛㆻ ㄏㄧㄨˇ

> \* 參考：片岡新(2014)：“香港政府粵語拼音”：一個亂中有序的系統，《中國語文通訊》，93(1)，頁9-25。

## 安裝方法

* 使用[東風破](https://github.com/rime/plum)指令：
```sh
bash rime-install tanxpyox/rime-cantonese-schemes-editor
```
* 使用Windows小狼毫配置器：
  * 【輸入法設定】--> 【獲取更多輸入法檔案】
  * 輸入 `tanxpyox/rime-cantonese-schemes-editor`，拍 <kbd>Enter</kbd>
* 或者撳[呢度](https://github.com/tanxpyox/rime-cantonese-schemes-editor/archive/master.zip)下載成個程式庫，然後將啲檔案搬入去[用戶資料夾](https://github.com/rime/home/wiki/UserData#%E4%BD%8D%E7%BD%AE)度。
