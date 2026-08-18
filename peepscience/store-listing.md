# 삐약과학 — 플레이스토어 등록 정보 (15개 언어)

앱: 삐약과학 / Peep Science · 패키지 `com.peep.science`

플레이 콘솔 [기본 스토어 등록정보]에서 언어를 추가하며 그대로 붙여 넣는다.
**이 파일 하나로 끝나도록** 한국어 본문까지 여기에 두었다 — 앱 소스 저장소는
비공개가 될 수 있으니, 출시에 필요한 것은 이 저장소 안에 있어야 한다.

## 스토어에 넣을 링크

| 칸 | 주소 |
|---|---|
| 개인정보처리방침 | `https://yongminlee2.github.io/legal/peepscience/privacy.html` |
| 웹사이트 | `https://yongminlee2.github.io/legal/peepscience/` |
| 지원 | `https://yongminlee2.github.io/legal/peepscience/support.html` |

## 잊지 말 것

- 데이터 보안 신고에서 **수집·공유 항목을 하나도 체크하지 않는다.**
  인터넷 권한이 없어 기기 밖으로 보낼 방법 자체가 없다.
- **권한을 하나도 쓰지 않는다.** 권한 목록 자체가 비어 있다.
- 앱 안 언어는 14개(이탈리아어 포함). 콘솔 등록정보는 여기에 中文(香港)을
  더해 15개다 — 홍콩은 앱 안에서 繁體 표를 그대로 쓴다.

**글자 수 제한** — 앱 이름 30자, 짧은 설명 80자, 자세한 설명 4000자.
공백도 한 자로 센다. 아래 문구는 전부 제한 안에 들어가는 것을 확인했다
(`python check-store-listing.py`).

**언어 코드** — 콘솔에서 고를 이름은 다음과 같다.
한국어 / English (United States) / 日本語 / 中文(简体) / 中文(繁體) /
中文(香港) / Español (España) / Português (Brasil) / Deutsch /
Français (France) / Italiano / Русский / Bahasa Indonesia /
Tiếng Việt / ไทย

출시 노트는 `release-notes.txt` 에 언어 묶음표 형식으로 따로 두었다.

---

## 한국어 (ko)

**앱 이름**
```
삐약과학 - 물리 조립 퍼즐 게임
```
**짧은 설명**
```
부품 12종을 조립하고 ▶로 굴리면 진짜 물리로 풀리는 퍼즐. 100스테이지 5개 월드.
```
**자세한 설명**
```
판자를 걸치고 톱니를 맞물려 나만의 장치를 만들고, ▶ 한 번으로 진짜 물리 법칙에 맡겨 보세요.

■ 이런 게 재미있어요
- 스크립트 연출이 아니라 진짜 물리 시뮬레이션 — 공이 구르고 시소가 기울고 톱니가 맞물리는 모든 움직임이 실제 물리 법칙을 따릅니다. 같은 스테이지도 놓는 방식에 따라 다른 장치로 풀 수 있어요.
- 부품 12종의 조합 — 널빤지, 고무공과 쇠공, 풍선, 도미노, 시소, 모터 톱니와 일반 톱니, 노 달린 톱니, 선풍기, 트램펄린, 압정. 무게와 탄성, 바람의 세기가 저마다 다르게 반응해서 같은 상황도 여러 방법으로 풀립니다.
- 5개 테마 월드 × 20스테이지, 총 100스테이지 — 아이 방에서 시작해 뒷마당, 장난감 공장, 우주를 거쳐 최종 관문 삐약 연구소까지. 월드마다 새 부품이 하나씩 열리며 점점 재미있어집니다.
- 실패해도 배치는 그대로 남아요 — 멈추고 조금씩 고쳐가며 다시 도전하면 됩니다. 정답을 외우는 게 아니라 원리를 이해하며 맞춰가는 재미예요.

■ 부품과 월드
공을 굴리고, 시소로 튕겨 보내고, 톱니를 맞물려 동력을 전달하고, 선풍기 바람으로 가벼운 것만 밀어내고… 12가지 부품이 저마다 다른 물리 성질을 가지고 있어서 조합할수록 새로운 방법이 보입니다. 목표도 공을 바구니에 넣기, 버튼 누르기, 풍선 모두 터뜨리기, 도미노 모두 쓰러뜨리기까지 네 가지예요.

그림은 유아 그림책처럼 따뜻하고 둥글게 그렸고, 글자를 몰라도 아이콘만으로 이해할 수 있도록 만들었습니다. 화면은 가로로 고정되어 두 손으로 편하게 잡고 즐길 수 있어요.

아이와 함께, 또는 혼자서도. 내가 만든 장치가 진짜로 움직이는 순간의 재미를 삐약과학에서 만나 보세요.
```

---

## English (en-US)

**앱 이름**
```
Peep Science - Physics Puzzle
```
**짧은 설명**
```
12 parts, real physics, 100 stages in 5 worlds. Build it, run it, watch it work.
```
**자세한 설명**
```
Prop a plank, mesh two gears, place your contraption - then hit play and let real physics take over.

WHAT MAKES IT FUN
- Real physics, not scripted animation. Every ball roll, seesaw tilt, and gear mesh follows an actual simulation, so the same stage can be solved with a different machine every time.
- 12 parts to combine: planks, rubber and metal balls, balloons, dominoes, a seesaw, motor and plain gears, a paddle gear, a fan, a trampoline, and a tack. Weight, bounce, and wind each behave differently, opening up multiple solutions to the same puzzle.
- 100 stages across 5 themed worlds, 20 stages each. Start in a kid's bedroom, move through the backyard, a toy factory and space, and graduate from the Peep Lab. Each world unlocks a new part.
- Fail and your layout stays put. Stop, nudge a few pieces, and try again - it's about understanding how things move, not memorizing an answer.

PARTS AND WORLDS
Roll a ball, launch it off a seesaw, mesh gears to pass along motion, or let a fan push only the lightest pieces - 12 parts each behave differently, so combining them keeps revealing new tricks. Four goal types keep things varied: land a ball in the basket, press the button, pop every balloon, or topple every domino.

The art has a warm, rounded picture-book style, and the whole game reads through icons, so young players can follow it before they can read. The screen stays in landscape, so it sits comfortably in two hands.

Play it solo or side-by-side with your kids - see the machine you built actually work, in Peep Science.
```

---

## Español (es)

**앱 이름**
```
Peep Science - Puzle de Física
```
**짧은 설명**
```
12 piezas, física real y 100 niveles en 5 mundos. Móntalo, pulsa ▶ y observa.
```
**자세한 설명**
```
Apoya una tabla, encaja dos engranajes, coloca tu invento y pulsa ▶: a partir de ahí manda la física de verdad.

LO MÁS DIVERTIDO
- Física real, no animaciones preparadas. Cada pelota que rueda, cada balancín que se inclina y cada engranaje que gira siguen una simulación auténtica, así que un mismo nivel se puede resolver con una máquina distinta cada vez.
- 12 piezas para combinar: tablas, pelotas de goma y de metal, globos, dominós, un balancín, engranajes con motor y engranajes normales, un engranaje con paletas, un ventilador, una cama elástica y una chincheta. El peso, el rebote y el viento reaccionan de forma distinta y abren varias soluciones para el mismo problema.
- 100 niveles en 5 mundos temáticos, 20 en cada uno. Empiezas en el Dormitorio y pasas por el Patio, la Fábrica y el Espacio hasta llegar al Lab Peep. Cada mundo desbloquea una pieza nueva.
- Si sale mal, tu montaje se queda tal cual. Paras, mueves un par de piezas y lo intentas otra vez: aquí se trata de entender cómo se mueven las cosas, no de memorizar la respuesta.

PIEZAS Y MUNDOS
Haz rodar una pelota, lánzala con el balancín, encaja engranajes para transmitir el movimiento o deja que el ventilador empuje solo lo más ligero. Las 12 piezas se comportan de manera diferente, así que combinarlas siempre revela trucos nuevos. Y hay cuatro metas distintas: meter la pelota en la cesta, pulsar el botón, explotar todos los globos o tirar todos los dominós.

Los dibujos son cálidos y redondeados, como los de un cuento infantil, y todo el juego se entiende con iconos: no hace falta saber leer. La pantalla se queda en horizontal, así que el móvil se sujeta cómodamente con las dos manos.

Solo o codo con codo con tus hijos: en Peep Science lo mejor es ver cómo cobra vida de verdad la máquina que acabas de construir.
```

---

## Português (pt-BR)

**앱 이름**
```
Peep Science - Quebra-cabeça
```
**짧은 설명**
```
12 peças, física de verdade, 100 fases em 5 mundos. Monte, aperte ▶ e observe.
```
**자세한 설명**
```
Encoste uma tábua, encaixe duas engrenagens, monte a sua invenção e aperte ▶: daí em diante quem manda é a física de verdade.

POR QUE É DIVERTIDO
- Física de verdade, não animação pronta. Cada bola que rola, cada gangorra que inclina e cada engrenagem que gira seguem uma simulação real, então a mesma fase pode ser resolvida com uma máquina diferente a cada tentativa.
- 12 peças para combinar: tábuas, bolas de borracha e de metal, balões, dominós, uma gangorra, engrenagens com motor e engrenagens comuns, uma engrenagem com pás, um ventilador, uma cama elástica e uma tachinha. Peso, elasticidade e vento reagem de um jeito diferente e abrem várias soluções para o mesmo problema.
- 100 fases em 5 mundos temáticos, 20 em cada um. Você começa no Quarto e passa pelo Quintal, pela Fábrica e pelo Espaço até chegar ao Lab Peep. Cada mundo libera uma peça nova.
- Se der errado, a sua montagem continua ali. É só parar, ajustar algumas peças e testar de novo: aqui a graça é entender como as coisas se movem, não decorar a resposta.

PEÇAS E MUNDOS
Faça a bola rolar, lance-a com a gangorra, encaixe engrenagens para transmitir o movimento ou deixe o ventilador empurrar só o que é bem leve. As 12 peças se comportam de formas diferentes, então combiná-las sempre revela um truque novo. E são quatro objetivos: bola na cesta, apertar o botão, estourar os balões ou derrubar os dominós.

Os desenhos são quentinhos e arredondados, como os de um livro infantil, e o jogo inteiro se entende pelos ícones: não precisa saber ler. A tela fica sempre na horizontal, então dá para segurar o aparelho com as duas mãos.

Sozinho ou lado a lado com as crianças: no Peep Science o melhor é ver a máquina que você montou funcionando de verdade.
```

---

## Italiano (it)

**앱 이름**
```
Peep Science - Fisica e Puzzle
```
**짧은 설명**
```
12 pezzi, fisica vera e 100 livelli in 5 mondi. Costruisci, premi ▶ e osserva.
```
**자세한 설명**
```
Appoggia una tavola, incastra due ingranaggi, sistema il tuo aggeggio e premi ▶: da lì in poi comanda la fisica vera.

PERCHÉ DIVERTE
- Fisica vera, non animazioni preparate. Ogni palla che rotola, ogni altalena che si inclina e ogni ingranaggio che gira seguono una simulazione autentica: lo stesso livello si può risolvere ogni volta con una macchina diversa.
- 12 pezzi da combinare: tavole, palle di gomma e di metallo, palloncini, domino, un'altalena a bilico, ingranaggi con motore e ingranaggi normali, un ingranaggio con pale, un ventilatore, un tappeto elastico e una puntina. Peso, rimbalzo e vento reagiscono in modo diverso e aprono più soluzioni per lo stesso problema.
- 100 livelli in 5 mondi a tema, 20 ciascuno. Si parte dalla Cameretta e si passa per il Giardino, la Fabbrica e lo Spazio fino al Lab Peep. Ogni mondo sblocca un pezzo nuovo.
- Se va male, la tua costruzione resta dov'è. Basta fermarsi, spostare un paio di pezzi e riprovare: qui conta capire come si muovono le cose, non imparare a memoria la soluzione.

PEZZI E MONDI
Fai rotolare una palla, lanciala con l'altalena, incastra gli ingranaggi per trasmettere il movimento o lascia che il ventilatore spinga solo le cose più leggere. I 12 pezzi si comportano ognuno a modo suo, così combinarli fa sempre scoprire un trucco nuovo. E gli obiettivi sono quattro: la palla nel cesto, premere il pulsante, bucare i palloncini o far cadere i domino.

I disegni sono caldi e arrotondati come quelli di un libro illustrato, e tutto il gioco si capisce dalle icone: non serve saper leggere. Lo schermo resta in orizzontale, così si tiene comodamente con due mani.

Da solo o insieme ai bambini: in Peep Science la parte più bella è vedere funzionare davvero la macchina che hai costruito.
```

---

## Français (fr)

**앱 이름**
```
Peep Science - Jeu de Physique
```
**짧은 설명**
```
12 pièces, vraie physique, 100 niveaux, 5 mondes. Construis, lance ▶, observe.
```
**자세한 설명**
```
Cale une planche, emboîte deux engrenages, installe ta machine et appuie sur ▶ : à partir de là, c'est la vraie physique qui décide.

POURQUOI C'EST AMUSANT
- De la vraie physique, pas une animation préparée. Chaque balle qui roule, chaque balançoire qui bascule et chaque engrenage qui tourne suivent une simulation réelle : un même niveau se résout avec une machine différente à chaque fois.
- 12 pièces à combiner : planches, balles en caoutchouc et en métal, ballons, dominos, une balançoire à bascule, des engrenages à moteur et des engrenages simples, un engrenage à palettes, un ventilateur, un trampoline et une punaise. Le poids, le rebond et le vent réagissent chacun à leur manière et ouvrent plusieurs solutions au même problème.
- 100 niveaux répartis en 5 mondes à thème, 20 par monde. On commence dans la Chambre, puis le Jardin, l'Usine et l'Espace, jusqu'au Labo Peep. Chaque monde débloque une nouvelle pièce.
- Si ça rate, ton montage reste en place. Tu arrêtes, tu déplaces deux ou trois pièces et tu recommences : l'idée est de comprendre comment les choses bougent, pas d'apprendre une réponse par cœur.

PIÈCES ET MONDES
Fais rouler une balle, envoie-la avec la balançoire, emboîte des engrenages pour transmettre le mouvement ou laisse le ventilateur pousser seulement le plus léger. Les 12 pièces réagissent chacune différemment, donc les combiner révèle toujours une nouvelle astuce. Et il y a quatre objectifs : la balle dans le panier, appuyer sur le bouton, éclater les ballons ou faire tomber les dominos.

Les dessins sont chaleureux et tout en rondeurs, comme dans un album jeunesse, et le jeu se comprend entièrement par les icônes : pas besoin de savoir lire. L'écran reste à l'horizontale, ce qui permet de tenir le téléphone à deux mains.

Seul ou à côté de tes enfants : dans Peep Science, le plus beau, c'est de voir la machine que tu as construite fonctionner pour de vrai.
```

---

## 日本語 (ja)

**앱 이름**
```
Peep Science - 物理組み立てパズル
```
**짧은 설명**
```
パーツ12種を組んで▶を押すと、本物の物理で動きだす。5つの世界に100ステージ。
```
**자세한 설명**
```
板を渡し、歯車をかみ合わせ、自分だけの装置を組み上げたら、▶をひと押し。あとは本物の物理法則にまかせます。

■ ここが楽しい
・演出ではなく本物の物理シミュレーション — ボールが転がり、シーソーが傾き、歯車がかみ合う。そのすべてが実際の物理法則にしたがって動きます。同じステージでも、置き方しだいで別の装置で解けます。
・パーツ12種の組み合わせ — 板、ゴムボールと鉄球、ふうせん、ドミノ、シーソー、モーター歯車と普通の歯車、羽根つき歯車、扇風機、トランポリン、画びょう。重さも弾みも風の強さもそれぞれ違うので、同じ場面がいくつもの方法で解けます。
・5つのテーマ世界 × 20ステージ、あわせて100ステージ — こども部屋からはじまり、うらにわ、おもちゃ工場、うちゅうを通って、最後の関門ピープ研究所まで。世界がひとつ進むごとに新しいパーツがひとつ開きます。
・失敗しても置いたパーツはそのまま — 止めて、少しずつ直して、もう一度ためせます。答えをおぼえるのではなく、しくみがわかっていく楽しさです。

■ パーツと世界
ボールを転がし、シーソーではじき飛ばし、歯車をかみ合わせて力を伝え、扇風機の風で軽いものだけを押しやる。12種のパーツがそれぞれ違う物理の性質を持っていて、組み合わせるほど新しい手が見えてきます。目標も4種類 — ボールをかごに、ボタンをおす、ふうせんを全部わる、ドミノを全部たおす。

絵は幼児向けの絵本のようにやわらかく丸く描き、字が読めなくてもアイコンだけでわかるようにしました。画面は横向き固定なので、両手で持ってゆっくり遊べます。

お子さんといっしょに、ひとりでも。自分で組んだ装置が本当に動きだす瞬間を、Peep Science で。
```

---

## 中文（简体）(zh-CN)

**앱 이름**
```
Peep Science - 物理组装解谜
```
**짧은 설명**
```
12 种零件组装，按下▶就交给真实物理。5 个世界，共 100 关。
```
**자세한 설명**
```
架一块木板，让两个齿轮咬合，把自己的装置搭好，再按一下▶，剩下的交给真实的物理法则。

■ 好玩在哪里
· 是真实的物理模拟，不是预设动画 —— 球滚动、跷跷板倾斜、齿轮咬合，每一个动作都由模拟算出来。同一关换个摆法，就能用另一台装置通过。
· 12 种零件自由组合 —— 木板、橡胶球和铁球、气球、骨牌、跷跷板、马达齿轮和普通齿轮、带桨齿轮、风扇、蹦床、图钉。重量、弹力和风力各不相同，同一个难题往往有好几种解法。
· 5 个主题世界 × 20 关，共 100 关 —— 从儿童房出发，经过后院、玩具工厂和太空，最后走到皮普实验室。每进入一个新世界，就多解锁一种零件。
· 失败了摆好的零件也不会消失 —— 停下来，挪一挪，再试一次。这里要的不是背答案，而是弄明白东西为什么会动。

■ 零件与世界
让球滚起来，用跷跷板把它弹出去，让齿轮咬合把力传下去，或者用风扇的风只吹动最轻的那个。12 种零件各有各的物理脾气，越组合越能发现新招。目标也有四种：把球投进篮子、按下按钮、戳破所有气球、推倒所有骨牌。

画风像幼儿绘本一样温暖圆润，全程看图标就懂，不识字也能玩。画面横向固定，双手捧着刚刚好。

和孩子一起玩，一个人玩也行。看着自己搭的装置真的动起来，这就是 Peep Science。
```

---

## 中文（繁體）(zh-TW)

**앱 이름**
```
Peep Science - 物理組裝解謎
```
**짧은 설명**
```
12 種零件組裝，按下▶就交給真實物理。5 個世界，共 100 關。
```
**자세한 설명**
```
架一塊木板，讓兩個齒輪咬合，把自己的裝置搭好，再按一下▶，剩下的交給真實的物理法則。

■ 好玩在哪裡
· 是真實的物理模擬，不是預設動畫 —— 球滾動、蹺蹺板傾斜、齒輪咬合，每一個動作都由模擬算出來。同一關換個擺法，就能用另一台裝置通過。
· 12 種零件自由組合 —— 木板、橡膠球和鐵球、氣球、骨牌、蹺蹺板、馬達齒輪和普通齒輪、附槳齒輪、風扇、彈簧床、圖釘。重量、彈力和風力各不相同，同一個難題往往有好幾種解法。
· 5 個主題世界 × 20 關，共 100 關 —— 從兒童房出發，經過後院、玩具工廠和太空，最後走到皮普實驗室。每進入一個新世界，就多解鎖一種零件。
· 失敗了擺好的零件也不會消失 —— 停下來，挪一挪，再試一次。這裡要的不是背答案，而是弄明白東西為什麼會動。

■ 零件與世界
讓球滾起來，用蹺蹺板把它彈出去，讓齒輪咬合把力傳下去，或者用風扇的風只吹動最輕的那個。12 種零件各有各的物理脾氣，越組合越能發現新招。目標也有四種：把球投進籃子、按下按鈕、戳破所有氣球、推倒所有骨牌。

畫風像幼兒繪本一樣溫暖圓潤，全程看圖示就懂，不識字也能玩。畫面橫向固定，雙手捧著剛剛好。

和孩子一起玩，一個人玩也行。看著自己搭的裝置真的動起來，這就是 Peep Science。
```

---

## 中文（香港）(zh-HK)

**앱 이름**
```
Peep Science - 物理組裝解謎
```
**짧은 설명**
```
12 種零件砌埋一齊，撳▶就交畀真實物理。5 個世界，共 100 關。
```
**자세한 설명**
```
架一塊木板，令兩個齒輪咬合，砌好自己嘅裝置，再撳一下▶，餘下嘅交畀真實嘅物理法則。

■ 好玩喺邊度
· 係真實嘅物理模擬，唔係預設動畫 —— 波碌動、搖搖板傾斜、齒輪咬合，每一個動作都係計出嚟嘅。同一關換個擺法，就可以用另一台裝置過。
· 12 種零件自由組合 —— 木板、橡膠波同鐵波、氣球、骨牌、搖搖板、摩打齒輪同普通齒輪、附槳齒輪、風扇、彈床、圖釘。重量、彈力同風力各有唔同，同一個難題通常有好幾種解法。
· 5 個主題世界 × 20 關，共 100 關 —— 由兒童房出發，經過後院、玩具工廠同太空，最後去到皮普實驗室。每入一個新世界，就多解鎖一種零件。
· 失敗咗擺好嘅零件都唔會消失 —— 停低，郁一郁，再試多次。呢度要嘅唔係背答案，而係搞清楚啲嘢點解會郁。

■ 零件同世界
等個波碌起上嚟，用搖搖板彈佢出去，用齒輪咬合將力傳落去，或者用風扇嘅風淨係吹得郁最輕嗰件。12 種零件各有各嘅物理脾性，越夾越搵到新招。目標亦有四種：把球投進籃子、按下按鈕、戳破所有氣球、推倒所有骨牌。

畫風好似幼兒繪本咁溫暖圓潤，全程睇圖示就明，唔識字都玩得。畫面橫向固定，兩隻手揸住啱啱好。

同小朋友一齊玩，一個人玩都得。睇住自己砌嘅裝置真係郁得起，呢個就係 Peep Science。
```

---

## ไทย (th)

**앱 이름**
```
Peep Science - ปริศนาฟิสิกส์
```
**짧은 설명**
```
ประกอบชิ้นส่วน 12 แบบ กด ▶ แล้วปล่อยให้ฟิสิกส์จริงทำงาน 100 ด่าน 5 โลก
```
**자세한 설명**
```
พาดไม้กระดาน ขบเฟืองเข้าด้วยกัน ประกอบเครื่องกลของตัวเองให้เสร็จ แล้วกด ▶ ครั้งเดียว จากนั้นปล่อยให้กฎฟิสิกส์จริงทำงานต่อ

■ สนุกตรงไหน
· เป็นการจำลองฟิสิกส์จริง ไม่ใช่แอนิเมชันที่เขียนไว้ล่วงหน้า — ลูกบอลกลิ้ง ไม้กระดกเอียง เฟืองขบกัน ทุกการเคลื่อนไหวคำนวณจากการจำลองจริง ด่านเดียวกันถ้าวางคนละแบบ ก็ผ่านได้ด้วยเครื่องกลคนละเครื่อง
· ชิ้นส่วน 12 แบบ ผสมกันได้อิสระ — ไม้กระดาน ลูกบอลยางและลูกบอลเหล็ก ลูกโป่ง โดมิโน ไม้กระดก เฟืองมอเตอร์และเฟืองธรรมดา เฟืองติดใบพัด พัดลม แทรมโพลีน และหมุดปัก น้ำหนัก ความเด้ง และแรงลมต่างกันไป โจทย์เดียวกันจึงมีทางแก้ได้หลายทาง
· 5 โลกตามธีม × 20 ด่าน รวม 100 ด่าน — เริ่มจากห้องเด็ก ผ่านหลังบ้าน โรงงาน และอวกาศ ไปจนถึงด่านสุดท้ายที่ห้องแล็บพีป ทุกครั้งที่ขึ้นโลกใหม่ จะได้ชิ้นส่วนใหม่เพิ่มอีกหนึ่งอย่าง
· พลาดแล้วชิ้นส่วนที่วางไว้ยังอยู่ที่เดิม — หยุด ขยับทีละนิด แล้วลองใหม่ได้เลย ที่นี่ไม่ได้ให้ท่องคำตอบ แต่ให้ค่อย ๆ เข้าใจว่าทำไมของถึงเคลื่อนที่

■ ชิ้นส่วนกับโลก
กลิ้งลูกบอล ดีดมันออกไปด้วยไม้กระดก ขบเฟืองเพื่อส่งแรงต่อ หรือใช้ลมจากพัดลมดันเฉพาะของที่เบาที่สุด ชิ้นส่วนทั้ง 12 แบบมีนิสัยทางฟิสิกส์ของตัวเอง ยิ่งผสมยิ่งเจอวิธีใหม่ เป้าหมายก็มีสี่แบบ คือ ส่งลูกบอลลงตะกร้า กดปุ่มให้ได้ ทำลูกโป่งแตกให้หมด และทำโดมิโนล้มให้หมด

ภาพวาดอบอุ่นมนกลมเหมือนหนังสือภาพสำหรับเด็กเล็ก และดูไอคอนก็เข้าใจได้โดยไม่ต้องอ่านหนังสือออก หน้าจอล็อกเป็นแนวนอน จับสองมือได้พอดี

เล่นกับลูก หรือเล่นคนเดียวก็ได้ มาดูช่วงเวลาที่เครื่องกลซึ่งเราประกอบเองขยับได้จริง ใน Peep Science
```

---

## Deutsch (de)

**앱 이름**
```
Peep Science - Physik-Puzzle
```
**짧은 설명**
```
12 Teile, echte Physik, 100 Stufen in 5 Welten. Bauen, ▶ drücken, staunen.
```
**자세한 설명**
```
Ein Brett anlegen, zwei Zahnräder ineinandergreifen lassen, deine Maschine hinstellen - dann auf ▶ tippen und echte Physik übernehmen lassen.

DARUM MACHT ES SPASS
- Echte Physik statt fester Animation. Jeder rollende Ball, jede kippende Wippe, jedes greifende Zahnrad folgt einer echten Simulation. Dieselbe Stufe lässt sich deshalb mit ganz unterschiedlichen Maschinen lösen.
- 12 Teile zum Kombinieren: Bretter, Bälle aus Gummi und Metall, Ballons, Dominosteine, eine Wippe, ein Motor-Zahnrad und ein normales Zahnrad, ein Schaufelrad, ein Ventilator, ein Trampolin und eine Reißzwecke. Gewicht, Sprungkraft und Wind wirken jeweils anders, und so hat jede Aufgabe mehrere Lösungswege.
- 100 Stufen in 5 Themenwelten, je 20 Stufen. Los geht es im Kinderzimmer, dann durch Garten, Fabrik und Weltraum bis ins Peep-Labor. Jede Welt schaltet ein neues Teil frei.
- Ein Fehlversuch räumt nichts weg. Deine Teile bleiben liegen: kurz nachbessern, noch einmal starten. Es geht ums Verstehen, nicht ums Auswendiglernen.

TEILE UND WELTEN
Einen Ball rollen lassen, ihn über die Wippe schleudern, mit Zahnrädern Bewegung weitergeben oder mit dem Ventilator nur die leichten Teile wegpusten - jedes der 12 Teile verhält sich anders, und je mehr du kombinierst, desto mehr Tricks findest du. Vier Aufgabenarten sorgen für Abwechslung: den Ball in den Korb bringen, den Knopf drücken, alle Ballons platzen lassen oder alle Dominos umwerfen.

Die Bilder sind warm und rund wie in einem Bilderbuch, und alles läuft über Symbole - lesen können muss man dafür nicht. Der Bildschirm bleibt im Querformat, so liegt das Gerät bequem in beiden Händen.

Allein oder gemeinsam mit deinem Kind: Sieh in Peep Science zu, wie die selbst gebaute Maschine wirklich läuft.
```

---

## Русский (ru)

**앱 이름**
```
Peep Science - Головоломка
```
**짧은 설명**
```
12 деталей, настоящая физика, 100 уровней в 5 мирах. Собери, нажми ▶, смотри.
```
**자세한 설명**
```
Приставь доску, сцепи две шестерёнки, поставь машину на место - и нажми ▶, дальше всё сделает настоящая физика.

ЧЕМ ЭТО ИНТЕРЕСНО
- Настоящая физика, а не заранее нарисованный мультик. Мяч катится, качели наклоняются, шестерёнки цепляются друг за друга - всё считает настоящая симуляция, поэтому один и тот же уровень можно пройти совсем разными машинами.
- 12 деталей: доски, резиновый и металлический мячи, воздушные шарики, домино, качели, шестерёнка с мотором и обычная, лопастная шестерёнка, вентилятор, батут и гвоздик. Вес, упругость и сила ветра работают по-разному, так что у каждой задачи есть несколько решений.
- 100 уровней в 5 тематических мирах, по 20 в каждом. Начинаем в Детской, дальше Двор, Фабрика, Космос и, наконец, Peep-лаб. В каждом мире открывается новая деталь.
- Не получилось - детали остаются на месте. Останови, поправь пару штук и запусти снова: тут важно понять, как всё движется, а не запомнить ответ.

ДЕТАЛИ И МИРЫ
Прокатить мяч, подбросить его качелями, передать движение через шестерёнки, сдуть вентилятором только самое лёгкое - 12 деталей ведут себя по-разному, и чем больше их сочетаешь, тем больше находишь приёмов. Целей четыре: закинуть мяч в корзину, нажать на кнопку, лопнуть все шарики или уронить все домино.

Рисунки тёплые и круглые, как в книжке с картинками, а всё понятно по значкам - читать не нужно. Экран всегда горизонтальный, поэтому телефон удобно держать двумя руками.

Вместе с ребёнком или в одиночку - посмотри в Peep Science, как оживает машина, которую ты собрал сам.
```

---

## Bahasa Indonesia (id)

**앱 이름**
```
Peep Science - Puzzle Fisika
```
**짧은 설명**
```
12 bagian, fisika sungguhan, 100 level di 5 dunia. Susun, tekan ▶, amati.
```
**자세한 설명**
```
Sandarkan papan, rapatkan dua gir, susun mesinmu - lalu tekan ▶ dan biarkan fisika sungguhan yang bekerja.

SERUNYA DI SINI
- Fisika sungguhan, bukan animasi yang sudah diatur. Bola menggelinding, jungkat-jungkit miring, gir berputar - semuanya dihitung simulasi sungguhan, jadi satu level bisa diselesaikan dengan mesin yang berbeda-beda.
- 12 bagian untuk dipadukan: papan, bola karet dan bola besi, balon, domino, jungkat-jungkit, gir bermotor dan gir biasa, gir berdayung, kipas, trampolin, dan paku payung. Berat, pantulan, dan angin bereaksi berbeda-beda sehingga satu soal punya banyak jalan keluar.
- 100 level di 5 dunia bertema, masing-masing 20 level. Mulai dari Kamar Anak, lanjut ke Halaman Belakang, Pabrik, Angkasa, sampai Lab Peep di ujung. Tiap dunia membuka satu bagian baru.
- Gagal pun susunanmu tetap di tempat. Berhenti sebentar, geser satu dua bagian, lalu coba lagi - yang penting paham cara benda bergerak, bukan menghafal jawaban.

BAGIAN DAN DUNIA
Menggelindingkan bola, melontarkannya lewat jungkat-jungkit, meneruskan tenaga dengan gir, atau memakai kipas untuk mendorong benda yang paling ringan - 12 bagian punya sifat masing-masing, makin dipadukan makin banyak cara baru yang muncul. Tujuannya ada empat: memasukkan bola ke keranjang, menekan tombol, memecahkan semua balon, atau menjatuhkan semua domino.

Gambarnya hangat dan membulat seperti buku cerita anak, dan semuanya dijelaskan lewat ikon sehingga anak yang belum bisa membaca tetap mengerti. Layarnya terkunci mendatar, jadi pas dipegang dengan dua tangan.

Main sendiri atau bersama anak: lihat mesin buatanmu benar-benar hidup di Peep Science.
```

---

## Tiếng Việt (vi)

**앱 이름**
```
Peep Science - Giải đố Vật lý
```
**짧은 설명**
```
12 mảnh ghép, vật lý thật, 100 màn chơi, 5 thế giới. Lắp, nhấn ▶, xem chạy.
```
**자세한 설명**
```
Gác một tấm ván, cho hai bánh răng khớp vào nhau, đặt xong cỗ máy - rồi nhấn ▶ để vật lý thật lo phần còn lại.

ĐIỀU THÚ VỊ Ở ĐÂY
- Vật lý thật, không phải hoạt hình dựng sẵn. Bóng lăn, bập bênh nghiêng, bánh răng ăn khớp - tất cả đều do mô phỏng vật lý tính toán, nên cùng một màn chơi có thể giải bằng những cỗ máy hoàn toàn khác nhau.
- 12 mảnh ghép để kết hợp: tấm ván, bóng cao su và bóng sắt, bóng bay, quân domino, bập bênh, bánh răng có mô tơ và bánh răng thường, bánh răng mái chèo, quạt, bạt nhún và đinh ghim. Trọng lượng, độ nảy và sức gió mỗi thứ một khác nên màn nào cũng có nhiều lời giải.
- 100 màn chơi trong 5 thế giới, mỗi thế giới 20 màn. Bắt đầu từ Phòng bé, qua Sân sau, Nhà máy, Vũ trụ rồi kết thúc ở Lab Peep. Mỗi thế giới mở thêm một mảnh ghép mới.
- Thua cũng không phải xếp lại từ đầu. Các mảnh ghép vẫn nằm nguyên, chỉ cần chỉnh vài chỗ rồi chạy tiếp - cái hay là hiểu vì sao mọi thứ chuyển động, chứ không phải học thuộc đáp án.

MẢNH GHÉP VÀ THẾ GIỚI
Lăn quả bóng, hất nó lên bằng bập bênh, truyền chuyển động qua bánh răng, hay dùng quạt thổi bay những thứ nhẹ nhất - 12 mảnh ghép mỗi thứ một tính nết, càng kết hợp càng ra cách mới. Mục tiêu có bốn kiểu: đưa bóng vào rổ, nhấn vào nút, làm nổ hết bóng bay, hoặc xô đổ hết quân domino.

Nét vẽ ấm áp và bo tròn như truyện tranh thiếu nhi, mọi thứ đều hiện bằng biểu tượng nên bé chưa biết chữ vẫn chơi được. Màn hình luôn nằm ngang, cầm hai tay là vừa.

Chơi một mình hay ngồi cùng con đều được - hãy xem cỗ máy do chính tay mình lắp chạy thật trong Peep Science.
```

---
## 카테고리

- 앱 유형: **게임**
- 카테고리: **퍼즐**
- 태그: 퍼즐, 물리, 조립, 어린이, 교육, 가족

## 데이터 보안 (Data safety) 신고

| 질문 | 답 |
|---|---|
| 데이터를 수집하거나 공유하나요? | **아니요** |
| 전송 중 데이터가 암호화되나요? | 해당 없음 (전송 자체가 없음) |
| 사용자가 데이터 삭제를 요청할 수 있나요? | 해당 없음 (수집하지 않음) |

앱에 **인터넷 권한이 없다.** 기기 밖으로 무엇을 보내는 것이 기술적으로 불가능하다.
진행 상황(클리어·별)은 기기 안에만 저장되고, 앱을 지우면 같이 사라진다.

## 권한

**하나도 쓰지 않는다.** 매니페스트에 권한 선언이 없어 스토어의 권한 목록이 비어 있다.

## 광고·인앱 구매

현재 빌드에는 **둘 다 없다.** 콘텐츠 등급 설문과 데이터 보안 신고에도 없다고 답한다.
나중에 붙일 때는 **개인정보처리방침을 먼저 고치고** 두 신고를 갱신한 뒤 새 빌드를 올린다.

## 콘텐츠 등급

전체이용가. 폭력·공포·선정성·도박 요소가 없고, 이용자 간 소통 기능도 없다.
타깃 연령은 **어린이와 성인 모두**로 신고한다.

## 스크린샷

`PiyakScience/store/업로드/스크린샷/<언어>/` 에 언어마다 일곱 장씩 있다
(홈 · 스테이지 · 부품 배치 · 클리어 · 예측 퀴즈 · 톱니 공장 · 삐약 연구소).
2340×1080, **가로**. 같은 판만 여러 장 넣지 않고 월드와 기믹이 서로 다르게
보이도록 골랐다.
플레이 콘솔은 언어마다 최소 두 장, 최대 여덟 장을 받는다.
언어별로 올리지 않으면 기본 언어(en-US) 것이 대신 쓰인다.

그래픽 자산은 글자가 없어 언어를 타지 않는다 — 아이콘 `store/art/icon_6.png`(512×512),
그래픽 이미지 `store/art/feature_graphic.png`(1024×500).

## 쓰지 않을 표현

설명란에 아래 부류는 한 줄도 쓰지 않는다. 지금은 참이어도 나중에 거짓이 되고,
그때 문구를 지워도 그것을 보고 받은 사람은 남는다.

- 광고 없음 · 인앱결제 없음 · 완전 무료
- 인터넷을 쓰지 않음 · 개인정보를 일절 수집하지 않음 · 오프라인 전용

단 **데이터 보안 설문과 콘텐츠 등급의 「광고 포함」·「인앱 구매」 항목은 반대다.**
그건 마케팅 문구가 아니라 신고 사항이라, 올리는 빌드의 실제 모습대로 적어야 한다.

## 출시 노트

`release-notes.txt` 에 15개 언어가 콘솔 묶음표 형식으로 들어 있다.
콘솔의 출시 노트 칸에 그 파일을 통째로 붙여 넣으면 한 번에 들어간다.
