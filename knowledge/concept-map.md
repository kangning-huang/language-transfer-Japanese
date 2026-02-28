# 概念地图

一个轻量级的日语概念索引，按 JLPT 水平组织。每个条目列出前置条件并指向详细教学指导的主题文件。导师读取此文件来决定下一步教什么，与学生的 MEMORY.md 交叉参考。

注意：本课程专为中文母语者设计，充分利用汉字基础优势。

---

## N5 — 完全入门

- **kanji-bridge**: prereqs=[] → `topics/kanji-bridge.md`
  汉字桥梁：中日汉字对比，同形同义词、同形异义词、日语简化字，利用中文汉字基础快速掌握大量日语词汇

- **hiragana-katakana**: prereqs=[] → `topics/hiragana-katakana.md`
  平假名和片假名：发音、书写、记忆技巧，片假名的外来语用途

- **pronunciation**: prereqs=[hiragana-katakana] → `topics/pronunciation.md`
  日语发音：元音(あいうえお)、长音短音、促音(っ)、拨音(ん)、声调(高低音型)、与中文发音的区别

- **desu-masu**: prereqs=[hiragana-katakana] → `topics/desu-masu.md`
  です/ます基本句型：～は～です、～ます/～ません/～ました、肯定否定过去

- **particles-basic**: prereqs=[desu-masu] → `topics/particles-basic.md`
  基础助词：は(主题)、が(主语)、を(宾语)、に(目标/时间)、で(场所/手段)、の(所属)、へ(方向)

- **adjectives**: prereqs=[desu-masu] → `topics/adjectives.md`
  形容词：い形容词和な形容词、变形(否定/过去/连用)、做定语和谓语的用法

- **verb-groups**: prereqs=[desu-masu] → `topics/verb-groups.md`
  动词分类：五段动词(u-verbs)、一段动词(ru-verbs)、不规则动词(する/くる)、辞书形与ます形的关系

- **te-form**: prereqs=[verb-groups] → `topics/te-form.md`
  て形：五段动词的音便变化(い音便/っ音便/ん音便)、一段动词和不规则动词、て形的连用/请求/进行态用法

- **counters-time**: prereqs=[hiragana-katakana] → `topics/counters-time.md`
  数量词和时间：数字、常用量词(つ/人/個/枚/本/匹/杯)、时间表达(～時～分)、日期星期

- **basic-expressions**: prereqs=[] → `topics/basic-expressions.md`
  基本表达：打招呼(おはよう/こんにちは/こんばんは)、感谢道歉、自我介绍、购物餐厅常用语

## N4 — 初级

- **verb-forms**: prereqs=[verb-groups, te-form] → `topics/verb-forms.md`
  动词变形系统：ない形(否定)、た形(过去)、可能形、意志形(よう/おう)、命令形与禁止形

- **giving-receiving**: prereqs=[verb-forms] → `topics/giving-receiving.md`
  授受表达：あげる/もらう/くれる、てあげる/てもらう/てくれる、视角与恩惠关系

- **conditional**: prereqs=[verb-forms] → `topics/conditional.md`
  条件表达：たら(如果...了)、ば(假如)、と(一...就)、なら(要说...的话)、四种条件形式的区别与选择

- **keigo-intro**: prereqs=[verb-forms] → `topics/keigo-intro.md`
  敬语入门：丁寧語(です/ます)复习、基本尊敬语(お/ご～)、基本谦让语(いたします)、敬语的社会功能

- **compound-sentences**: prereqs=[te-form] → `topics/compound-sentences.md`
  复合句：原因(から/ので)、转折(けど/のに)、并列(し/たり)、目的(ために/ように)

## N3 — 中级

- **passive**: prereqs=[verb-forms] → `topics/passive.md`
  被动态：直接被动、间接被动(迷惑被动)、非生物主语被动、被动态在正式文中的使用

- **causative**: prereqs=[verb-forms] → `topics/causative.md`
  使役态：使役形的构成、让/叫/使、使役被动(させられる)、与中文"让"的对比

- **kanji-readings**: prereqs=[kanji-bridge] → `topics/kanji-readings.md`
  音读训读规律：音读与古汉语的关系、常见音读规律、训读的和语特征、熟字训、重箱读与湯桶読

- **grammar-patterns-n3**: prereqs=[compound-sentences] → `topics/grammar-patterns-n3.md`
  N3语法句型：ようにする/ようになる、ことにする/ことになる、はずだ/わけだ、ようだ/らしい/みたい

- **honorific-humble**: prereqs=[keigo-intro] → `topics/honorific-humble.md`
  尊敬语与谦让语体系：お/ご＋动词、特殊敬语动词(いらっしゃる/おっしゃる等)、谦让动词(参る/申す等)、使用场景

## N2 — 中高级

- **formal-expressions**: prereqs=[grammar-patterns-n3] → `topics/formal-expressions.md`
  书面语表达：である体、に際して/にあたって、において/における、に基づいて、を通じて

- **grammar-patterns-n2**: prereqs=[grammar-patterns-n3] → `topics/grammar-patterns-n2.md`
  N2语法句型：にもかかわらず、に反して、を問わず、に伴って、次第、かねる/かねない

- **nuance-particles**: prereqs=[particles-basic] → `topics/nuance-particles.md`
  语气助词：ね/よ/さ/ぞ/ぜ/な/わ/かな 的微妙差异、男女用语差别、地域差异

- **idiomatic-expressions**: prereqs=[kanji-readings] → `topics/idiomatic-expressions.md`
  惯用表达：体の部分を使った慣用句(目/手/足/口/頭)、四字熟语与中文成语的对比

## N1 — 高级

- **classical-remnants**: prereqs=[formal-expressions] → `topics/classical-remnants.md`
  古语残留：べし/まい/ごとし、文语助词在现代日语中的残留、公文和法律用语

- **business-japanese**: prereqs=[honorific-humble] → `topics/business-japanese.md`
  商务日语：メール/電話/会議の表現、クッション言葉、社内外の使い分け

- **regional-dialects**: prereqs=[grammar-patterns-n2] → `topics/regional-dialects.md`
  方言与地域差异：関西弁/博多弁/東北弁等的基本特征、标准语与方言的关系、流行文化中的方言
