# 검 강화 — 플레이스토어 등록 정보 (14개 언어)

앱: 검 강화 / Sword Forge · 패키지 `com.geomgang.game`

플레이 콘솔 [기본 스토어 등록정보]에서 언어를 추가하며 그대로 붙여 넣는다.
**이 파일 하나로 끝나도록** 한국어 본문까지 여기에 두었다 — 앱 소스 저장소는
비공개가 될 수 있으니, 출시에 필요한 것은 이 저장소 안에 있어야 한다.

## 스토어에 넣을 링크

| 칸 | 주소 |
|---|---|
| 개인정보처리방침 | `https://yongminlee2.github.io/legal/swordforge/privacy.html` |
| 웹사이트 | `https://yongminlee2.github.io/legal/swordforge/` |
| 지원 | `https://yongminlee2.github.io/legal/swordforge/support.html` |

## 잊지 말 것

- 데이터 보안 신고에서 **수집·공유 항목을 하나도 체크하지 않는다.**
  인터넷 권한이 없어 기기 밖으로 보낼 방법 자체가 없다.
- 진동 권한(`VIBRATE`) 하나만 쓴다. 권한 목록에 그것만 뜬다.

**글자 수 제한** — 앱 이름 30자, 짧은 설명 80자, 자세한 설명 4000자.
공백도 한 자로 센다. 아래 문구는 전부 제한 안에 들어가는 것을 확인했다
(`python check-store-listing.py`).

**언어 코드** — 콘솔에서 고를 이름은 다음과 같다.
한국어 / English (United States) / 日本語 / 中文(简体) / 中文(繁體) /
中文(香港) / Español (España) / Français (France) / Deutsch /
Português (Brasil) / Русский / Tiếng Việt / Bahasa Indonesia / ไทย

---

## 한국어 (ko)

**앱 이름**
```
검 강화 — 검 키우기
```
**짧은 설명**
```
검을 강화해서 올립니다. 부서지면 되살릴지 조각을 챙길지 그 자리에서 고릅니다.
```
**자세한 설명**
```
검 한 자루를 계속 강화하는 게임입니다.

■ 강화 — 올리거나, 내려가거나, 부서지거나
성공하면 +1. +5까지는 실패해도 검이 그대로지만, 그 위부터는 한 단계 내려갑니다.
+10부터는 부서질 수 있습니다.
부서진 그 순간 고릅니다 — 검을 되살릴지, 조각을 챙길지. 시간이 지나면 둘 다 놓칩니다.

■ 일곱 계열 — 강화해서 넘어간다
직검·곡도·대검·세검으로 시작합니다. 곡도는 +10을 찍으면, 대검은 검을 세 자루 부숴 보면,
세검은 +15를 찍으면 열립니다.
+20짜리 두 자루를 합치면 새 계열 +1이 됩니다.
직검+곡도는 마검, 대검+세검은 성검, 마검+성검은 용검.
용검부터는 전설 구간이 열려 +50까지 올라갑니다.

■ 고유검 — 힌트만 준다
"가장 어두운 것 둘을 +12까지 올려 심연의 정수에 담그면…"
어떤 검을 어디까지 올려 무엇과 섞는지는 직접 알아내야 합니다.
완성한 고유검은 더 올릴 수 없습니다. 그 자체로 끝난 검입니다.

■ 사냥터 — 24구역 144종
화면을 눌러 때립니다. 계열마다 속도와 타격 방식이 다릅니다.
잡몹을 정해진 수만큼 잡으면 보스가 나오고, 보스를 잡으면 다음 구역과 그 구역의 정수가 열립니다.
초원에서 시작해 화산, 용의 둥지, 심연, 별의 무덤을 지나 끝의 문까지 갑니다.

■ 무한 회랑 — 층마다 갈림길
축복·보물·저주 중 하나를 고릅니다. 저주는 다음 층 체력이 두 배지만 보상이 네 배입니다.
다섯 층마다 보상이 확정되고, 확정 전에 쓰러지면 쌓아 둔 것의 일부만 남습니다.

■ 그 밖에
· 도감 174칸 — 단계마다 검 모양이 다릅니다
· 업적과 칭호 40개 — 얻은 칭호는 강화 화면 위에 붙습니다
· 펫 24종 — 구역 보스가 알을 떨어뜨립니다
· 담금질 — 실패가 쌓일수록 다음 성공률이 오릅니다
· 별 강화 — 용검부터 별을 다섯 개까지, 실패해도 검은 부서지지 않습니다
· 자리를 비운 사이에도 보상이 쌓입니다
· 표기 확률과 실제 확률을 나란히 보여 주는 통계 화면

■ 13개 언어
한국어 · English · 日本語 · 简体中文 · 繁體中文 · Español · Français · Deutsch ·
Português · Русский · ไทย · Tiếng Việt · Bahasa Indonesia
```
**출시 노트**
```
첫 출시입니다.
검을 +50까지 강화하고, 일곱 계열을 모으고, 힌트만 보고 고유검을 찾아냅니다.
사냥터 24구역 144종과 무한 회랑, 펫 24종, 도감 174칸.
13개 언어로 즐길 수 있습니다.
```

---

## English (en-US)

**앱 이름**
```
Sword Forge — Enhance & Break
```
**짧은 설명**
```
Enhance one sword higher. When it shatters: restore it, or salvage shards.
```
**자세한 설명**
```
A game about enhancing one sword, over and over.

■ Enhancing — climb, drop, or shatter
A success adds +1. Up to +5 a failure leaves the sword untouched; above that it drops a level.
From +10 it can shatter.
The moment it shatters you choose: restore the sword, or salvage shards. Let the timer run out
and you get neither.

■ Seven families — enhance your way across
You start with the Straight Sword, Curved Sword, Greatsword and Rapier. The Curved Sword opens
at +10, the Greatsword after you survive three shatters, the Rapier at +15.
Combine two swords at +20 and a new family begins at +1.
Straight + Curved makes the Demon Sword, Greatsword + Rapier the Holy Sword,
Demon + Holy the Dragon Sword.
From the Dragon Sword the legendary range opens and runs to +50.

■ Unique Swords — hints are all you get
"Bring the two darkest blades to +12 and steep them in Abyss Essence…"
Which swords, how far, and what to mix them with is yours to work out.
A finished Unique Sword can never be enhanced again. It is done.

■ Hunting grounds — 24 zones, 144 monsters
Tap the screen to attack. Every family swings at its own speed and rhythm.
Clear enough monsters and the boss appears; beat it to open the next zone and claim its Essence.
From the Meadow through the Volcano, the Dragon's Nest, the Abyss and the Grave of the Stars,
all the way to the Door of the End.

■ Infinite Corridor — a fork on every floor
Blessing, treasure, or curse. A curse doubles the next floor's health and quadruples the reward.
Rewards are banked every five floors; fall before banking and you keep only part of the pile.

■ And more
· A 174-slot collection — the blade changes shape at every level
· 40 achievements and titles — an earned title sits above the forge
· 24 pets — zone bosses drop the eggs
· Tempering — every failure raises the odds of the next success
· Star enhancement — up to five stars from the Dragon Sword on; a failure never breaks the sword
· Rewards pile up while you are away
· A stats screen showing the listed odds next to what actually happened

■ 13 languages
한국어 · English · 日本語 · 简体中文 · 繁體中文 · Español · Français · Deutsch ·
Português · Русский · ไทย · Tiếng Việt · Bahasa Indonesia
```
**출시 노트**
```
First release.
Take a sword to +50, work through seven families, and figure out the Unique Swords
from hints alone.
24 hunting zones with 144 monsters, the Infinite Corridor, 24 pets, a 174-slot collection.
Playable in 13 languages.
```

---

## 日本語 (ja)

**앱 이름**
```
剣強化 — 一本を強くする
```
**짧은 설명**
```
剣を強化して上げる。砕けた瞬間、直すかシャードを拾うかをその場で選ぶ。
```
**자세한 설명**
```
剣を一本、ひたすら強化していくゲームです。

■ 強化 — 上がるか、下がるか、砕けるか
成功すれば +1。+5 までは失敗しても剣はそのままですが、その上は一段階下がります。
+10 からは砕けることがあります。
砕けたその瞬間に選びます — 剣を直すか、シャードを拾うか。時間が過ぎれば両方逃します。

■ 七つの系統 — 強化して渡っていく
直剣・曲刀・大剣・レイピアから始まります。曲刀は +10 で、大剣は剣を三本砕くと、
レイピアは +15 で開きます。
+20 の二本を合成すると新しい系統が +1 で生まれます。
直剣+曲刀で魔剣、大剣+レイピアで聖剣、魔剣+聖剣でドラゴンソード。
ドラゴンソードからは伝説の区間が開き、+50 まで上がります。

■ ユニークソード — 手がかりはヒントだけ
「最も暗い二本を +12 まで強化して深淵のエッセンスに浸すと…」
どの剣をどこまで上げ、何と混ぜるのかは自分で解き明かします。
完成したユニークソードは二度と強化できません。それで完成した剣です。

■ 狩猟場 — 24区域144種
画面を叩いて攻撃します。系統ごとに速さと当たり方が違います。
雑魚を決まった数だけ倒すとボスが現れ、倒せば次の区域とその区域のエッセンスが開きます。
草原から火山、竜の巣、深淵、星の墓を抜けて終わりの門まで。

■ 無限回廊 — 階ごとに分かれ道
祝福・宝物・呪いのどれかを選びます。呪いは次の階の体力が二倍、報酬は四倍。
五階ごとに報酬が確定し、確定前に倒れると積んだもののうち一部だけが残ります。

■ そのほか
・図鑑174枠 — 段階ごとに刃の形が変わります
・実績と称号40個 — 得た称号は強化画面の上に付きます
・ペット24種 — 区域のボスが卵を落とします
・焼き入れ — 失敗が重なるほど次の成功率が上がります
・星強化 — ドラゴンソードから星を五つまで。失敗しても剣は砕けません
・離れている間も報酬がたまります
・表示された確率と実際の確率を並べて見せる統計画面

■ 13言語
한국어 · English · 日本語 · 简体中文 · 繁體中文 · Español · Français · Deutsch ·
Português · Русский · ไทย · Tiếng Việt · Bahasa Indonesia
```
**출시 노트**
```
初回リリースです。
剣を +50 まで強化し、七つの系統を集め、ヒントだけを頼りにユニークソードを解き明かします。
狩猟場24区域144種、無限回廊、ペット24種、図鑑174枠。
13言語で遊べます。
```

---

## 中文（简体）(zh-CN)

**앱 이름**
```
锻剑 — 一把剑强化到底
```
**짧은 설명**
```
把一把剑一路强化上去。碎裂的瞬间，是修好还是捡碎片，你当场决定。
```
**자세한 설명**
```
一把剑，一路强化上去。

■ 强化 — 上升、掉级，或者碎裂
成功加 +1。到 +5 为止，失败也不会动这把剑；再往上会掉一级。
从 +10 起可能碎裂。
碎裂的那一刻你要选：修好这把剑，还是捡走碎片。时间过了两样都拿不到。

■ 七个系列 — 一路强化过去
从直剑、弯剑、巨剑、细剑开始。弯剑到 +10 开启，巨剑要先碎三把剑，细剑到 +15 开启。
把两把 +20 合成，新系列从 +1 开始。
直剑+弯剑成魔剑，巨剑+细剑成圣剑，魔剑+圣剑成龙剑。
从龙剑起开启传说区间，一路到 +50。

■ 独有之剑 — 只给线索
「把最暗的两把强化到 +12 再浸入深渊精华…」
用哪几把、打到几级、和什么混，全靠自己想。
已完成的独有之剑无法再强化。它到此为止。

■ 狩猎场 — 24 个区域 144 种怪
点屏幕攻击。每个系列的出手速度和手感都不一样。
清掉规定数量的小怪，首领就出现；打倒它便开启下一个区域和该区域的精华。
从草原到火山、龙巢、深渊、星之墓，一直走到终末之门。

■ 无限回廊 — 每层一个岔路
祝福、宝藏，或者诅咒。诅咒让下一层血量翻倍，奖励翻四倍。
每五层结算一次奖励；结算前倒下，只能留下已堆积的一部分。

■ 还有
· 174 格图鉴 — 每一级刀身的样子都不同
· 40 项成就与头衔 — 拿到的头衔会挂在强化画面上方
· 24 种宠物 — 区域首领会掉蛋
· 淬火 — 失败越多，下一次成功的概率越高
· 镶星 — 从龙剑起最多五颗星，失败也不会碎剑
· 离开期间也会累积奖励
· 把标示概率和实际概率并排给你看的统计页

■ 13 种语言
한국어 · English · 日本語 · 简体中文 · 繁體中文 · Español · Français · Deutsch ·
Português · Русский · ไทย · Tiếng Việt · Bahasa Indonesia
```
**출시 노트**
```
首次发布。
把剑强化到 +50，集齐七个系列，只凭线索解开独有之剑。
狩猎场 24 个区域 144 种怪、无限回廊、24 种宠物、174 格图鉴。
支持 13 种语言。
```

---

## 中文（繁體）(zh-TW)

**앱 이름**
```
鍛劍 — 一把劍強化到底
```
**짧은 설명**
```
把一把劍一路強化上去。碎裂的瞬間，是修好還是撿碎片，你當場決定。
```
**자세한 설명**
```
一把劍，一路強化上去。

■ 強化 — 上升、掉級，或者碎裂
成功加 +1。到 +5 為止，失敗也不會動這把劍；再往上會掉一級。
從 +10 起可能碎裂。
碎裂的那一刻你要選：修好這把劍，還是撿走碎片。時間過了兩樣都拿不到。

■ 七個系列 — 一路強化過去
從直劍、彎劍、大劍、細劍開始。彎劍到 +10 開啟，大劍要先碎三把劍，細劍到 +15 開啟。
把兩把 +20 合成，新系列從 +1 開始。
直劍+彎劍成魔劍，大劍+細劍成聖劍，魔劍+聖劍成龍劍。
從龍劍起開啟傳說區間，一路到 +50。

■ 獨有之劍 — 只給線索
「把最暗的兩把強化到 +12 再浸入深淵精華…」
用哪幾把、打到幾級、和什麼混，全靠自己想。
已完成的獨有之劍無法再強化。它到此為止。

■ 狩獵場 — 24 個區域 144 種怪
點螢幕攻擊。每個系列的出手速度和手感都不一樣。
清掉規定數量的小怪，首領就出現；打倒牠便開啟下一個區域和該區域的精華。
從草原到火山、龍巢、深淵、星之墓，一直走到終末之門。

■ 無限迴廊 — 每層一個岔路
祝福、寶藏，或者詛咒。詛咒讓下一層血量翻倍，獎勵翻四倍。
每五層結算一次獎勵；結算前倒下，只能留下已堆積的一部分。

■ 還有
· 174 格圖鑑 — 每一級刀身的樣子都不同
· 40 項成就與頭銜 — 拿到的頭銜會掛在強化畫面上方
· 24 種寵物 — 區域首領會掉蛋
· 淬火 — 失敗越多，下一次成功的機率越高
· 鑲星 — 從龍劍起最多五顆星，失敗也不會碎劍
· 離開期間也會累積獎勵
· 把標示機率和實際機率並排給你看的統計頁

■ 13 種語言
한국어 · English · 日本語 · 简体中文 · 繁體中文 · Español · Français · Deutsch ·
Português · Русский · ไทย · Tiếng Việt · Bahasa Indonesia
```
**출시 노트**
```
首次發布。
把劍強化到 +50，集齊七個系列，只憑線索解開獨有之劍。
狩獵場 24 個區域 144 種怪、無限迴廊、24 種寵物、174 格圖鑑。
支援 13 種語言。
```

---

## 中文（香港）(zh-HK)

**앱 이름**
```
鍛劍 — 一把劍強化到底
```
**짧은 설명**
```
把一把劍一路強化上去。碎裂嗰一刻，係修好定係執碎片，你當場決定。
```
**자세한 설명**
```
一把劍，一路強化上去。

■ 強化 — 上升、掉級，或者碎裂
成功加 +1。到 +5 為止，失敗都唔會郁到把劍；再上去就會跌一級。
由 +10 起有機會碎裂。
碎裂嗰一刻你要揀：修好把劍，定係執走碎片。過咗時間兩樣都冇。

■ 七個系列 — 一路強化過去
由直劍、彎劍、大劍、細劍開始。彎劍到 +10 開啟，大劍要先碎三把劍，細劍到 +15 開啟。
合成兩把 +20，新系列由 +1 開始。
直劍+彎劍成魔劍，大劍+細劍成聖劍，魔劍+聖劍成龍劍。
由龍劍起開啟傳說區間，一路去到 +50。

■ 獨有之劍 — 只畀線索
「把最暗嘅兩把強化到 +12 再浸入深淵精華…」
用邊幾把、打到幾級、同乜嘢溝，全部靠自己諗。
已完成嘅獨有之劍無法再強化。到此為止。

■ 狩獵場 — 24 個區域 144 種怪
撳螢幕攻擊。每個系列出手嘅速度同手感都唔同。
清晒指定數量嘅小怪，首領就出現；打低佢就開啟下一個區域同嗰區嘅精華。
由草原去到火山、龍巢、深淵、星之墓，一路行到終末之門。

■ 無限迴廊 — 每層一個岔路
祝福、寶藏，或者詛咒。詛咒令下一層血量翻倍，獎勵翻四倍。
每五層結算一次獎勵；結算前倒下，只可以留低已堆積嘅一部分。

■ 仲有
· 174 格圖鑑 — 每一級刀身嘅樣都唔同
· 40 項成就同頭銜 — 攞到嘅頭銜會掛喺強化畫面上面
· 24 種寵物 — 區域首領會跌蛋
· 淬火 — 失敗越多，下一次成功嘅機率越高
· 鑲星 — 由龍劍起最多五粒星，失敗都唔會碎劍
· 離開期間都會累積獎勵
· 將標示機率同實際機率並排畀你睇嘅統計頁

■ 13 種語言
한국어 · English · 日本語 · 简体中文 · 繁體中文 · Español · Français · Deutsch ·
Português · Русский · ไทย · Tiếng Việt · Bahasa Indonesia
```
**출시 노트**
```
首次發布。
把劍強化到 +50，集齊七個系列，凈係靠線索解開獨有之劍。
狩獵場 24 個區域 144 種怪、無限迴廊、24 種寵物、174 格圖鑑。
支援 13 種語言。
```

---

## Español (es)

**앱 이름**
```
Forja de Espadas: sube o rompe
```
**짧은 설명**
```
Mejora una espada para subirla. Si se rompe: repárala o salva fragmentos.
```
**자세한 설명**
```
Un juego sobre mejorar una sola espada, una y otra vez.

■ Mejora: sube, baja o se rompe
Un acierto suma +1. Hasta +5 un fallo deja la espada intacta; por encima baja un nivel.
Desde +10 puede romperse.
En el instante en que se rompe eliges: recuperar la espada o salvar fragmentos.
Si se acaba el tiempo, pierdes las dos cosas.

■ Siete familias: mejora hasta la siguiente
Empiezas con la espada recta, la curva, la gran espada y el estoque. La curva se abre al +10,
la gran espada tras sobrevivir a tres roturas, el estoque al +15.
Combina dos espadas a +20 y nace una familia nueva en +1.
Recta + curva da la espada demoníaca; gran espada + estoque, la sagrada;
demoníaca + sagrada, la espada del dragón.
Desde la espada del dragón se abre el tramo legendario, que llega hasta +50.

■ Espadas únicas: solo tienes pistas
«Lleva a +12 las dos hojas más oscuras y sumérgelas en esencia del abismo…»
Qué espadas, hasta dónde y con qué mezclarlas es cosa tuya.
Una espada única terminada ya no se puede mejorar. Está acabada.

■ Zonas de caza: 24 zonas, 144 monstruos
Toca la pantalla para atacar. Cada familia golpea a su propio ritmo.
Derrota a los monstruos suficientes y aparece el jefe; véncelo para abrir la zona siguiente
y quedarte con su esencia.
Del prado al volcán, el nido de dragón, el abismo y la tumba de estrellas, hasta la puerta del final.

■ Corredor infinito: una bifurcación en cada piso
Bendición, tesoro o maldición. La maldición dobla la vida del piso siguiente y cuadruplica el premio.
La recompensa se asegura cada cinco pisos; si caes antes, solo conservas una parte.

■ Y además
· Una colección de 174 casillas: la hoja cambia de forma en cada nivel
· 40 logros y títulos: el título que llevas aparece sobre la forja
· 24 mascotas: los jefes de zona sueltan los huevos
· Temple: cada fallo sube la probabilidad del siguiente acierto
· Estrellas: hasta cinco desde la espada del dragón; un fallo nunca rompe la espada
· La recompensa se acumula mientras no juegas
· Una pantalla de estadísticas que pone la probabilidad indicada junto a la real

■ 13 idiomas
한국어 · English · 日本語 · 简体中文 · 繁體中文 · Español · Français · Deutsch ·
Português · Русский · ไทย · Tiếng Việt · Bahasa Indonesia
```
**출시 노트**
```
Primera versión.
Sube una espada hasta +50, reúne las siete familias y descubre las espadas únicas
solo con pistas.
24 zonas de caza con 144 monstruos, el corredor infinito, 24 mascotas y 174 casillas de colección.
Disponible en 13 idiomas.
```

---

## Français (fr)

**앱 이름**
```
Forge d'Épées — Monte ou casse
```
**짧은 설명**
```
Améliore une épée pour la monter. Si elle se brise : répare ou récupère.
```
**자세한 설명**
```
Un jeu où l'on améliore une seule épée, encore et encore.

■ Amélioration : monter, redescendre ou se briser
Une réussite ajoute +1. Jusqu'à +5, un échec laisse l'épée intacte ; au-dessus, elle perd un niveau.
À partir de +10, elle peut se briser.
À l'instant où elle se brise, tu choisis : réparer l'épée ou récupérer des éclats.
Si le temps s'écoule, tu perds les deux.

■ Sept familles : améliore jusqu'à la suivante
Tu commences avec l'épée droite, l'épée courbe, la grande épée et la rapière. L'épée courbe
s'ouvre à +10, la grande épée après trois bris survécus, la rapière à +15.
Combine deux épées à +20 et une nouvelle famille naît à +1.
Droite + courbe donne l'épée démoniaque ; grande épée + rapière, l'épée sacrée ;
démoniaque + sacrée, l'épée du dragon.
À partir de l'épée du dragon, la plage légendaire s'ouvre et grimpe jusqu'à +50.

■ Épées uniques : tu n'as que les indices
« Amène à +12 les deux lames les plus sombres et plonge-les dans l'essence de l'abîme… »
Quelles épées, jusqu'où, et avec quoi les mêler : à toi de le trouver.
Une épée unique achevée ne peut plus être améliorée. Elle est finie.

■ Terrains de chasse : 24 zones, 144 monstres
Touche l'écran pour attaquer. Chaque famille frappe à son propre rythme.
Abats assez de monstres et le boss apparaît ; bats-le pour ouvrir la zone suivante
et récupérer son essence.
De la prairie au volcan, au nid de dragon, à l'abîme et au tombeau des étoiles,
jusqu'à la porte de la fin.

■ Couloir infini : une bifurcation à chaque étage
Bénédiction, trésor ou malédiction. La malédiction double les points de vie de l'étage suivant
et quadruple la récompense.
La récompense est acquise tous les cinq étages ; si tu tombes avant, tu n'en gardes qu'une part.

■ Et encore
· Une collection de 174 cases : la lame change de forme à chaque niveau
· 40 succès et titres : le titre porté s'affiche au-dessus de la forge
· 24 familiers : les boss de zone lâchent les œufs
· Trempe : chaque échec augmente les chances du prochain succès
· Étoiles : jusqu'à cinq à partir de l'épée du dragon ; un échec ne brise jamais l'épée
· Les récompenses s'accumulent pendant ton absence
· Un écran de statistiques qui met la probabilité annoncée à côté de la réelle

■ 13 langues
한국어 · English · 日本語 · 简体中文 · 繁體中文 · Español · Français · Deutsch ·
Português · Русский · ไทย · Tiếng Việt · Bahasa Indonesia
```
**출시 노트**
```
Première version.
Monte une épée jusqu'à +50, réunis les sept familles et devine les épées uniques
avec les seuls indices.
24 zones de chasse et 144 monstres, le couloir infini, 24 familiers, 174 cases de collection.
Jouable en 13 langues.
```

---

## Deutsch (de)

**앱 이름**
```
Schwertschmiede — Verstärken
```
**짧은 설명**
```
Verstärke ein Schwert höher. Zerbricht es: retten oder Scherben bergen.
```
**자세한 설명**
```
Ein Spiel darüber, ein einziges Schwert immer weiter zu verstärken.

■ Verstärken: steigen, sinken oder zerbrechen
Ein Erfolg gibt +1. Bis +5 bleibt das Schwert bei einem Fehlschlag unberührt; darüber verliert
es eine Stufe. Ab +10 kann es zerbrechen.
Im Moment des Bruchs wählst du: das Schwert wiederherstellen oder Scherben bergen.
Läuft die Zeit ab, ist beides weg.

■ Sieben Familien: verstärke dich hinüber
Du beginnst mit Geradem Schwert, Gebogenem Schwert, Großschwert und Rapier. Das Gebogene
öffnet bei +10, das Großschwert nach drei überstandenen Brüchen, das Rapier bei +15.
Kombiniere zwei Schwerter auf +20, und eine neue Familie beginnt bei +1.
Gerade + Gebogen ergibt das Dämonenschwert, Großschwert + Rapier das Heilige Schwert,
Dämonen + Heilig das Drachenschwert.
Ab dem Drachenschwert öffnet sich der legendäre Bereich und läuft bis +50.

■ Einzigartige Schwerter: mehr als Hinweise gibt es nicht
„Bring die zwei dunkelsten Klingen auf +12 und tauche sie in Abgrund-Essenz …"
Welche Schwerter, wie weit und womit gemischt — das musst du selbst herausfinden.
Ein fertiges einzigartiges Schwert lässt sich nie wieder verstärken. Es ist vollendet.

■ Jagdreviere: 24 Zonen, 144 Monster
Tippe auf den Bildschirm, um anzugreifen. Jede Familie schlägt in eigenem Tempo.
Besiege genug Monster, und der Boss erscheint; schlägst du ihn, öffnet sich die nächste Zone
und du bekommst ihre Essenz.
Von der Wiese über den Vulkan, das Drachennest, den Abgrund und das Sternengrab
bis zum Tor des Endes.

■ Unendlicher Korridor: auf jeder Etage eine Abzweigung
Segen, Schatz oder Fluch. Der Fluch verdoppelt die Lebenspunkte der nächsten Etage
und vervierfacht die Belohnung.
Alle fünf Etagen wird die Belohnung gesichert; fällst du davor, bleibt nur ein Teil.

■ Und außerdem
· Eine Sammlung mit 174 Feldern — die Klinge sieht auf jeder Stufe anders aus
· 40 Erfolge und Titel — der getragene Titel steht über der Schmiede
· 24 Haustiere — die Zonenbosse lassen die Eier fallen
· Härtung — jeder Fehlschlag hebt die Chance auf den nächsten Erfolg
· Sterne — bis zu fünf ab dem Drachenschwert; ein Fehlschlag bricht das Schwert nie
· Belohnungen sammeln sich, während du weg bist
· Ein Statistikschirm, der die angegebene Wahrscheinlichkeit neben die echte stellt

■ 13 Sprachen
한국어 · English · 日本語 · 简体中文 · 繁體中文 · Español · Français · Deutsch ·
Português · Русский · ไทย · Tiếng Việt · Bahasa Indonesia
```
**출시 노트**
```
Erste Veröffentlichung.
Bring ein Schwert auf +50, sammle die sieben Familien und finde die einzigartigen
Schwerter allein aus Hinweisen.
24 Jagdzonen mit 144 Monstern, der unendliche Korridor, 24 Haustiere, 174 Sammlungsfelder.
In 13 Sprachen spielbar.
```

---

## Português (pt-BR)

**앱 이름**
```
Forja de Espadas: sobe ou cai
```
**짧은 설명**
```
Aprimore uma espada para subir. Se quebrar: restaure ou salve fragmentos.
```
**자세한 설명**
```
Um jogo sobre aprimorar uma única espada, vez após vez.

■ Aprimoramento: sobe, cai ou quebra
Um acerto soma +1. Até +5 uma falha deixa a espada intacta; acima disso ela cai um nível.
A partir de +10 ela pode quebrar.
No instante em que quebra você escolhe: restaurar a espada ou salvar fragmentos.
Se o tempo acabar, você perde os dois.

■ Sete famílias: aprimore até a seguinte
Você começa com a espada reta, a curva, a espada grande e o florete. A curva abre em +10,
a espada grande depois de sobreviver a três quebras, o florete em +15.
Combine duas espadas em +20 e uma família nova nasce em +1.
Reta + curva dá a espada demoníaca; espada grande + florete, a sagrada;
demoníaca + sagrada, a espada do dragão.
A partir da espada do dragão abre-se a faixa lendária, que vai até +50.

■ Espadas únicas: você só tem as dicas
"Leve a +12 as duas lâminas mais escuras e as mergulhe na essência do abismo…"
Quais espadas, até onde e com o que misturar é você quem descobre.
Uma espada única pronta nunca mais pode ser aprimorada. Ela está concluída.

■ Áreas de caça: 24 zonas, 144 monstros
Toque na tela para atacar. Cada família golpeia no seu próprio ritmo.
Derrote monstros suficientes e o chefe aparece; vença-o para abrir a próxima zona
e ficar com a essência dela.
Do prado ao vulcão, ao ninho de dragão, ao abismo e ao túmulo das estrelas,
até a porta do fim.

■ Corredor infinito: uma bifurcação em cada andar
Bênção, tesouro ou maldição. A maldição dobra a vida do andar seguinte
e quadruplica a recompensa.
A recompensa é garantida a cada cinco andares; se você cair antes, fica só com uma parte.

■ E ainda
· Uma coleção de 174 espaços — a lâmina muda de forma a cada nível
· 40 conquistas e títulos — o título usado aparece acima da forja
· 24 mascotes — os chefes de zona soltam os ovos
· Têmpera — cada falha aumenta a chance do próximo acerto
· Estrelas — até cinco a partir da espada do dragão; uma falha nunca quebra a espada
· As recompensas se acumulam enquanto você está fora
· Uma tela de estatísticas que põe a probabilidade indicada ao lado da real

■ 13 idiomas
한국어 · English · 日本語 · 简体中文 · 繁體中文 · Español · Français · Deutsch ·
Português · Русский · ไทย · Tiếng Việt · Bahasa Indonesia
```
**출시 노트**
```
Primeira versão.
Leve uma espada até +50, reúna as sete famílias e descubra as espadas únicas
só pelas dicas.
24 zonas de caça com 144 monstros, o corredor infinito, 24 mascotes, 174 espaços de coleção.
Jogável em 13 idiomas.
```

---

## Русский (ru)

**앱 이름**
```
Кузница Мечей: до +50
```
**짧은 설명**
```
Улучшай один меч всё выше. Разбился — выбирай: вернуть его или забрать осколки.
```
**자세한 설명**
```
Игра о том, как улучшать один-единственный меч снова и снова.

■ Улучшение: вверх, вниз или вдребезги
Успех даёт +1. До +5 неудача не трогает меч; выше — он теряет уровень.
С +10 он может разбиться.
В тот миг, когда меч разбился, ты выбираешь: вернуть его или забрать осколки.
Время выйдет — не будет ни того, ни другого.

■ Семь семейств: улучшай до следующего
Начинаешь с прямого меча, изогнутого, большого и рапиры. Изогнутый открывается на +10,
большой — после трёх пережитых разрушений, рапира — на +15.
Соедини два меча на +20, и новое семейство начнётся с +1.
Прямой + изогнутый дают демонический меч, большой + рапира — святой,
демонический + святой — меч дракона.
С меча дракона открывается легендарный отрезок, он идёт до +50.

■ Уникальные мечи: у тебя есть только подсказки
«Доведи два самых тёмных клинка до +12 и погрузи их в эссенцию бездны…»
Какие мечи, до какого уровня и с чем смешивать — разбираться тебе.
Готовый уникальный меч улучшать уже нельзя. Он завершён.

■ Охотничьи угодья: 24 зоны, 144 монстра
Нажимай на экран, чтобы бить. У каждого семейства свой темп удара.
Убей достаточно монстров — появится босс; победи его, и откроется следующая зона
вместе с её эссенцией.
От луга через вулкан, гнездо дракона, бездну и могилу звёзд — до двери конца.

■ Бесконечный коридор: развилка на каждом этаже
Благословение, сокровище или проклятие. Проклятие удваивает здоровье следующего этажа
и учетверяет награду.
Награда закрепляется каждые пять этажей; падёшь раньше — останется только часть.

■ И ещё
· Коллекция на 174 ячейки — на каждом уровне клинок выглядит иначе
· 40 достижений и званий — надетое звание стоит над кузницей
· 24 питомца — яйца роняют боссы зон
· Закалка — каждая неудача поднимает шанс следующего успеха
· Звёзды — до пяти начиная с меча дракона; неудача никогда не ломает меч
· Награды копятся, пока тебя нет
· Экран статистики, где заявленная вероятность стоит рядом с настоящей

■ 13 языков
한국어 · English · 日本語 · 简体中文 · 繁體中文 · Español · Français · Deutsch ·
Português · Русский · ไทย · Tiếng Việt · Bahasa Indonesia
```
**출시 노트**
```
Первый выпуск.
Доведи меч до +50, собери семь семейств и разгадай уникальные мечи по одним подсказкам.
24 охотничьи зоны со 144 монстрами, бесконечный коридор, 24 питомца, коллекция на 174 ячейки.
Играется на 13 языках.
```

---

## Tiếng Việt (vi)

**앱 이름**
```
Rèn Kiếm — Lên hoặc vỡ
```
**짧은 설명**
```
Cường hóa một thanh kiếm lên cao. Kiếm vỡ thì bạn chọn: cứu nó hay nhặt mảnh vỡ.
```
**자세한 설명**
```
Một trò chơi về việc cường hóa một thanh kiếm mãi không thôi.

■ Cường hóa: lên, tụt, hoặc vỡ
Thành công cộng +1. Đến +5 thất bại không đụng tới kiếm; trên nữa thì tụt một cấp.
Từ +10 kiếm có thể vỡ.
Đúng lúc kiếm vỡ bạn phải chọn: phục hồi kiếm hay nhặt mảnh vỡ.
Hết giờ thì mất cả hai.

■ Bảy hệ: cường hóa để đi tiếp
Bạn bắt đầu với kiếm thẳng, đao cong, đại kiếm và rapier. Đao cong mở ở +10,
đại kiếm sau khi chịu ba lần vỡ, rapier ở +15.
Ghép hai thanh +20 thì một hệ mới ra đời ở +1.
Kiếm thẳng + đao cong thành quỷ kiếm; đại kiếm + rapier thành thánh kiếm;
quỷ kiếm + thánh kiếm thành kiếm rồng.
Từ kiếm rồng mở ra đoạn truyền thuyết, đi tới +50.

■ Kiếm độc đáo: chỉ có gợi ý
"Đưa hai lưỡi tối nhất lên +12 rồi nhúng vào tinh chất thâm uyên…"
Dùng thanh nào, lên tới đâu, trộn với gì — tự bạn tìm ra.
Kiếm độc đáo đã hoàn thành thì không cường hóa được nữa. Nó đã xong.

■ Bãi săn: 24 vùng, 144 loại quái
Chạm màn hình để đánh. Mỗi hệ có tốc độ và nhịp ra đòn riêng.
Hạ đủ quái thì trùm xuất hiện; đánh bại nó sẽ mở vùng kế tiếp và tinh chất của vùng đó.
Từ đồng cỏ qua núi lửa, tổ rồng, thâm uyên và mộ sao, tới tận cánh cửa cuối.

■ Hành lang vô tận: mỗi tầng một ngã rẽ
Phước lành, kho báu, hoặc lời nguyền. Lời nguyền nhân đôi máu tầng sau và nhân bốn phần thưởng.
Cứ năm tầng thì thưởng được chốt; ngã trước đó chỉ giữ được một phần.

■ Và còn
· Bộ sưu tập 174 ô — mỗi cấp lưỡi kiếm một hình khác
· 40 thành tích và danh hiệu — danh hiệu đang mang hiện trên lò rèn
· 24 thú cưng — trùm của vùng thả trứng
· Tôi luyện — càng thất bại thì lần sau càng dễ thành công
· Gắn sao — tối đa năm ngôi từ kiếm rồng; thất bại không bao giờ làm vỡ kiếm
· Phần thưởng dồn lại khi bạn không chơi
· Màn thống kê đặt tỉ lệ ghi trên bảng cạnh tỉ lệ thật

■ 13 ngôn ngữ
한국어 · English · 日本語 · 简体中文 · 繁體中文 · Español · Français · Deutsch ·
Português · Русский · ไทย · Tiếng Việt · Bahasa Indonesia
```
**출시 노트**
```
Bản phát hành đầu tiên.
Đưa một thanh kiếm lên +50, gom đủ bảy hệ, và giải ra kiếm độc đáo chỉ bằng gợi ý.
24 vùng săn với 144 loại quái, hành lang vô tận, 24 thú cưng, bộ sưu tập 174 ô.
Chơi được bằng 13 ngôn ngữ.
```

---

## Bahasa Indonesia (id)

**앱 이름**
```
Tempa Pedang — Naik atau pecah
```
**짧은 설명**
```
Tingkatkan satu pedang makin tinggi. Kalau pecah: pulihkan atau ambil pecahan.
```
**자세한 설명**
```
Permainan tentang meningkatkan satu pedang, terus-menerus.

■ Peningkatan: naik, turun, atau pecah
Berhasil menambah +1. Sampai +5 kegagalan tidak mengubah pedang; di atasnya turun satu tingkat.
Mulai dari +10 pedang bisa pecah.
Begitu pecah kamu memilih: pulihkan pedangnya, atau selamatkan pecahannya.
Kalau waktunya habis, dua-duanya hilang.

■ Tujuh keluarga: tingkatkan sampai berikutnya
Kamu mulai dengan pedang lurus, pedang melengkung, pedang hebat, dan rapier. Pedang melengkung
terbuka di +10, pedang hebat setelah tiga kali pecah, rapier di +15.
Gabungkan dua pedang di +20 dan keluarga baru lahir di +1.
Lurus + melengkung jadi pedang setan; pedang hebat + rapier jadi pedang suci;
setan + suci jadi pedang naga.
Dari pedang naga terbuka rentang legenda, sampai +50.

■ Pedang unik: yang kamu punya cuma petunjuk
"Naikkan dua bilah tergelap ke +12 lalu celupkan ke esensi jurang…"
Pedang mana, sampai berapa, dicampur dengan apa — kamu sendiri yang harus tahu.
Pedang unik yang sudah jadi tidak bisa ditingkatkan lagi. Ia sudah selesai.

■ Tempat berburu: 24 zona, 144 monster
Ketuk layar untuk menyerang. Tiap keluarga punya kecepatan dan irama pukulan sendiri.
Kalahkan monster secukupnya lalu bos muncul; kalahkan bos untuk membuka zona berikutnya
dan mengambil esensinya.
Dari padang rumput ke gunung berapi, sarang naga, jurang, dan makam bintang,
sampai gerbang akhir.

■ Koridor tanpa batas: percabangan di tiap lantai
Berkah, harta, atau kutukan. Kutukan menggandakan nyawa lantai berikutnya
dan melipatempatkan hadiah.
Hadiah diamankan tiap lima lantai; jatuh sebelum itu, hanya sebagian yang tersisa.

■ Dan lagi
· Koleksi 174 petak — bentuk bilah berubah di tiap tingkat
· 40 prestasi dan gelar — gelar yang dipakai tampil di atas bengkel
· 24 hewan peliharaan — bos zona menjatuhkan telurnya
· Sepuh — makin sering gagal, makin besar peluang berhasil berikutnya
· Bintang — sampai lima mulai dari pedang naga; gagal tidak pernah memecahkan pedang
· Hadiah menumpuk selagi kamu pergi
· Layar statistik yang menaruh peluang tertulis di sebelah peluang sebenarnya

■ 13 bahasa
한국어 · English · 日本語 · 简体中文 · 繁體中文 · Español · Français · Deutsch ·
Português · Русский · ไทย · Tiếng Việt · Bahasa Indonesia
```
**출시 노트**
```
Rilis pertama.
Bawa satu pedang ke +50, kumpulkan tujuh keluarga, dan pecahkan pedang unik hanya dari petunjuk.
24 zona berburu dengan 144 monster, koridor tanpa batas, 24 hewan peliharaan,
koleksi 174 petak.
Bisa dimainkan dalam 13 bahasa.
```

---

## ไทย (th)

**앱 이름**
```
ตีดาบ — ขึ้นหรือแตก
```
**짧은 설명**
```
เสริมพลังดาบเล่มเดียวให้สูงขึ้น ถ้าแตก คุณเลือกเอง จะซ่อมหรือจะเก็บเศษ
```
**자세한 설명**
```
เกมที่คุณเสริมพลังดาบเล่มเดียวไปเรื่อย ๆ

■ เสริมพลัง — ขึ้น ลง หรือแตก
สำเร็จได้ +1 ถึง +5 ถ้าล้มเหลวดาบยังคงเดิม เหนือจากนั้นจะลดลงหนึ่งขั้น
ตั้งแต่ +10 ดาบอาจแตกได้
ทันทีที่แตก คุณต้องเลือก จะซ่อมดาบหรือจะเก็บเศษ ถ้าหมดเวลาจะไม่ได้ทั้งสองอย่าง

■ เจ็ดสาย — เสริมพลังเพื่อข้ามไป
เริ่มจากดาบตรง ดาบโค้ง ดาบใหญ่ และเรเปียร์ ดาบโค้งเปิดที่ +10
ดาบใหญ่เปิดเมื่อทำดาบแตกครบสามครั้ง เรเปียร์เปิดที่ +15
รวมดาบ +20 สองเล่ม แล้วสายใหม่จะเกิดที่ +1
ดาบตรง+ดาบโค้งได้ดาบปีศาจ ดาบใหญ่+เรเปียร์ได้ดาบศักดิ์สิทธิ์
ดาบปีศาจ+ดาบศักดิ์สิทธิ์ได้ดาบมังกร
ตั้งแต่ดาบมังกรจะเปิดช่วงตำนาน ไปได้ถึง +50

■ ดาบเฉพาะตัว — มีแต่เบาะแส
"เสริมใบดาบที่มืดที่สุดสองเล่มถึง +12 แล้วจุ่มในแก่นแท้แห่งเหวลึก…"
ใช้ดาบเล่มไหน ถึงระดับใด ผสมกับอะไร คุณต้องหาเอง
ดาบเฉพาะตัวที่สำเร็จแล้วเสริมพลังต่อไม่ได้ มันจบในตัวมันเอง

■ พื้นที่ล่าสัตว์ — 24 โซน 144 ชนิด
แตะหน้าจอเพื่อโจมตี แต่ละสายมีความเร็วและจังหวะต่างกัน
กำจัดมอนสเตอร์ครบจำนวนแล้วบอสจะปรากฏ ล้มบอสได้จะเปิดโซนถัดไปและแก่นแท้ของโซนนั้น
จากทุ่งหญ้าผ่านภูเขาไฟ รังมังกร เหวลึก และสุสานดาว ไปจนถึงประตูสุดท้าย

■ โถงอนันต์ — ทางแยกทุกชั้น
เลือกพร สมบัติ หรือคำสาป คำสาปทำให้ชั้นถัดไปเลือดสองเท่าแต่รางวัลสี่เท่า
ทุกห้าชั้นรางวัลจะถูกเก็บ ถ้าล้มก่อนเก็บจะเหลือเพียงบางส่วน

■ และอีก
· สมุดภาพ 174 ช่อง — รูปทรงใบดาบเปลี่ยนไปทุกระดับ
· ความสำเร็จและตำแหน่ง 40 อย่าง — ตำแหน่งที่สวมจะขึ้นเหนือโรงตีเหล็ก
· สัตว์เลี้ยง 24 ชนิด — บอสประจำโซนทำไข่ตก
· ชุบแข็ง — ยิ่งล้มเหลวสะสม โอกาสสำเร็จครั้งถัดไปยิ่งสูง
· ติดดาว — สูงสุดห้าดวงตั้งแต่ดาบมังกร ล้มเหลวก็ไม่ทำให้ดาบแตก
· รางวัลสะสมต่อแม้คุณไม่ได้เล่น
· หน้าสถิติที่วางความน่าจะเป็นที่ระบุไว้ข้างความน่าจะเป็นจริง

■ 13 ภาษา
한국어 · English · 日本語 · 简体中文 · 繁體中文 · Español · Français · Deutsch ·
Português · Русский · ไทย · Tiếng Việt · Bahasa Indonesia
```
**출시 노트**
```
เปิดตัวครั้งแรก
เสริมพลังดาบให้ถึง +50 เก็บครบทั้งเจ็ดสาย และไขดาบเฉพาะตัวจากเบาะแสเพียงอย่างเดียว
พื้นที่ล่าสัตว์ 24 โซน 144 ชนิด โถงอนันต์ สัตว์เลี้ยง 24 ชนิด สมุดภาพ 174 ช่อง
เล่นได้ 13 ภาษา
```

---

## 카테고리

- 앱 유형: **게임**
- 카테고리: **롤플레잉** (또는 시뮬레이션 — 강화·수집이 중심이라 롤플레잉이 가깝다)
- 태그: 강화, 대장간, 검, 수집, 방치형, 도트

## 데이터 보안 (Data safety) 신고

| 질문 | 답 |
|---|---|
| 데이터를 수집하거나 공유하나요? | **아니요** |
| 전송 중 데이터가 암호화되나요? | 해당 없음 (전송 자체가 없음) |
| 사용자가 데이터 삭제를 요청할 수 있나요? | 해당 없음 (수집하지 않음) |

앱에 **인터넷 권한이 없다.** 기기 밖으로 무엇을 보내는 것이 기술적으로 불가능하다.
진행 상황은 기기 안에만 저장되고, 앱을 지우면 같이 사라진다.
`android:allowBackup="false"` 라서 구글 자동 백업으로도 올라가지 않는다.

## 권한

`android.permission.VIBRATE` 하나. 강화 결과를 손끝으로 알리는 데만 쓴다.
설정에서 끌 수 있다.

## 광고·인앱 구매

현재 빌드에는 **둘 다 없다.** 콘텐츠 등급 설문과 데이터 보안 신고에도 없다고 답한다.
나중에 붙일 때는 **개인정보처리방침을 먼저 고치고** 두 신고를 갱신한 뒤 새 빌드를 올린다.

## 스크린샷

`SwordForge/store/screenshots/<언어>/` 에 언어마다 여섯 장씩 있다
(강화 · 사냥터 · 무한 회랑 · 조합소 · 도감 · 펫). 1080×2340, 세로.
플레이 콘솔은 언어마다 최소 두 장, 최대 여덟 장을 받는다.


## 쓰지 않을 표현

설명란에 아래 부류는 한 줄도 쓰지 않는다. 지금은 참이어도 나중에 거짓이 되고,
그때 문구를 지워도 그것을 보고 받은 사람은 남는다.

- 광고 없음 · 인앱결제 없음 · 완전 무료
- 인터넷을 쓰지 않음 · 개인정보를 일절 수집하지 않음 · 오프라인 전용

단 **데이터 보안 설문과 콘텐츠 등급의 「광고 포함」·「인앱 구매」 항목은 반대다.**
그건 마케팅 문구가 아니라 신고 사항이라, 올리는 빌드의 실제 모습대로 적어야 한다.

---

## 출시 노트 — 콘솔에 한 번에 붙여 넣기

콘솔의 출시 노트 칸은 언어를 묶음표로 나눈다. 아래를 통째로 복사해
붙여 넣으면 열네 언어가 한 번에 들어간다.

```
<en-US>
First release.
Take a sword to +50, work through seven families, and figure out the Unique Swords
from hints alone.
24 hunting zones with 144 monsters, the Infinite Corridor, 24 pets, a 174-slot collection.
Playable in 13 languages.
</en-US>
<de-DE>
Erste Veröffentlichung.
Bring ein Schwert auf +50, sammle die sieben Familien und finde die einzigartigen
Schwerter allein aus Hinweisen.
24 Jagdzonen mit 144 Monstern, der unendliche Korridor, 24 Haustiere, 174 Sammlungsfelder.
In 13 Sprachen spielbar.
</de-DE>
<es-ES>
Primera versión.
Sube una espada hasta +50, reúne las siete familias y descubre las espadas únicas
solo con pistas.
24 zonas de caza con 144 monstruos, el corredor infinito, 24 mascotas y 174 casillas de colección.
Disponible en 13 idiomas.
</es-ES>
<fr-FR>
Première version.
Monte une épée jusqu'à +50, réunis les sept familles et devine les épées uniques
avec les seuls indices.
24 zones de chasse et 144 monstres, le couloir infini, 24 familiers, 174 cases de collection.
Jouable en 13 langues.
</fr-FR>
<id>
Rilis pertama.
Bawa satu pedang ke +50, kumpulkan tujuh keluarga, dan pecahkan pedang unik hanya dari petunjuk.
24 zona berburu dengan 144 monster, koridor tanpa batas, 24 hewan peliharaan,
koleksi 174 petak.
Bisa dimainkan dalam 13 bahasa.
</id>
<ja-JP>
初回リリースです。
剣を +50 まで強化し、七つの系統を集め、ヒントだけを頼りにユニークソードを解き明かします。
狩猟場24区域144種、無限回廊、ペット24種、図鑑174枠。
13言語で遊べます。
</ja-JP>
<ko-KR>
첫 출시입니다.
검을 +50까지 강화하고, 일곱 계열을 모으고, 힌트만 보고 고유검을 찾아냅니다.
사냥터 24구역 144종과 무한 회랑, 펫 24종, 도감 174칸.
13개 언어로 즐길 수 있습니다.
</ko-KR>
<pt-BR>
Primeira versão.
Leve uma espada até +50, reúna as sete famílias e descubra as espadas únicas
só pelas dicas.
24 zonas de caça com 144 monstros, o corredor infinito, 24 mascotes, 174 espaços de coleção.
Jogável em 13 idiomas.
</pt-BR>
<ru-RU>
Первый выпуск.
Доведи меч до +50, собери семь семейств и разгадай уникальные мечи по одним подсказкам.
24 охотничьи зоны со 144 монстрами, бесконечный коридор, 24 питомца, коллекция на 174 ячейки.
Играется на 13 языках.
</ru-RU>
<th>
เปิดตัวครั้งแรก
เสริมพลังดาบให้ถึง +50 เก็บครบทั้งเจ็ดสาย และไขดาบเฉพาะตัวจากเบาะแสเพียงอย่างเดียว
พื้นที่ล่าสัตว์ 24 โซน 144 ชนิด โถงอนันต์ สัตว์เลี้ยง 24 ชนิด สมุดภาพ 174 ช่อง
เล่นได้ 13 ภาษา
</th>
<vi>
Bản phát hành đầu tiên.
Đưa một thanh kiếm lên +50, gom đủ bảy hệ, và giải ra kiếm độc đáo chỉ bằng gợi ý.
24 vùng săn với 144 loại quái, hành lang vô tận, 24 thú cưng, bộ sưu tập 174 ô.
Chơi được bằng 13 ngôn ngữ.
</vi>
<zh-CN>
首次发布。
把剑强化到 +50，集齐七个系列，只凭线索解开独有之剑。
狩猎场 24 个区域 144 种怪、无限回廊、24 种宠物、174 格图鉴。
支持 13 种语言。
</zh-CN>
<zh-HK>
首次發布。
把劍強化到 +50，集齊七個系列，凈係靠線索解開獨有之劍。
狩獵場 24 個區域 144 種怪、無限迴廊、24 種寵物、174 格圖鑑。
支援 13 種語言。
</zh-HK>
<zh-TW>
首次發布。
把劍強化到 +50，集齊七個系列，只憑線索解開獨有之劍。
狩獵場 24 個區域 144 種怪、無限迴廊、24 種寵物、174 格圖鑑。
支援 13 種語言。
</zh-TW>
```
