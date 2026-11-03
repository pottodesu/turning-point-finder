# 出力の例:核融合発電

turning-point-finder に「核融合発電」を入れて得た出力です。

- 実行日:2026-11-03
- スキルの版:壁の版
- 実行条件:メモリをオフにした新しい会話
- 注意:出力をそのまま載せています。内容の正しさは保証しません。非査読の資料や換算値も含みます。スキルを直すたびに、出力は変わります。

## 主目的

燃料の制約なしに、炭素を出さない大量の電力を昼夜・天候に関係なく作ること

## 性質

重水素とリチウムが原料で海水から実質無尽蔵に得られる、CO2を出さない、出力が天候・季節・昼夜に左右されない、燃料の輸送・備蓄がほぼ要らない、立地が鉱山や日照・風況に縛られない、単位燃料あたりのエネルギーが化石燃料の約数百万倍、1億度級のプラズマを扱う、炉壁から数百〜千度級の高温熱が取れる、14MeVの高速中性子を大量に出す、中性子でリチウムからトリチウムを作る(自己増殖)、高レベルの長寿命廃棄物をほぼ出さない、暴走しにくく止めれば止まる、強力な超電導磁石技術が育つ、極低温技術が育つ、耐放射線材料が育つ、ヘリウムが副産物として出る、中性子で物質を変換できる、比推力の高い推進に転用できる、出力を高い密度で一か所に集められる、エネルギー供給国と輸入国の区別が薄れる、電力単価の上限が燃料費ではなく設備費で決まる

## 上限

- 農業:農地面積・日照・降水量
- 水:降水量・地下水量・河川の量
- 食料:光合成効率・作付け期間
- エネルギー:化石燃料埋蔵量・日照・風況
- 化学工業:化石由来の水素・炭素原料の量
- 環境:大気中CO2量(残余カーボンバジェット)
- 資源:陸上鉱床の埋蔵量・鉱石品位
- 医療:医療用同位体の生産炉数
- 廃棄物:長寿命核種の減衰時間
- 宇宙:化学ロケットの比推力・移動日数
- 交通:液体燃料の埋蔵量
- 住宅:居住可能地の水・気候条件
- 災害:干ばつ時の水量
- 軍事:燃料補給線の長さ

## 有力

**人工光と電力→日照・農地面積の壁→「食料は土地と太陽の量で決まる」が当たり前でなくなる**

- 点検:垂直農場の収量は露地の約20倍超、小麦の理論上限は露地の約600倍。ただし米国小麦を屋内で作ると米国全電力の約8倍
- 成立条件:光合成効率の上限(作物で1〜2%)は越えられないため、主食は国の総発電量級の電力が要る
- 出典:[Plantae(PNAS紹介)](https://plantae.org/wheat-yield-potential-in-controlled-environment-vertical-farms-proc-natl-acad-sci-usa/)、[Gizmodo](https://gizmodo.com/vertical-farms-could-grow-all-the-wheat-we-need-but-at-1844521193)、[arXiv](https://arxiv.org/pdf/2405.09643)、[Wikipedia](https://en.wikipedia.org/wiki/Photosynthetic_efficiency)

**電力と逆浸透膜→降水量・地下水の壁→「使える水は雨の量で決まる」が当たり前でなくなる**

- 点検:実用2.5〜5kWh/m³、理論最小約0.6kWh/m³。世界の取水を全量賄うと約1.16万TWh/年で、現在の発電量の約3分の1
- 成立条件:濃縮塩水の排出処理と内陸への揚水(1000m揚程で約2.7kWh/m³)の電力が別に要る
- 出典:[WaterWorld](https://www.waterworld.com/drinking-water-treatment/potable-water-quality/article/16200772/economics-of-desalination-reducing-costs-by-lowering-energy-use)、[IRENA](https://www.irena.org/-/media/Files/IRENA/Agency/Publication/2012/IRENA-ETSAP-Tech-Brief-I12-Water-Desalination.pdf)、[weltagrarbericht](https://www.weltagrarbericht.de/wp-content/uploads/2016WorldData-Withdrawal_eng.pdf)、[CleanTechnica](https://cleantechnica.com/2019/01/17/humans-worth-their-salt-the-price-of-desalination-brine-disposal/)

**電力と高温熱→化石燃料埋蔵量の壁→「燃料と肥料は地下から掘るもの」が当たり前でなくなる**

- 点検:水電解は実用50〜53kWh/kg(理論約33)。アンモニアの水素は今は主に天然ガス由来。電力から液体燃料への効率は約28〜44%
- 成立条件:直接電化の最大5倍の電力を食うため、燃料を電力量の上限が決める構図に変わるだけ
- 出典:[Wikipedia(水電解)](https://en.wikipedia.org/wiki/Water_electrolysis)、[Wikipedia(ハーバー法)](https://en.wikipedia.org/wiki/Haber_process)、[Strathprints](https://strathprints.strath.ac.uk/85603/7/Atsonios_etal_Energy_2023_Process_analysis_and_comparative_assessment_of_advanced_thermochemical_pathways_for_e_kerosene.pdf)、[Fraunhofer ISI](https://www.isi.fraunhofer.de/en/presse/2023/presseinfo-05-efuels-nicht-sinnvoll-fuer-pkw-und-lkw.html)

**炭素なしの熱・電力→大気中CO2の壁→「出したCO2は戻せない」が当たり前でなくなる**

- 点検:理論最小約0.43GJ/t、実用は5〜9GJ/t。年10Gt回収で約2,800〜2万TWh/年
- 成
