<div lang="yue-HK">

# 中州韻粵語分歧拼音系統排版工具

**℞**: `CanCLID/rime-cantonese-schemes-editor`

依賴於：[`rime-cantonese`](https://github.com/rime/rime-cantonese)

## 使用說明

* 呢個程式庫嘅 schema 係用嚟輸入「耶魯」、「教院」、「黃錫凌」、「劉錫祥」等嘅分歧拼音系統嘅工具。
* 只要啓用呢個程式庫入面嘅 schema，**輸入正確嘅[粵拼](https://www.lshk.org/jyutping)**，選字框上面就會顯示正確嘅分歧拼音。
* 跟住用 <kbd>Ctrl</kbd> + <kbd>Enter</kbd> 就可以將選字框入面嘅字打出嚟嘞。

###### 註：因為粵拼以外嘅大多數方案都唔支援 a 同 oet，佢哋會事先被分別轉換成 aa 同 eot。

## 方案列表

|方案名（逆時序）|發表年份| 檔名 | 示例：「春眠不覺曉」|
|----- | :------: | :-----: | ------|
|[IPA](https://github.com/rime/rime-cantonese)| - | `ipa` | t͡sʰɵn˥ miːn˨˩ pɐt̚˥ kɔːk̚˧ hiːu̯˧˥|
|新法蘭西|2009| `nf`|  tsœ̈n꜒ min꜖ bät꜒ gok꜔ hiu꜖꜒|
|耶魯（修訂）|1994| `yale_new`|  cheun¹ min⁴ bat¹ gok³ hiu²|
|**[粵拼](https://github.com/rime/rime-cantonese)**|**1993**| - | **ceon1 min4 bat1 gok3 hiu2**|
|教院 |1990| `edu` |  tsoen¹ min⁴ bat⁷ gok⁸ hiu²|
|饒秉才 |1981| `rao` | cên¹ min⁴ bed¹ gog³ hiu²|
|劉錫祥 |1977| `lau` | cheun¹ min⁴ bat¹ gok³ hiu²|
|耶魯 |1973| `yale` | chēun mìhn bāt gok híu|
|[注音（人民政府）](https://github.com/CanCLID/rime-cantonese-bpmf)|1950| `bpmf_cpg` |ㄑㆾㄋˉ ㄇㄧㄋˊ ㄅㆿㆵ˙ ㄍㄛㆻ ㄏㄧㄨˇ|
|Barnett-Chao（趙元任）|1947| `bc` | tson min pat koak xio|
|黃錫凌羅馬拼音 |1941| `wong` |  ˈtseun ˌmin ˈbat ˉgok ˊhiu|
|寬式國際音標 |1941| `wong_ipa` | ˈtsœn ˌmin ˈbɐt ˉgɔk ˊhiu|
|Meyer-Wempe\* |1934| `mw` | ts‘un mīn pat kòk híu|
|[注音（國民政府）](https://github.com/CanCLID/rime-cantonese-bpmf) |1932| `bpmf_ng` |ㄘ￥ㄣˉ ㄇㄧㄣˊ ㄅㆿㆵ˙ ㄍㄛㆶ ㄏㄧㄨˇ|
|Wisner\* |1906| `wisner` | ts‘un mīn pat kòk híu|
|Dyer-Ball\*† |1883| `db` | ꜀ts‘un ꜁mín pat꜆ kok° ꜂híú|
|Eitel\*† |1877| `eitel` | ꜀ts‘un ꜁min pat꜆ kok° ꜂hiú|
|Williams\*† |1856| `williams` | ꜀ts‘un ꜁mín pat꜆ kok ꜂hiú|
|Chalmers\* |1855| `chalmers` | ts‘un meen put kok hew （唔標調）|
|Bridgman\*† |1841| `bridgman` | ꜀ts‘un ꜁mín pat꜆ kok ꜂híú|
|Morrison\* |1828| `morrison` | tsun meen păt kok hew （唔標調）|

###### \* 參考：片岡新(2014)：[“香港政府粵語拼音”：一個亂中有序的系統](https://www.cuhk.edu.hk/ics/clrc/crcl_93_1/kataoka.pdf)，《中國語文通訊》，93(1)，頁9-25。<br><br>† 需要支援 `U+A70X MODIFIER LETTER CHINESE TONE XXX` 嘅字體。

## 安裝方法

* 使用[東風破](https://github.com/rime/plum)指令：
```sh
bash rime-install CanCLID/rime-cantonese-schemes-editor
```
* 使用 Windows 小狼毫配置器：
  * 【輸入法設定】→【獲取更多輸入法檔案】
  * 輸入 `CanCLID/rime-cantonese-schemes-editor`，撳 <kbd>Enter</kbd>
* 或者撳[呢度](https://github.com/CanCLID/rime-cantonese-schemes-editor/archive/master.zip)下載成個程式庫，然後將啲檔案搬入去[用戶資料夾](https://github.com/rime/home/wiki/UserData#%E4%BD%8D%E7%BD%AE)度。

</div>
