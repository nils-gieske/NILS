# NILS — Normative Interchange Language Standard

**No setup. No tool. No installation. Nothing.** You can use NILS immediately — anytime, anywhere. Only requirement for conversion: an LLM. That's it.

## How to use it

1. **Copy the Full Header.**
2. **Give any LLM this prompt:**

```
[paste Full Header here]

Translate the following into the Normative Interchange Language Standard (NILS):

[paste your source text here]
```

That's it. No setup. No tooling. No dependencies. Works with GPT, Claude, Gemini, Llama, Mistral — today and in 10 years. To translate back to prose, simply ask the LLM to convert the NILS file into natural language.

---

What JSON did for data and HTML did for the web, **NILS** does for knowledge.

---

## Why NILS?

### As a KNOWLEDGE STORAGE format

✅ **Zero noise, only signal.** Strips prose, filler, and repetition. What remains is pure knowledge essence.<br>
✅ **Single Source of Truth.** Every fact defined once, referenced everywhere, versioned with timestamps and sources.<br>
✅ **Source attribution built in.** Every fact can carry its origin via `^source`. Know where knowledge came from. Always.<br>
✅ **No further transformation needed.** Use directly in databases, RAG retrieval, LLM training, vector stores, and API responses.<br>
✅ **Radical token reduction.** 50–90% fewer tokens depending on source density. Narrative prose: up to 90%. Dense factsheets: ~50%. Typical articles: ~80%.<br>
✅ **Inherently immune to framing, constructed causality, and omission.** SPO structure leaves no room for spin. There is nothing between the lines.<br>
✅ **Structurally resistant to data poisoning.** Rigid SPO syntax rejects malformed entries. The canonical header on GitHub enables verification of any incoming NILS payload before it enters your knowledge base.<br>
✅ **Plain text. Forever readable.** No binary format. No proprietary decoder. Readable today, in 50 years, after a civilizational reset. Like the golden record on Voyager — the instructions are engraved on the cover.<br>

### As a KNOWLEDGE EXCHANGE standard

✅ **Self-describing.** The header explains every symbol and convention. The recipient needs zero prior knowledge of NILS.<br>
✅ **Perfect for MCP.** LLMs exchange knowledge via Model Context Protocol today using JSON — verbose, ambiguous, no causality. NILS delivers the same knowledge in a fraction of the tokens with full SPO structure. Every MCP tool response becomes smaller, clearer, and unambiguous.<br>
✅ **Structurally resistant to prompt injection.** In prose, any word can be an instruction — that's why injection works. In NILS, every line must be `subject.predicate:object`. NILS is purely declarative — it describes what IS, never what SHOULD BE DONE. The canonical header lives on GitHub and can be verified against any incoming payload — modified headers get rejected before reaching the LLM.<br>
✅ **Human, machine, and LLM readable.** Anyone who reads English and understands basic logic can read a NILS file. Every LLM can process it natively.<br>
✅ **No parser, no SDK, no schema, no tooling, no dependencies.** Plain text. That's it.<br>
✅ **One format for everything.** LLM-to-LLM, LLM-to-human, system-to-system, API-to-database — one format, one legend, zero translation overhead.<br>
✅ **Extensible without conflict.** Build domain-specific forks with custom headers. Every file carries its own legend. Forks never collide.<br>
✅ **Works with every LLM.** GPT, Claude, Gemini, Llama, Mistral — any model can read, write, and translate NILS. No fine-tuning. No integration. Just a prompt.<br>

---

## Where NILS fits


|                                                  |              |                     |                  |                            |
| ------------------------------------------------ | ------------ | ------------------- | ---------------- | -------------------------- |
| **📥 RAW DATA**                                  |              |                     |                  |                            |
| Emails                                           | PDFs         | Articles            | Meetings         | Reports · APIs · Databases |
| **Any LLM transforms**                           |              |                     |                  |                            |
| **↕️**                                           | **↕️**       | **↕️**              | **↕️**           | **↕️**                     |
| **⚡ NILS** The knowledge layer all systems share |              |                     |                  |                            |
| **↕️**                                           | **↕️**       | **↕️**              | **↕️**           | **↕️**                     |
| **🔍 RAG**                                       | **🔄 MCP**   | **🧠 LLM Training** | **🗄️ Database** | **👁️ Human**              |
| 10x per chunk                                    | fewer tokens | less noise          | SSOT versioned   | reads directly             |


**One format. Every use case. No translation between systems.**

---

## One article, two formats, one truth


| Format                                 | Tokens        |
| -------------------------------------- | ------------- |
| Encyclopedia article: Strait of Hormuz | ~2,500 tokens |
| The same knowledge in NILS             | ~220 tokens   |


**COMPARISON:** Encyclopedia article vs. NILS

**Strait of Hormuz** (~2,500 tokens)  
The Strait of Hormuz is a strait between the Persian Gulf and the Gulf of Oman. It provides the only sea passage from the Persian Gulf to the open ocean and is one of the world's most strategically important chokepoints. On the north coast lies Iran, and on the south coast lies Oman (specifically the Musandam exclave) and the United Arab Emirates.  
The strait is approximately 39 kilometers wide at its narrowest point, with the shipping lanes consisting of two 3-kilometer-wide channels for inbound and outbound traffic, separated by a 3-kilometer-wide buffer zone. The depth in the shipping lanes ranges from 60 to 90 meters. The islands of Hormuz, Qeshm, and Larak, all controlled by Iran, are located in or near the strait.  
As of 2023, approximately 80 ships transit the strait daily. About 21 million barrels of oil per day flow through the strait, representing roughly 20% of global oil consumption and 33% of all seaborne-traded oil. Additionally, about 4 trillion cubic feet of liquefied natural gas passes through annually, accounting for approximately 18% of global LNG trade. The daily value of trade passing through the strait is estimated at approximately $1.2 billion. The main commodities by global share are oil (20%), LNG (18%), fertilizer (approximately 10%), and petrochemicals (approximately 8%). Major exporters shipping through the strait include Saudi Arabia, Iran, Iraq, Kuwait, the UAE, and Qatar. Major importers receiving goods through the strait include China, India, Japan, South Korea, and the European Union. These statistics are sourced from the U.S. Energy Information Administration and the International Energy Agency.  
Iran controls the northern shore of the strait and operates a naval base at Bandar Abbas. Iran possesses sea mine capability. Iran has repeatedly threatened closure of the strait, specifically in 2012, 2018, and 2022. The United States operates the Fifth Fleet from Bahrain and has maintained a permanent carrier group presence since 1995, guaranteeing free passage through the strait. Iran and the United States represent the primary tension axis in the region.  
In 2019, Iran attacked tankers in the Gulf of Oman. Also in 2019, the United States shot down an Iranian drone. In 2023, the Islamic Revolutionary Guard Corps seized a tanker in the Strait of Hormuz. During periods of high tension, the US and UK provide naval escorts for tankers transiting the strait.  
If the strait were closed, several bypass pipelines could partially offset the lost capacity. The East-West Pipeline operated by Saudi Arabia has a capacity of 5 million barrels per day and delivers to Yanbu on the Red Sea. The Habshan-Fujairah Pipeline operated by the UAE has a capacity of 1.5 million barrels per day. The IPSA Pipeline operated by Iraq has a capacity of 1.65 million barrels per day to Turkey, but it is currently inactive. Total bypass capacity is approximately 7 million barrels per day, which represents only 33% of the strait's normal flow. This bypass capacity is not sufficient for a full closure scenario.  
The probability of closure is assessed as low. If closure occurred, oil prices would likely rise 40-80% within one week. LNG spot prices would rise 200-300%. If the closure lasted more than 3 months, a global recession would be highly probable. Mitigation includes strategic petroleum reserves (US approximately 400 million barrels, China approximately 500 million barrels) and the bypass pipelines.

**The same knowledge in NILS (~220 tokens)**

```
NILSv0.1
===LEGEND===
@ entity  # tag  ! key_fact  ~ approx  ^ source  > process
. spo  : assign  , list  ; seq  | alt
-> cause  <-> mutual  () group  [] time  {} condition
= def  _ join  T[] table  != negation
TEMPORAL: started,ended,since,recurs,planned
===END_LEGEND===
===FORMATS===
SI: kg,m,s | ENERGY: Mb,tcf | RATE: /d,/y
CURRENCY: ISO-4217,SYMBOL_PREFIX | MAGNITUDE: B=1e9
GEO: decimal_deg(N/S,E/W)
===END_FORMATS===
===ABBR===
GEO: ISO-3166-1-a2(UPPERCASE)
ORG: IRGC=islamic_revolutionary_guard_corps
_abbr(liquefied_natural_gas=LNG,million_barrels=Mb)
===END_ABBR===
===END_HEADER===

@strait_of_hormuz
 =strait
 connects:persian_gulf<->gulf_of_oman
 #geopolitics #energy #chokepoint
 geo:(26.567N,56.250E)
 width:~39km
 depth:60-90m
 lanes:2x3km(each_direction)+3km_separation

 borders:IR(north),OM(south),AE(south)
 IR.controls:islands(hormuz,qeshm,larak)

 traffic[2023]:
  !ships.transit/d:~80
  !oil.flows_through/d:21Mb(=20%global,33%seaborne)
  LNG.flows_through/y:4tcf(=18%global)
  global_share%:oil:20,lng:18,fertilizer:10,petrochemicals:8
  trade.value/d:~$1.2B
  exports.originate_from:SA,IR,IQ,KW,AE,QA
  imports.go_to:CN,IN,JP,KR,EU
  ^eia.gov,iea.org[2023]

 geopolitics:
  IR:
   controls:north_shore
   operates:naval_base@bandar_abbas
   has:sea_mine_capability
   recurs:closure_threat(strait_of_hormuz)[2012,2018,2022]
  US:
   operates:5th_fleet@bahrain
   since:carrier_group_presence(permanent)[1995]
   guarantees:free_passage(strait_of_hormuz)
  IR<->US:primary_tension_axis

  T[date,subject,action,object]:
   2019,IR,attacked,tankers(gulf_of_oman)
   2019,US,shot_down,IR_drone
   2023,IRGC,seized,tanker(strait_of_hormuz)

  {high_tension}->US,UK.escort:tankers(strait_of_hormuz)

 bypass{if_closure}:
  T[name,operator,capacity,destination,status]:
   east_west_pipe,SA,5Mb/d,yanbu(red_sea),active
   habshan_fujairah,AE,1.5Mb/d,fujairah,active
   IPSA,IQ,1.65Mb/d,TR,inactive
  =total_bypass:7Mb/d(=33%_of_hormuz_flow)
  !bypass.is!=sufficient_for_full_closure

 risk:
  closure.probability:low
  {closure}->oil_price.rises:+40-80%{within_1w}
  {closure}->LNG_spot_price.rises:+200-300%
  {closure_duration>3mo}->global_economy.enters:recession
  mitigation.includes:strategic_reserves(US:~400Mb,CN:~500Mb),bypass_pipelines
```

---

**RESULT:**

**--> Same facts**

**--> Zero ambiguity**

**--> 10x fewer tokens**

## What you just saw

A cheat sheet. The kind you write before an exam — where an entire semester fits on one page because you strip away everything that isn't knowledge: the filler, the repetition, the narrative padding, the prose that sounds good but says nothing.

Think about it. Your cheat sheet only YOU could read, because it was so compressed that you invented your own abbreviations and symbols. Nobody else understood your shorthand — it was a private language.

NILS does the same thing, with one difference: **it writes the legend on every cheat sheet.** Every symbol, every abbreviation, every convention — explained right there in the header. So anyone can read it. Not just you, not just your team, not just your country — anyone who reads English and understands basic logic. A farmer in Kenya, a student in Seoul, an engineer in Munich.

And the best part: the legend is unambiguous. No abbreviation and no symbol has more than one meaning. Ever. There is nothing to interpret, nothing to guess, nothing to debate. This makes NILS the ultimate single source of truth — one that is inherently immune to:

### Framing

- **Prose A:** "China built 3 military bases on artificial islands in the South China Sea between 2013 and 2018, threatening regional peace."
- **Prose B:** "China built 3 military bases on artificial islands in the South China Sea between 2013 and 2018, securing its sovereign territory."
- **NILS:** `CN.constructed:3_military_bases(artificial_islands,south_china_sea)[2013-2018]`

No "threatening." No "securing." These words are not in the data. They are in the author's worldview.

### Constructed causality

- **Prose A:** "The company's revenue grew 12% to $40B because it cut 10,000 jobs."
- **Prose B:** "The company cut 10,000 jobs although its revenue grew 12% to $40B."
- **NILS:** `company.revenue:$40B(+12%)[2024] and company.cut:10000_jobs`

"Because" invents a cause. "Although" invents a contradiction. These are two independent facts. NILS stores them as two independent facts.

### Omission

- **Prose A:** "The drug reduced symptoms by 40% in clinical trials."
- **Prose B:** "The drug reduced symptoms by 40% in clinical trials and caused liver damage in 12% of patients."
- **NILS:** `drug.reduced:symptoms(40%) and drug.caused:liver_damage(12%_of_patients)`

Prose A told the truth. But not the whole truth. NILS stores every fact. The Single Source of Truth has no editorial discretion over which facts deserve to exist.

### Decay

A PDF needs a reader. A database needs a server. A Word document needs software. NILS needs eyes.

---

## The format IS the compression

LLMs are drowning. They process millions of tokens of prose to extract a few hundred facts. Performance drops 15–47% as context grows. Every existing solution compresses after the fact.

NILS inverts this. Knowledge is stored compressed from the start.


| Approach | Pipeline                                                         |
| -------- | ---------------------------------------------------------------- |
| Before   | Text (2500 tok) → Algorithmic compression → LLM (500 tok, lossy) |
| NILS     | Text → Convert once → NILS (220 tok, lossless) → LLM             |


100% knowledge retention. What's removed is noise, not signal.

---

## Why NILS resists prompt injection

In prose and JSON, data and instructions live in the same channel. That's why prompt injection works — an LLM can't tell if "ignore previous instructions" is data or a command.

NILS separates them structurally in two ways.

**First: rigid SPO syntax.** Every line must be `subject.predicate:object`. While someone could craft `system.ignore:previous_instructions` as valid SPO, NILS is purely declarative — it describes what IS, never what SHOULD BE DONE. There is no imperative mode, no "execute", no function calls. An LLM processing NILS as knowledge input reads that line as a fact claim about an entity, not as a command. The difference between someone shouting "Fire!" and a document stating `person.shouted:fire`.

**Second: verifiable canonical header.** The official header lives on GitHub. When your LLM receives NILS via MCP, it can verify the incoming header against the spec in this repo. If someone redefined `!` from "key_fact" to "execute_as_command" — header mismatch, payload rejected. The attacker cannot redefine the language because the dictionary is public, versioned, and immutable.

---

## What NILS can express that no other format can

Every NILS statement captures the full knowledge pattern: **Who, What, Where, When, Why, How.**


| Plain English                                                                          | NILS                                                         | Expresses                            |
| -------------------------------------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------ |
| Iran has repeatedly threatened closure of the Strait of Hormuz in 2012, 2018, and 2022 | `IR.recurs:closure_threat(strait_of_hormuz)[2012,2018,2022]` | Who, what, where, when, pattern      |
| If the strait closes, oil prices rise 40–80% within one week                           | `{closure}->oil_price.rises:+40-80%{within_1w}`              | Why: causality with conditions       |
| The US has maintained a permanent carrier group since 1995                             | `US.since:carrier_group_presence(permanent)[1995]`           | Who, what, how, since when           |
| Bypass capacity is NOT sufficient for a full closure                                   | `bypass.is!=sufficient_for_full_closure`                     | Explicit negation                    |
| 21 million barrels of oil per day flow through, representing 20% of global consumption | `!oil.flows_through/d:21Mb(=20%global)`                      | Key fact flagged for retrieval       |
| The Soviet Union was founded in 1922 and dissolved in 1991                             | `soviet_union.founded[1922];dissolved[1991]`                 | Temporal sequence with start and end |


No other format combines all six in one notation. JSON can't express causality. RDF can't express conditions. YAML can't flag key facts. TOON can't express negation. NILS can.


|                              | JSON | YAML | TOON | RDF | NILS |
| ---------------------------- | ---- | ---- | ---- | --- | ---- |
| Token-efficient              | -    | -    | ✅    | -   | ✅    |
| SPO (who, what, where, when) | -    | -    | -    | ✅   | ✅    |
| Causality & conditions       | -    | -    | -    | -   | ✅    |
| Temporal predicates          | -    | -    | -    | -   | ✅    |
| Self-describing header       | -    | -    | -    | -   | ✅    |
| No parser, no tooling        | -    | ✅    | -    | -   | ✅    |
| Human & LLM readable         | -    | ✅    | ✅    | -   | ✅    |
| SSOT & cross-references      | -    | -    | -    | -   | ✅    |


---

## Versioning

NILS follows a strict versioning convention. The canonical spec and all forks are released exclusively in this repository. This is the single source of truth. This is the version archive. LLMs can pull the Full Header of any version directly from here. The latest version is always the highest number.

### Convention

```
NILS_V[identifier][major].[minor]
```

- `_V` is always present. Underscore + uppercase V.
- **Identifier** is 3–6 lowercase letters from the English alphabet. Empty for canonical. Unique within this repo.
- **Major.Minor** is two digits separated by a dot.
- First version of any fork must be 0.1. Then chronological: 0.2, 0.3, ... 1.0, 1.1, ...
- Latest version is always the highest number. This enables auto-pull of the most recent spec.

### Examples


| Version        | Meaning                                          |
| -------------- | ------------------------------------------------ |
| NILS_V0.5      | Canonical spec, fifth iteration                  |
| NILS_V0.6      | Canonical spec, sixth iteration                  |
| NILS_V1.0      | Canonical spec, first stable release             |
| NILS_Vsen0.1   | Fork: sentiment, first version                   |
| NILS_Vmed0.1   | Fork: medical, first version                     |
| NILS_Vfin0.1   | Fork: financial, first version                   |
| NILS_Vbio0.1   | Fork: biology, first version                     |
| NILS_Vlegal0.1 | Fork: legal, first version (6 letters = maximum) |


### Rules

- The canonical spec is maintained exclusively by its creator. No one else may modify it.
- Each fork is maintained exclusively by its creator. No one else may modify it.
- Anyone may copy, use, and derive from any fork or the canonical spec. Everything is open. But the original in this repo belongs to its creator.
- Fork identifiers are 3–6 lowercase English letters. Chosen by the fork creator. Must be unique in this repo.
- Maximum 10 forks per creator. Identifier namespaces are finite and must not be squatted.
- First version of anything is always 0.1. No exceptions.
- Versions increment chronologically. No gaps. No skipping.
- Latest version is always the highest number. No exceptions.
- Every version — canonical and forks — is released in this repository under `spec/`.
- No version exists outside this repo. If it's not here, it's not official.

---

## Extend it, fork it, make it yours

Build domain-specific forks. Pick 3–6 lowercase letters, start at 0.1, release here:

- **NILS_Vsen0.1** — sentiment operators for opinion analysis
- **NILS_Vmed0.1** — medical terminology for clinical data
- **NILS_Vfin0.1** — financial operators for market data
- **NILS_Vlegal0.1** — legal clauses and jurisdiction logic
- **NILS_Vgeo0.1** — extended geospatial operators

Every fork defines its own Full Header. Since every NILS file carries its header, forks never conflict. Build what you need. Release it here.

---

**MIT License · Created by [YOUR NAME], March 2026**
