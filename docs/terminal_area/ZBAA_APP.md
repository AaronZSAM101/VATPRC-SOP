# 北京终端区标准运行程序

## 1. 通则
### 1.1 依据
本文是依据中国民用航空局(CAAC)发布的AIP，结合VATPRC实际运行场景编制适用于北京终端区的标准运行程序。管制员上线时需遵守VATSIM Code of Conduct (CoC)，并积极与上下级管制员协调以达成一致认知。

### 1.2 适用范围
本文适用范围是VATPRC管辖内北京进近(ZBAA_APP)，主要服务机场包括北京首都(ZBAA)、北京大兴(ZBAD)，按需服务机场包括天津滨海(ZBTJ)。
**本文严禁用于真实运行。**

## 2. 运行信息
### 2.1 服务空域
<img width="500" alt="16254CAA-B2AE-4578-AFB0-AC1C308BD729" src="https://github.com/user-attachments/assets/3aa423fe-d635-48cb-b7d4-56f35864b19d">

### 2.2 主要服务机场运行规则
#### 2.2.1 北京首都
北京首都国际机场在非低能见度运行的标准情况下，可按下列建议运行，但以机场管制员的运行需求为准:
- 北向运行时，跑道36L用于落地和起飞，跑道36R用于起飞，跑道01用于落地和起飞。跑道36L和01可以实施独立平行进近。
- 南向运行时，跑道18R主要用于落地，跑道18L主要用于起飞，跑道19用于落地和起飞。任意两条平行可以实施相关平行进近，**不可以实施独立平行进近。**
- 原则上不执行宵禁模拟。

#### 2.2.2 北京大兴
北京大兴国际机场在非低能见度运行的标准情况下，可按下列建议运行，但以机场管制员的运行需求为准:
- 北向运行时，跑道35L、跑道01L用于落地，跑道35R、跑道11L用于起飞。跑道35L和01L可以用于独立平行进近。
- 南向运行时，跑道17R、跑道19R用于落地，跑道17L、跑道11L用于起飞。跑道17R和19R可以用于独立平行进近。

### 2.3 按需服务机场运行规则
#### 2.3.1 天津滨海
天津滨海国际机场在非低能见度运行的标准情况下，可按下列建议运行，但以机场管制员的运行需求为准:
- 北向运行时，跑道34L用于起飞，跑道34R用于落地。
- 南向运行时，跑道16R用于起飞，跑道16L用于落地。

## 3. 席位划分
### 3.1 合扇
|登录名|呼号|频率|职责范围|
|:---:|:---:|:---:|:---:|
|ZBAA_APP|北京进近|120.600|北京终端区全扇*|

*当未设立任何分扇时，本席位管制整个北京终端区(含天津进近及机场管制区，可按需放弃机场管制区)。当设立任意分扇时，本席位需按分扇移交方式与分扇移交。移交方式可快速参考附录B的扇区移交示意图，但以下述表格划分为准。

#### 3.1.1 总则
在进近各扇区移交时，扇区之间的管制移交以高度移交和交接点移交相结合，管制移交必须在管制移交点前15公里至5公里或垂直间隔在到达移交高度前300米至0米之间，无法满足时应当提前协调接收单位。向同一扇区移交的航班，同高度顺向水平间隔不小于15公里，并确保无追赶，且确认与本扇区其他航班无冲突后，方可实施移交。航空器完成移交后，接受单位应当尽早指挥航空器脱离移交高度。

在进近各扇区内(除天津进近使用天津滨海机场修正海平面气压)，3000米(含)以下高度表拨正值统一使用终端区修正海平面气压(即首都机场修正海平面气压)。大兴起降航班仅在大兴塔台管制空域内使用大兴机场修正海平面气压。
   
**扇区划分及移交示意图，请见另外公布的《北京终端区分扇示意图》。**

### 3.2 首都低扇
#### 3.2.1 席位概况
|登录名|呼号|频率|职责范围|
|:---:|:---:|:---:|:---:|
|ZBAA_F_APP|首都进近|126.100|首都机场最终进场和初始离场调配。*|

*本扇区在雷达引导时，需注意避让空中禁区【ZB(P)801】以及禁止绕飞区，详细内容请参见AIP ENR2.2.2.2与北京首都机场的标准仪表程序图。

#### 3.2.2 移交协议
(1) 进扇区
|航线|程序|移交位置|移交高度/百米|上级席位|
|:---:|:---:|:---:|:---:|:---:|
|首都进港 (北向)|**AVBOX-9ZA DUGEB-9ZA** GUVBA-9YA*|AA441|24|高扇|
|首都进港 (北向)|**DUMAP-9ZA OSUBA-9ZA GUVBA-9ZA**|AA422|21|高扇|
|大兴进港 (北向)|**BUMDU-01A**|AD623以北尽早|24|高扇|
|首都进港 (南向)**|**DUGEB-8ZA** DUGEB-8YA **GUVBA-8ZA**|AA582|27|高扇|
|首都进港 (南向)|**AVBOX-8ZA DUMAP-8ZA**|AA543|24|高扇|
|首都进港 (南向)|**OSUBA-8ZA**|AA524以南尽早|24|高扇|
|大兴进港 (南向)|**BUMDU-11A**|AD724以南尽早|21|高扇|

*被加粗的程序为常用程序，否则为不常用程序，需协调使用，下同。

**PMS程序(DUGEB-8XA、GUVBA-8YA)不包含在此表格中，如需使用请当班管制员自行协调移交点及高度。

(2) 出扇区
|航线|离场/进场点|移交位置|移交高度/百米|下级席位|
|:---:|:---:|:---:|:---:|:---:|
|首都出港 (北向)*|**IDKEX/DOTRA/** LULTA/MUGLO/IGMOR**|AA411前(满足高度即可移交)|21|高扇|
|首都出港 (北向)|**MUGLO/IGMOR/ELKUR/RUSDO/BOTPU**|AA451/431前(满足高度即可移交)|27|高扇|
|大兴进港 (北向)|**BUMDU**|AD622|21|大兴低扇|
|首都出港 (南向)|**MUGLO/IGMOR/ELKUR/RUSDO**|AA532|27|高扇|
|首都出港 (南向)|**RUSDO/BOTPU**|AA572|27|高扇|
|首都出港 (南向)|**IDKEX/DOTRA/BOTPU/** LULTA/MUGLO/IGMOR|AA513前(满足高度即可移交)|21|高扇|
|大兴进港 (南向)|**BUMDU**|AD723后|18***|大兴低扇|

*需注意的是，首都36R跑道离港默认保持跑道航迹，如无需此项需与塔台管制员协调。

**被加粗的离场点为常用离场点或使用了常用离场程序，否则为不常用离场点或使用了不常用离场程序，需要视情与区域管制员协调使用。

***该移交高度是为了和南侧进港的机组错开高度，AD722有1200米以下的程序限高，因此需尽早交由大兴低扇处理。

### 3.3 大兴低扇
#### 3.3.1 席位概况
|登录名|呼号|频率|职责范围|
|:---:|:---:|:---:|:---:|
|ZBAD_APP|大兴进近|126.500|大兴机场最终进场和初始离场调配。*|

*请注意，大兴低扇使用首都机场修正海平面气压。首次与出港机组建立联系时，请主动告知修正海平面气压。

#### 3.3.2 移交协议
(1) 进扇区
|航线|程序|移交位置|移交高度/百米|上级席位|
|:---:|:---:|:---:|:---:|:---:|
|大兴进港 (北向)|AVBOX-01A AVBOX-02A|AD645|24|高扇|
|大兴进港 (北向)|BELAX-01A|AD661|15|高扇|
|大兴进港 (北向)|ELAPU-01A|AD682|21|高扇|
|大兴进港 (北向)|BUMDU-01A|AD622|21|首都低扇|
|大兴进港 (北向)|DUMAP-01A|AD642|18|天津进近|
|大兴进港 (南向)|DUMAP-11A|AD742|18|天津进近|
|大兴进港 (南向)|AVBOX-11A|AD742|21|高扇|
|大兴进港 (南向)|BUMDU-11A|AD723后|18*|首都低扇|
|大兴进港 (南向)|ELAPU-11A|AD783|27**|高扇|
|大兴进港 (南向)|BELAX-11A|AD783|24|高扇|

*AD722有1200米以下的程序限高，需尽快下高。同时请注意南侧进港的交通冲突。

**因与PEGSO离场有冲突，且需要和南侧进港的交通错开，因此此高度超过大兴低扇的的垂直边界。

(2) 出扇区
|航线|离场/进场点|移交位置|移交高度/百米|下级席位|
|:---:|:---:|:---:|:---:|:---:|
|大兴出港 (北向)|DOTRA/IDKEX|AD612|15|高扇|
|大兴出港 (北向)|PEGSO/OMDEK|AD653前|24|高扇|
|大兴出港 (北向)|MUGLO/ELKUR|AD633|21|天津进近|
|大兴出港 (南向)|IDKEX/DOTRA|AD712|15|高扇|
|大兴出港 (南向)|PEGSO|AD772|24|高扇|
|大兴出港 (南向)|OMDEK|AD752/AD754|24|高扇|
|大兴出港 (南向)|ELKUR/MUGLO|AD733|21|天津进近|

### 3.4 天津进近
#### 3.4.1 席位概况
|登录名|呼号|频率|职责范围|
|:---:|:---:|:---:|:---:|
|ZBTJ_APP|天津进近|127.900|天津终端区及大兴机场部分初始离场调配。*|

*请注意，天津进近使用天津滨海机场修正海平面气压。首次与大兴出港机组建立联系时请主动告知修正海平面气压。

#### 3.4.2 移交协议
(1) 进扇区
|航线|程序|移交位置|移交高度/百米|上级席位|
|:---:|:---:|:---:|:---:|:---:|
|天津进港|AVBOX/DUMAP*|AVBOX DUMAP|27|北京区域|
|天津进港|GUVBA|TJ988/TJ867|42|高扇|
|大兴离港|ELKUR-01D ELKUR-02D MUGLO-01D MUGLO-02D|AD633|21|大兴低扇|
|大兴离港|ELKUR-11D MUGLO-11D|AD733|21|大兴低扇|
|大兴进港**|DUMAP-01A DUMAP-11A|DUMAP|39|北京区域|

*天津进港使用的程序由天津进近当班管制员决定，并告知相关管制员。

**天津进近需询问负责大兴低扇的管制员大兴的运行方向，以便决定使用何种程序。

(2) 出扇区
|航线|离场/进场点|移交位置|移交高度/百米|下级席位|
|:---:|:---:|:---:|:---:|:---:|
|天津离港|MUGLO|MUGLO|27|北京区域|
|天津离港|IGMOR|IGMOR|30|北京区域|
|天津离港|ELKUR|ELKUR|45|北京区域|
|天津离港|OMDEK/PEGSO|ELKUR|45|高扇|
|天津离港|BOTPU/IDKEX|TJ837|39|高扇|
|大兴离港|ELKUR/MUGLO|ELKUR/MUGLO|45|北京区域|
|大兴进港|DUMAP|AD642|18|大兴低扇|

### 3.5 高扇
#### 3.5.1 席位概况
|登录名|呼号|频率|职责范围|
|:---:|:---:|:---:|:---:|
|ZBAA_APP|北京进近|120.600|北京终端区进场初始调配，离场最终调配。*|

*本扇和合扇登录名/频率完全一致，仅用于表示移交情况。如没有任何低扇启用，则职责和合扇一致。

#### 3.5.2 移交协议
(1) 进扇区
|移交点*|航线|移交高度/百米|上级席位|
|:---:|:---:|:---:|:---:|
|DUGEB|首都进港|51|北京区调|
|AVBOX|首都进港|51|北京区调|
|DUMAP|首都进港|51|北京区调|
|GUVBA|首都进港|45|北京区调|
|OSUBA|首都进港|39|北京区调|
|AVBOX|大兴进港|39|北京区调|
|BELAX|大兴进港|39|北京区调|
|ELAPU|大兴进港|39|北京区调|
|DUMAP|大兴进港|39|北京区调|
|BUMDU|大兴进港|48|北京区调|
|GUVBA|天津进港|60|北京区调|

*高扇发布的进场程序，请参考各低扇的进扇区表格。不含首都和大兴低扇进离港移交，请参见相关低扇的”进扇区“、“出扇区”表格。

(2) 出扇区
|移交点*|航线**|移交高度/百米|下一席位|
|:---:|:---:|:---:|:---:|
|TJ988/TJ867|天津进港|42|天津进近***|
|BOTPU|首都离港|60|北京区域|
|DOTRA|首都离港|60|北京区域|
|ELKUR|首都离港|60|北京区域|
|IDKEX|首都离港|60|北京区域|
|IGMOR|首都离港|60|北京区域|
|LULTA|首都离港|24|北京区域|
|MUGLO|首都离港|60|北京区域|
|RUSDO|首都离港|60|北京区域|
|IDKEX|大兴离港|60|北京区域|
|DOTRA|大兴离港|60|北京区域|
|PEGSO|大兴离港|45|北京区域|
|OMDEK|大兴离港|45|北京区域|
|ELKUR|大兴离港|45|北京区域|
|MUGLO|大兴离港|45|北京区域|
|OMDEK|天津离港|45+****|北京区域|
|PEGSO|天津离港|45+|北京区域|
|BOTPU|天津离港|60|北京区域|
|IDKEX|天津离港|60|北京区域|

*首都机场离场程序请参考首都机场SOP，大兴机场离场程序因与跑道绑定，故不再赘述。天津机场离场程序由当班管制员自行决策。

**各机场进港移交方式，请参考各低扇的”进扇区“表格。

***仅在GUVBA进港且天津进近在线时适用。

****此处表示任意高于4500米的高度，由高扇与北京区域协调决定。下同。