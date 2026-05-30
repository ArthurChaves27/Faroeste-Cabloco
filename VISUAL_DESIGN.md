# Faroeste Caboclo — Design Bible & Guia Visual

Documento de referência para geração de assets via inteligências artificiais generativas, consistência visual entre atos e identidade artística do projeto. Deve ser consultado antes de qualquer geração de sprite, background ou elemento de interface.

---

## Identidade Visual

**Estilo artístico:** Pixel art de alta fidelidade, sprites com shading detalhado e paletas restritas por ato. Resolução base de 48×48px a 64×64px por frame de personagem.

**Engine:** Godot 4

**Referência de jogabilidade:** Celeste — plataforma de precisão com narrativa emocional integrada à mecânica de movimento.

**Estética central:** Cangaço nordestino brasileiro encontra pixel art cinematográfico. Baseado na canção _Faroeste Caboclo_ de Renato Russo (Legião Urbana, 1987). A narrativa é uma tragédia social com linguagem visual de cordel e violência poética — sertão seco no início, asfalto periférico no fim.

**Tom geral:** Drama social / Faroeste urbano brasileiro / Tragédia de formação

---

## Diretrizes Gerais de Arte

As instruções abaixo devem ser incluídas como base em todo prompt gerado para assets deste jogo:

```
Pixel art style, detailed character sprites with shading, restricted color palette per scene,
Brazilian northeastern cangaço aesthetic, dramatic cinematic lighting, high contrast shadows,
16-bit to 32-bit pixel art fidelity, no anti-aliasing, no smooth gradients, no anime influence.
```

**Restrições visuais — nunca aplicar:**
- Influência de estilo anime ou mangá
- Paletas com tons pastel sem contraste definido
- Outline branco simples sem shading interno
- Cenários genéricos sem referência cultural brasileira
- Iluminação plana sem profundidade de sombra

---

## João de Santo Cristo — Evolução Visual por Ato

O protagonista muda de aparência a cada ato para refletir sua transformação emocional, social e moral. Figurino, expressão, postura e acessórios devem variar de forma legível entre as fases. As imagens da pasta `/Jogo` são referências de estilo de sprite — a aparência final de cada ato será definida pelos prompts deste documento.

**Traços físicos fixos em todos os atos:**
- Homem negro brasileiro, corpo jovem e ágil
- Cabelos escuros, curtos
- Pele de tom médio-escuro com shading detalhado em pixel art
- Estrutura corporal magra, postura que muda conforme o estado emocional

---

## Paleta de Cores e Visual por Ato

---

### ATO 1 — A Infância e a Fuga

**Localização:** Fazenda no interior do Nordeste brasileiro, zona rural do sertão, anos 1920.

**Descrição do ambiente:** Chão de terra rachada, vegetação de caatinga rala e amarelada, casas de adobe com paredes descascadas, cercas de madeira velha. Luz solar implacável e sem sombra suave — o calor é visível. Poeira suspensa no ar. Ambiente que transmite pobreza estrutural e violência silenciosa. Não há cor que não seja cansada pelo sol.

**Clima emocional:** Pobreza, abandono, revolta contida, violência aprendida desde cedo.

#### Paleta

| Nome | Hex | Papel visual |
|------|-----|--------------|
| Areia Rachada | `#C8A96E` | Cor dominante do chão e paredes de adobe; base quente e pálida do ambiente |
| Ocre Queimado | `#8B5E3C` | Troncos secos, raízes expostas, terra mais profunda; médio-tom térreo |
| Sangue Seco | `#6B1A1A` | Acento dramático de violência; usado em respingos, ferimentos, detalhes de perigo |
| Calor Branco | `#E8D5A3` | Céu lavado pelo calor, sem azul; claridade opressiva que apaga detalhes |
| Sombra do Sertão | `#2A1A0E` | Sombras densas sob telhados de palha, cantos de adobe; escuridão quente |
| Caatinga Murcha | `#4A5C2A` | Vegetação residual; verde dessaturado que mal contrasta com o amarelo do chão |

#### João — Ato 1

Criança de 8 a 10 anos no início, adolescente de 14 a 15 anos ao fim do ato. Descalço durante toda a fase. Roupas rasgadas e remendadas em tecido de algodão cru desbotado — sem chapéu, sem arma. Expressão de revolta latente misturada com medo. Postura encolhida mas olhar desafiador. A sujeira nas roupas e na pele é parte do design, não acidente.

```
Pixel art character sprite, young Black Brazilian boy, age 8 to 15 depending on scene,
barefoot, wearing torn and patched cotton clothes in faded beige and dirty brown tones,
no hat, no weapons, short dark hair, dark skin with detailed pixel shading.
Expression shifts from frightened to quietly furious across the act.
Hunched posture with defiant eyes. Dust and dirt integrated into costume design.
Background: cracked sertão ground, sparse caatinga vegetation, blinding pale sky.
Color palette anchored in #C8A96E, #8B5E3C, #2A1A0E. Hard dramatic top-lighting,
no soft gradients. Northeastern Brazil 1920s. No anti-aliasing.
```

---

### ATO 2 — Salvador: O Começo da Viagem

**Localização:** Salvador, Bahia. Centro histórico, porto, ruas coloniais, anos 1920.

**Descrição do ambiente:** Casarões coloniais com fachadas em azulejo português em tons de amarelo-ocre e branco envelhecido. Ladeiras de pedra com vegetação tropical emergindo entre as construções. O mar aparece ao fundo como linha azul-escura. Luz mais difusa que no sertão — menos agressiva, mais esperançosa. Movimento de pessoas, carroças, barcos no porto. O ambiente tem cor e vida pela primeira vez na história, mas ainda carrega textura de pobreza e esforço.

**Clima emocional:** Espanto diante da cidade, esperança frágil, desorientação do migrante.

#### Paleta

| Nome | Hex | Papel visual |
|------|-----|--------------|
| Azul Baía | `#1A4A7A` | Mar de Salvador ao fundo; tom profundo e distante, âncora de esperança |
| Colonial Desbotado | `#F0E8D0` | Paredes envelhecidas, caiação amarelada; base clara do cenário urbano |
| Amarelo Pelourinho | `#D4A017` | Fachadas iluminadas, detalhes arquitetônicos; único tom quente vibrante |
| Terracota Úmida | `#A0522D` | Telhados de telha colonial, calçada de pedra molhada pelo orvalho |
| Sombra Portuária | `#0D2B45` | Noite no porto, interior de galpões; azul-escuro denso e frio |
| Verde Tropical | `#2E7D32` | Vegetação que cresce entre pedras e muros; presença viva e orgânica |

#### João — Ato 2

Jovem de cerca de 17 a 18 anos, chegando à cidade pela primeira vez. Ainda sem chapéu. Usa roupas simples de viagem — camisa de algodão em tom azul-acinzentado desbotado, calça escura com remendos, sapatos velhos. Carrega um pequeno embrulho de pertences. Postura de quem não sabe onde está, olhos abertos e em alerta, expressão misturando admiração e insegurança. Nenhum elemento de cangaço ainda presente.

```
Pixel art character sprite, young Black Brazilian man, 17 to 18 years old,
wearing simple worn travel clothes: faded blue-grey cotton shirt, dark patched trousers,
old leather shoes with visible wear. No hat. Carrying a small tied cloth bundle.
Expression of wide-eyed disorientation mixed with cautious hope. Open alert posture.
Dark skin with detailed pixel shading. Short dark hair. No weapons.
Background: Salvador colonial architecture, yellow-ochre building facades,
cobblestone street, distant ocean line. Color palette: #1A4A7A, #D4A017, #0D2B45.
Diffused warm coastal light. 1920s Brazil. No anti-aliasing. Pixel art style.
```

---

### ATO 3 — Brasília e a Vida de Trabalhador

**Localização:** Taguatinga e Asa Norte, Brasília. Canteiros de obra, pensões de trabalhador, festas de periferia. Anos 1950-60 (período de construção de Brasília, adaptado ao universo do jogo).

**Descrição do ambiente:** Cenário dual — durante o dia, canteiros imensos de concreto bruto sob céu aberto do cerrado, pó de cimento no ar, andaimes de madeira, trabalhadores de coturnos. À noite, ruas de terra batida de Taguatinga com luzes amarelas fracas, bares simples com som de forró, grupos de migrantes nordestinos. O contraste entre a grandiosidade da obra e a precariedade da vida operária é o elemento visual central.

**Clima emocional:** Encantamento inicial com a cidade nova, frustração crescente com a injustiça social, primeiros contatos com o submundo.

#### Paleta

| Nome | Hex | Papel visual |
|------|-----|--------------|
| Concreto Bruto | `#8A9BA8` | Superfícies de concreto armado, estruturas inacabadas; frio e industrial |
| Cerrado Seco | `#A0784A` | Solo do planalto central, vegetação de cerrado; terra avermelhada |
| Céu do Planalto | `#2C5F8A` | Céu aberto e alto de Brasília; azul mais intenso que o da costa |
| Poeira de Obra | `#C4A882` | Pó de cimento no ar, paredes de bloco inacabadas; bege empoeirado |
| Ferrugem | `#8B3A2A` | Ferramentas, vergalhões oxidados, detalhes de trabalho braçal |
| Noite Periférica | `#0F1F2E` | Ruas de Taguatinga à noite; azul quase preto com textura urbana |

#### João — Ato 3

Homem de 19 a 22 anos. Agora usa roupas de trabalho: camisa de algodão bege-escuro com mangas dobradas, calça de brim marrom, cinto de couro simples, botas de trabalho cobertas de poeira. Sem chapéu durante o trabalho, às vezes usa um boné de tecido. Expressão de determinação desgastada — trabalha muito, ganha pouco, começa a questionar. Corpo mais forte que no ato anterior. Sem armas visíveis, mas postura defensiva começa a aparecer.

```
Pixel art character sprite, Black Brazilian man, 19 to 22 years old, construction worker.
Wearing beige-brown cotton work shirt with rolled sleeves, brown canvas trousers,
simple leather belt, dusty work boots. No hat or simple cloth cap.
Expression of exhausted determination with underlying disillusionment.
Stronger build than Act 1 and 2. No weapons. Hands visibly calloused.
Dark skin with detailed pixel shading. Short dark hair.
Background: Brasília construction site, raw concrete structures, open cerrado sky,
dust in the air, wooden scaffolding. Color palette: #8A9BA8, #2C5F8A, #0F1F2E.
Hard overhead midday lighting on site; dim yellow artificial light for night scenes.
1950s-60s Brazil. No anti-aliasing. Pixel art style.
```

---

### ATO 4 — O Traficante Santo Cristo

**Localização:** Periferias de Brasília — Planaltina, becos de Taguatinga, lotes abandonados de Ceilândia. Noite predominante.

**Descrição do ambiente:** Ruas de asfalto rachado com buracos, postes de luz solitários que mal iluminam, muros pichados, bares fechados com grade, carros velhos estacionados. Nenhuma vegetação. O ambiente é inteiramente construído pelo descaso urbano. As sombras são longas e os pontos de luz criam ilhas de visibilidade num mar de escuridão. A periferia de Brasília como território de abandono e controle paralelo.

**Clima emocional:** Ascensão criminosa, poder corrompido, paranoia crescente, violência como instrumento cotidiano.

#### Paleta

| Nome | Hex | Papel visual |
|------|-----|--------------|
| Ouro Corrompido | `#B8860B` | Adornos de riqueza criminosa, detalhes dourados no figurino; poder sujo |
| Verde Poder | `#1A4A1A` | Acentos de território e dinheiro; presente em elementos de status |
| Preto Autoridade | `#0A0A0A` | Roupas de status, fundos noturnos; presença que absorve luz |
| Vermelho Sangue | `#8B0000` | Violência direta, perigo imediato, detalhes de armas |
| Asfalto | `#3A3A3A` | Superfície das ruas periféricas; tom neutro-frio dominante |
| Roxo Paranoia | `#3D1A5C` | Sombras com tonalidade psicológica; tensão invisível mas presente |

#### João — Ato 4

Homem de 22 a 26 anos. Visual totalmente transformado — agora usa o chapéu de cangaceiro de couro escuro com ornamento de caveira, bandana vermelha no pescoço, colete de couro marrom-escuro com detalhes em metal dourado, calças escuras e botas de cano alto. Carrega espingarda ou rifle com naturalidade. Expressão de autoridade fria, olhar calculista. Postura dominante, ombros para trás, espaço ocupado com intenção. A roupa é cara mas tem a brutalidade do cangaço.

```
Pixel art character sprite, Black Brazilian man, 22 to 26 years old, criminal boss.
Wearing dark leather cangaceiro hat with brass skull ornament, red bandana tied at neck,
dark brown leather vest with gold metal details, dark trousers, tall leather boots.
Holding a shotgun or lever-action rifle with practiced ease. Cold commanding expression,
calculating eyes, dominant wide stance. Expensive but brutal outfit.
Dark skin with detailed pixel shading. Short dark hair.
Background: Brasília periphery at night, cracked asphalt, single streetlamp,
graffiti-covered walls. Color palette: #B8860B, #0A0A0A, #8B0000, #3D1A5C.
Dramatic low-angle lighting, deep purple-tinged shadows. No anti-aliasing. Pixel art style.
```

---

### ATO 5 — O Amor de Maria Lúcia

**Localização:** Zona residencial simples de Brasília. Casa de alvenaria humilde, quintal com terra batida, rua tranquila. Dia e entardecer.

**Descrição do ambiente:** Primeiro ambiente genuinamente doméstico e em paz do jogo. Casa pequena de tijolo com janelas de madeira, quintal com alguns vasos de planta, luz de fim de tarde entrando pelas frestas. Sem elementos de violência ou criminalidade no quadro. A paleta é a mais quente e suave da narrativa — o único momento de respiro visual antes do colapso final. Mesmo a pobreza do ambiente parece digna aqui.

**Clima emocional:** Esperança genuína, amor correspondido, tentativa de redenção, vulnerabilidade.

#### Paleta

| Nome | Hex | Papel visual |
|------|-----|--------------|
| Rosa Seco | `#D4607A` | Presença de Maria Lúcia, elementos de afeto; único tom verdadeiramente quente |
| Branco Envelhecido | `#F5F0E8` | Paredes da casa, tecido limpo; pureza dentro de limitação |
| Amarelo Entardecer | `#F0C040` | Luz de fim de tarde entrando pela janela; esperança temporária |
| Azul Sereno | `#4A7AAA` | Céu tranquilo, detalhes que remetem à paz interior |
| Bege Doméstico | `#D4B896` | Piso de cimento, móveis simples, tecidos da casa |
| Verde Vaso | `#5A9A5A` | Plantas do quintal; vida cultivada com cuidado |

#### João — Ato 5

Homem de 26 a 28 anos. Retorna ao visual civil. Sem chapéu. Sem armas visíveis. Usa camisa limpa em tom claro — bege ou branco gasto —, calça de brim escura simples, sapatos modestos mas conservados. Expressão aberta, olhar que ainda carrega peso mas escolheu soltar. Postura relaxada, ombros caídos sem tensão. O contraste com o ato anterior é total e intencional: o mesmo corpo, outra pessoa.

```
Pixel art character sprite, Black Brazilian man, 26 to 28 years old, civilian at peace.
Wearing clean light-coloured shirt in faded white or beige, simple dark canvas trousers,
modest well-kept shoes. No hat. No weapons. No cangaceiro elements.
Expression of genuine openness with residual sadness in the eyes. Relaxed posture,
shoulders down, arms at ease. This is the same man as Act 4 but visually transformed by choice.
Dark skin with detailed pixel shading. Short dark hair.
Background: simple Brasília residential house, warm late-afternoon light through window,
small yard with potted plants. Color palette: #D4607A, #F0C040, #4A7AAA, #D4B896.
Soft warm directional lighting, minimal shadows. No anti-aliasing. Pixel art style.
```

---

### ATO 6 — A Conspiração e o Rival

**Localização:** Planaltina e bares de periferia, Brasília. Interior de estabelecimentos com pouca luz, ruas desertas à noite.

**Descrição do ambiente:** Ambientes fechados e opressivos — bares com mesas de madeira úmida, luz de neon amarelada queimada, fumaça de cigarro que opacifica o ar. Ruas desertas com névoa baixa. Nenhum espaço aberto e seguro: paredes sempre próximas, saídas bloqueadas visualmente. O ambiente físico espelha o fechamento das possibilidades de João. Jeremias existe aqui como presença ameaçadora ainda não revelada diretamente.

**Clima emocional:** Paranoia, traição iminente, retorno forçado ao crime, tensão sem saída visível.

#### Paleta

| Nome | Hex | Papel visual |
|------|-----|--------------|
| Verde Opressivo | `#2A4A1A` | Paredes mofadas, ambiente fechado; verde que sufoca |
| Amarelo Desconfiança | `#8A7A00` | Luz de neon queimada, reflexo em superfícies sujas |
| Marrom Ambíguo | `#4A2A0A` | Móveis velhos, madeira escura, neutralidade moral deteriorada |
| Cinza Névoa | `#5A5A6A` | Névoa das ruas, fumaça de cigarro; percepção distorcida |
| Vermelho Alerta | `#6A0000` | Detalhes de perigo latente, elementos que sinalizam ameaça |
| Preto Conspiração | `#050505` | Cantos sem luz, silhuetas de ameaça, segredos não ditos |

#### João — Ato 6

Homem de 28 a 30 anos. Visual em transição — os elementos do cangaço voltam, mas de forma desgastada e reluctante. Chapéu recolocado mas amassado, bandana vermelha amarrada sem cuidado, casaco escuro sobre camisa civil. Arma presente mas não ostentada. Postura de quem olha por cima do ombro. Expressão tensa, olhos em movimento, testa franzida. A roupa é uma colagem contraditória entre o homem que queria ser e o que o sistema o força a voltar a ser.

```
Pixel art character sprite, Black Brazilian man, 28 to 30 years old, caught between lives.
Wearing crumpled cangaceiro leather hat returned but dented, loosely tied red bandana,
dark coat over a civilian shirt, dark trousers. Weapon holstered or at side, not raised.
Expression of tense paranoia: eyes scanning, jaw tight, slight backward lean.
Cangaceiro elements present but worn and reluctant, not dominant.
Dark skin with detailed pixel shading. Short dark hair.
Background: dimly lit periphery bar or empty night street, Planaltina.
Color palette: #2A4A1A, #8A7A00, #6A0000, #050505.
Split harsh lighting from single neon source, deep oppressive shadows. No anti-aliasing. Pixel art style.
```

---

### ATO 7 — A Traição

**Localização:** Interior da casa de João, Brasília. Cena noturna.

**Descrição do ambiente:** O mesmo espaço doméstico do Ato 5 — agora irreconhecível. A luz quente sumiu. Apenas uma fonte de luz fraca e lateral. Os mesmos móveis simples agora parecem cenário de colapso. A casa que era símbolo de recomeço torna-se testemunha da traição. Não há necessidade de dramatizar o espaço com elementos externos — a violência emocional acontece no ambiente mais íntimo possível.

**Clima emocional:** Devastação, raiva que paralisa, dor que se converte em decisão de morte.

#### Paleta

| Nome | Hex | Papel visual |
|------|-----|--------------|
| Vermelho Traição | `#7A0000` | Emoção dominante do ato; raiva e dor como cor |
| Preto Colapso | `#0A0505` | Escuridão emocional; fundos que consomem |
| Cinza Vazio | `#3A3040` | Neutralidade do luto; espaço entre a dor e a decisão |
| Roxo Fúria | `#4A0A5A` | Raiva que não encontra saída; cor da violência contida |
| Branco Memória | `#E8E8F0` | Flashes de memória de Maria Lúcia; claridade dolorosa |
| Laranja Brasa | `#8A3A00` | Ódio que queima devagar; transição para a decisão do duelo |

#### João — Ato 7

Mesmo figurino do Ato 6, mas em colapso total. Chapéu tombado ou no chão. Bandana afrouxada. Rifles apertado com as duas mãos por desespero, não por ameaça. Postura curvada pelo peso emocional, ombros para frente. Expressão de devastação que começa a solidificar em determinação letal. Olhos vermelhos, rosto tenso. Este é o momento de virada — a decisão do duelo nasce aqui.

```
Pixel art character sprite, Black Brazilian man, full cangaceiro outfit but in emotional collapse.
Hat fallen or tilted heavily, red bandana loose, dark coat open. Gripping rifle with both hands
in grief, not aggression. Posture collapsed forward, shoulders bearing invisible weight.
Face showing devastation shifting to cold deadly resolve. Eyes red, jaw clenched.
Dark skin with detailed pixel shading. Short dark hair.
Background: dimly lit interior of a simple Brasília home, single weak light source,
familiar domestic furniture now alien. Color palette: #7A0000, #0A0505, #4A0A5A, #8A3A00.
Single harsh lateral light, deep monochromatic shadows. No anti-aliasing. Pixel art style.
```

---

### ATO 8 — O Duelo Final

**Localização:** Ceilândia — Lote 14. Rua aberta, fim de tarde com pôr do sol. Multidão ao redor.

**Descrição do ambiente:** Rua larga de terra batida em Ceilândia com lotes vazios ao fundo. Pôr do sol dramático tingindo tudo de laranja-vermelho. Multidão de moradores formando corredor visual. Câmeras de televisão no canto direito — o espetáculo público da tragédia. Poeira levantada pelo vento. O ambiente tem a grandiosidade de um palco involuntário: a periferia que o Brasil ignora agora transmitida ao vivo. Luz natural contra-luz criando silhuetas.

**Clima emocional:** Espetáculo trágico, inevitabilidade, lenda nascendo em tempo real, morte com dignidade.

#### Paleta

| Nome | Hex | Papel visual |
|------|-----|--------------|
| Vermelho Ceilândia | `#A00000` | Violência do clímax, sangue, luz de pôr do sol no limite |
| Dourado Lenda | `#C8A000` | Aura mítica de João; o herói popular que a elite não reconhece |
| Preto Final | `#050505` | Morte, encerramento, silhuetas contra o céu |
| Branco Holofote | `#F0F0F0` | Luz de câmera de TV, atenção pública; violência midiatizada |
| Cinza Poeira | `#4A4040` | Terra batida, poeira em suspensão, textura do chão |
| Laranja Fim | `#C85A00` | Pôr do sol que encerra uma era; luz que transforma tudo em tragédia épica |

#### João — Ato 8

Mesmo homem, figurino de cangaceiro em estado máximo e deliberado — como se tivesse vestido para morrer com identidade. Chapéu de couro grande e ornamentado, bandana vermelha bem amarrada, colete com detalhes em latão, Winchester 22 levantada. Expressão de serenidade trágica — não há mais medo, só decisão. Postura ereta, quase estática. Silhueta icônica contra o pôr do sol. Este é o frame que se torna pôster.

```
Pixel art character sprite, Black Brazilian man, iconic cangaceiro appearance at its peak.
Large ornate dark leather hat with brass details, tight red bandana, brown leather vest
with brass fittings, dark trousers, tall boots. Holding Winchester rifle raised and level.
Expression of tragic serenity — no fear, only finality. Upright still posture, silhouetted
against sunset. This is a man who chose how he dies.
Dark skin with detailed pixel shading. Short dark hair.
Background: Ceilândia open dirt street, crowd of onlookers forming visual corridor,
TV camera crew at edge, dramatic orange-red sunset backlighting, dust in air.
Color palette: #A00000, #C8A000, #C85A00, #050505.
Strong backlit silhouette lighting, high contrast. No anti-aliasing. Pixel art style.
```

---

### Epílogo — O Mito

**Localização:** Brasília. Imagem estática ou sequência de telas finais com estética de xilogravura de cordel.

**Descrição do ambiente:** O ambiente do epílogo abandona o realismo e adota a linguagem visual da literatura de cordel nordestina: xilogravura, contorno grosso, áreas de cor sólida, composição frontal e simbólica. João não aparece mais como sprite de gameplay — torna-se imagem de lenda. A crítica social do jogo é explicitada visualmente aqui.

**Clima emocional:** Lamento coletivo, crítica à desigualdade, transformação do homem em símbolo.

#### Paleta

| Nome | Hex | Papel visual |
|------|-----|--------------|
| Sépia Memória | `#8B7355` | Cor base da xilogravura; passado que não apaga |
| Dourado do Povo | `#B8960C` | Lenda popular, mito nordestino, o que o povo guarda |
| Cinza Esquecimento | `#6A6A6A` | O que a elite desacredita; neutralidade do poder |
| Branco Cordel | `#F5F0E0` | Papel de cordel, fundo de xilogravura |
| Preto Tinta | `#1A1A1A` | Traço de gravura, texto, contorno da lenda |
| Vermelho Revolta | `#8A0000` | A injustiça que permanece; o que a morte de João não resolve |

---

## Cenários — Referências de Background por Ato

| Ato | Localização | Elementos Visuais Obrigatórios | Iluminação |
|-----|------------|-------------------------------|------------|
| 1 | Sertão Nordestino | Caatinga rala, chão rachado, casa de adobe, cercas velhas, poeira | Solar vertical, sem sombra suave |
| 2 | Salvador colonial | Casarões em azulejo, ladeiras de pedra, baía ao fundo, movimento de porto | Luz costeira difusa, quente |
| 3 | Brasília em obras / Taguatinga | Concreto bruto, andaimes, céu aberto do cerrado, ruas de terra à noite | Dia: topo duro; Noite: neon fraco |
| 4 | Periferias de Brasília | Asfalto rachado, muros pichados, postes isolados, ausência de vegetação | Contraluz baixo, sombras longas |
| 5 | Residência simples, Brasília | Casa de tijolo, quintal com vasos, janela com luz de tarde, quietude | Entardecer suave, lateral quente |
| 6 | Planaltina / bares de periferia | Interior fechado, neon queimado, fumaça, rua deserta com névoa | Neon split, sombras opressivas |
| 7 | Interior da casa de João | Mesmos elementos do Ato 5, esvaziados de calor | Fonte única fraca, lateral fria |
| 8 | Ceilândia — Lote 14 | Rua de terra, multidão, câmeras de TV, lotes vazios, pó no ar | Contraluz pôr do sol, laranja-vermelho |

**Prompt base para backgrounds:**

```
Pixel art background scene, Brazilian setting, [DESCRIÇÃO ESPECÍFICA DO LOCAL E ATO],
cinematic pixel art style, layered parallax depth, dramatic atmospheric lighting,
detailed environmental storytelling, restricted color palette per act,
no modern anachronistic elements, no anti-aliasing, no smooth gradients.
```

---

## Personagens Secundários

| Personagem | Descrição Visual |
|------------|-----------------|
| Maria Lúcia | Mulher jovem brasileira, cabelos escuros compridos, roupas simples e limpas da época, expressão determinada com traço de melancolia. No Ato 8 porta uma Winchester 22. Paleta do Ato 5 predomina em seu design em todos os atos. |
| Pablo | Homem peruano de aparência estrangeira visível, roupas urbanas de contrabandista — chapéu diferente do cangaço, mais associado ao estilo urbano latino-americano dos anos 1950. Tom de pele mediterrâneo. Postura esperta e discreta. |
| Jeremias | Traficante rival de João. Visual mais ostentoso e menos austero que o de João — mais brilho, mais ouro, menos couro. Expressão de arrogância com crueldade calculada. Representa o crime sem a tragédia — é o antagonista sem grandeza. |
| O Boiadeiro | Homem mais velho, figura de vaqueiro brasileiro clássico, pele curtida pelo sol, chapéu de couro simples sem ornamentos, roupas funcionais de sertanejo. Presença sábia e ambígua — um homem que viu demais para se surpreender. |

---

## Especificações Técnicas de Assets

| Parâmetro | Valor |
|-----------|-------|
| Resolução do sprite (personagem) | 48×48px base; 64×64px para cenas de close |
| Escala de exibição | 3× ou 4× pixel perfect |
| Fundo dos sprites | Transparente (PNG-24) |
| Paleta máxima por sprite | 32 cores indexadas |
| Formato de animação | Spritesheet horizontal, frames da esquerda para a direita |
| Resolução de background | 320×180px (resolução base da câmera Godot) |
| Outline de personagem | 1px, cor `#0A0A0A`, sem anti-aliasing |
| Anti-aliasing | Proibido em qualquer asset do projeto |
| Formato de entrega | PNG para sprites e backgrounds; ASEPRITE para arquivos editáveis |

---

## Template de Prompt para Geração de Assets

```
[PERSONAGEM ou CENA] in pixel art style. Brazilian cangaço western aesthetic,
[PERÍODO: 1920s / 1950s] northeastern or central Brazil setting.
[DESCRIÇÃO COMPLETA DO ATO — figurino, expressão, postura, elementos cênicos].
Color palette restricted to: [CORES HEXADECIMAIS DO ATO].
Dramatic pixel art lighting: [TIPO DE LUZ DO ATO].
No anti-aliasing. No smooth gradients. Transparent background for sprites.
~48x48px sprite scale reference. Cinematic composition.
Emotionally expressive character design with detailed pixel shading.
```

---

## Referências de Tom e Atmosfera

O jogo é uma adaptação temática da música _Faroeste Caboclo_ de Renato Russo (Legião Urbana, 1987). A narrativa segue a estrutura dramática da canção e não é uma história original — é uma transposição interativa de um texto já existente na cultura brasileira.

Referências visuais cruzadas úteis para prompts de IA:

- Literatura de cordel nordestina e xilogravura — composição frontal, contorno expressivo, cor simbólica
- Fotografia documental do cangaço real (Lampião e bando, anos 1920-1930) — vestimentas, armas, postura
- Pixel art cinematográfico de Celeste (2018) — resolução, shading emocional, legibilidade de sprite
- Cinema noir brasileiro dos anos 1950-60 — iluminação de contraste, ambiente urbano degradado
- Cordel ilustrado contemporâneo — uso de cor como símbolo, não como descrição naturalista

---

_Documento de desenvolvimento — IFTM Campus Uberlândia — Curso Técnico em Desenvolvimento de Sistemas — 1º ano._
_Versão 1.1 | Engine: Godot 4 | Status: desenvolvimento ativo_
