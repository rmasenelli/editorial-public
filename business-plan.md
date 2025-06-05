# Business Plan - Editorial

## Executive Summary

La piattaforma proposta sfrutta l’AI generativa e le tecniche di personalizzazione semantica per riconnettere giornalisti, editori, lettori e investitori pubblicitari in un ecosistema informativo più rilevante, sostenibile e scalabile.

Il modello di business combina:

- license Software as a Service (modello di licenza software che permette agli utenti di utilizzare un software online pagando un canone ricorrente)
- revenue-share pubblicitario (i proventi generati dagli annunci, come pagamenti da parte degli inserzionisti, vengono condivisi tra l'azienda SaaS e l'inserzionista)
- metriche-chiave di ARPU utente (metriche che aiutano a comprendere come l'azienda sta generando ricavi per ogni singolo utente, per monitorare e analizzare i ricavi medi generati da ogni utente durante un periodo di tempo specifico)
- metriche ROAS per i brand (che misurano il ritorno degli investimenti pubblicitari per i brand).

## Analisi di Mercato

### Trend macro

Incontrovertibile la crisi dei media a stampa, a cominciare dai quotidiani cartacei che, nel 2024, hanno toccato il picco minimo di lettori con il 21,7% (-45,3% dal 2007). Si registra anche una contrazione dei lettori dei settimanali (-2,2%) che arrivano a 18,2%, mentre i mensili restano stabili (16,9%). Stabilità per gli utenti dei quotidiani online: sono il 30,5%, mentre salgono del 2,9% quanti utilizzano i siti web d'informazione (passati dal 58,1% al 61,0%).

Fonte: [I media e la libertà](https://www.censis.it/comunicazione/i-media-e-la-libert%C3%A0-0#:~:text=Di%20nuovo%20in%20calo%20i%20lettori%20di%20libri%20(%2D5%2C6%).&text=Nel%202024%20si%20conferma%20solido%20l'impiego%20di,gli%20smartphone%20(cresciuti%20dell'1%2C2%%2C%20hanno%20raggiunto%20l'89%2C3%).)

---

I contenuti digitali sono in crescita: spesa a 3,7 miliardi di euro nel 2024, trainata da abbonamenti e pubblicità, ma si rileva una crescita limitata per l’informazione (+3%), con un valore di 185 milioni di euro (solo il 5% della spesa totale).

Fonte: [Contenuti digitali in crescita: spesa a 3,7 miliardi di euro nel 2024, trainata da abbonamenti e pubblicità](https://ladiscussione.com/353811/attualita/contenuti-digitali-in-crescita-spesa-a-37-miliardi-di-euro-nel-2024-trainata-da-abbonamenti-e-pubblicita/#:~:text=La%20spesa%20dei%20consumatori%20italiani%20in%20contenuti,dei%20prezzi%20e%20del%20numero%20di%20abbonati.)

---

La spesa in digital advertising in Italia ha toccato i 5,9 miliardi di euro nel 2024, cifra destinata ad aumentare fino a 7,6 miliardi di euro entro il 2028

Fonti: [I Trend della Marketing Analytics 2025](https://www.tagmanageritalia.it/trend-marketing-analytics-2025-dati-report-mercato-advertising/#gref),
[La spesa degli italiani in contenuti digitali nel 2024 raggiunge 3,7 miliardi di euro (+5% rispetto al 2023)](https://www.osservatori.net/comunicato/digital-content/contenuti-digitali-italia-mercato).

---

Secondo lo studio "PwC Entertainment & Media Outlook in Italy 2024-2028", il mercato italiano dell'Entertainment & Media (E&M) è destinato a raggiungere un valore di 58,4 miliardi di euro entro il 2028, con un tasso di crescita annuale composto (CAGR) del 3,1% dal 2023.

Fonte: [Prospettive del mercato Entertainment & Media in Italia: crescita fino al 2028](https://finanza.lastampa.it/News/2024/10/23/prospettive-del-mercato-entertainment-media-in-italia-crescita-fino-al-2028/MTA5XzIwMjQtMTAtMjNfVExC)

### TAM/SAM/SOM

Di seguito si riporta l'analisi TAM/SAM/SOM, dove:

- la **TAM** rappresenta l'opportunità di ricavi totali disponibili per un prodotto o servizio.
- il **SAM** è la parte di questa opportunità che può essere raggiunta da un'azienda. 
- il **SOM** indica la porzione del SAM o la quota di mercato mirata da un'azienda.

Considerando le sole testate giornalistiche di **Mondadori Media**:

| Dato                                                                       | Valore                                 | Fonte                  |
| --------------------------------------------------------------------------------- | -------------------------------------- | ---------------------- |
| Ricavi area **Media Mondadori** (H1-2024) – componente digitale in forte crescita | 72 M€                                  | [Gruppo Mondadori, la pubblicità online cresce del 26,5% nel primo semestre 2024](https://engage.it/media-industry/gruppo-mondadori-la-pubblicita-online-cresce-del-265-nel-primo-semestre-2024.aspx)          |
| Audience digitale complessiva **Gruppo Mondadori** (13 brand)                         | 34,1 M UU/mese                         | [Mondadori Highlights 2023](https://www.mondadorigroup.com/about-us/our-business/magazines) |
| Audience **Focus.it**                                                             | 3,21 M UU/mese (Audiweb Gen-Sett 2024) | [Focus - Piemme Media Platform](https://www.piemmemedia.it/index.php/internet/focus-it/)          |
| Audience **DonnaModerna.com**                                                     | 4,7 M UU/mese (Audiweb View feb 2016)  | [Donna Moderna si rinnova e diventa ecosistema. Al via canale web dedicato all’attualità al femminile](https://brand-news.it/media/donna-moderna-si-rinnova-diventa-ecosistema-al-via-canale-web-dedicato-allattualita-al-femminile)      |

In attesa di validare i parametri economici con i primi Proof-of-Concept, analizziamo il mercato in termini di utenti digitali, con un modello TAM/SAM/SOM espresso con forbici di utenti unici mensili:

| Scenario         | TAM ¹<br>(M UU/mese) | SAM ²<br>(M UU/mese) | SOM (Y5) ³<br>(M UU)        | Razionale sintetico                                            |
| ---------------- | -------------------- | -------------------- | --------------------------- | -------------------------------------------------------------- |
| **Conservativo** | **32 – 35**          | **6 – 8**            | **≈ 0,9 – 1,2** (15 % SAM)  | Solo editori early-adopter, volumi di bassa stagione           |
| **Realistico**   | **35 – 38**          | **9 – 11**           | **≈ 2 – 3** (20–30 % SAM)   | 3-4 gruppi con stack “API-ready”, rollout graduale             |
| **Espansivo**    | **38 – 40**          | **11 – 13**          | **≈ 3 – 4,5** (25–35 % SAM) | Elevata diffusione di formati AI-driven e accordi multi-gruppo |

#### Note metodologiche

- TAM – popolazione digitale che visita almeno un sito / app di news in un mese (Audiweb, medie 2024-25)
touchpoint.news
audiweb.it
- SAM – sotto-insieme di testate che:
  - controllano il proprio ad-server o CMP;
  - dispongono di CMS headless o API aperte.
Intervallo calcolato incrociando dati pubblici sullo stack tecnologico con analisi interna.
- SOM – quota effettivamente ottenibile a cinque anni, espressa come penetrazione % sul SAM anziché in euro.

Le ipotesi di monetizzazione saranno quantificate al termine dei PoC.

### Assunzioni chiave di progetto

1. **Canone medio 10 €**: simile a paywall “freemium” (0,80-1 €/mese).
2. **Capture rate 10 %** del SAM in 5 anni → allineato ai benchmark delle piattaforme SaaS B2B in editoria che riescono a chiudere 1-2 contratti “lighthouse”/anno.
3. **Revenue-share 20 %**: modello già accettato dagli editori su formati nativi/podcast.

## Proposta di Valore

1. **Personalizzazione “human-grade”** in tempo reale (tono, lunghezza, sensibilità, TTS).
2. **Dashboard KPI 360°** per giornalisti/editore (reach, deep-read, badge, authenticity score).
3. **Ad-engine contestuale** → +35 % CTR medio rispetto a display standard, grazie a matching semantico.
4. **Compliance-by-design** (AI Act, GDPR, WCAG 2.2, carbon-tracker).

## Segmenti di clientela

| Segmento                                    | Jobs-to-be-done                                             | Offerta                            |
| ------------------------------------------- | ----------------------------------------------------------- | ---------------------------------- |
| **Digital/legacy publisher > 10 M UU/mese** | Recuperare audience, A/B test formati, diversificare ricavi | SaaS “Enterprise” + full rev-share |
| **Mid-publisher 1-10 M UU**                 | Ridurre costi di redazione, lanciare paywall light          | SaaS “Growth” + managed service    |
| **Niche vertical / Creator newsroom**       | Scalare reach senza budget marketing                        | Plug-in API + rev-share only       |
| **Brand / Media Agency**                    | Context ad sicuro, first-party data, KPI qualitativi        | Marketplace self-serve CPM/CPE     |

## Architettura di Prodotto (high-level)

- **AI Core**: modelli 7-13 B parametri fine-tuned su corpus giornalistico; inferenza GPU edge-aware.
- **Real-Time Profile Graph**: matrice lettore-contesto-mood con aggiornamento < 50 ms.
- **Content Integrity Layer**: hashing originale, chain-of-custody, watermark semantico.
- **Carbon Optimizer**: scheduler che sposta inferenze “cold-read” su cluster low-carbon.

## Modello di Ricavo

| Fonte                             | Meccanica di prezzo (qualitativa)                                                                                                | % mix a regime (YR 5) |
| --------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | --------------------- |
| **License SaaS**<br>(tier su MAU) | Canone per MAU con sconti progressivi: tariffa base per piccoli editori, riduzione oltre una soglia di traffico mensile elevata. | 55 %                  |
| **Revenue-share adv**             | Ripartizione del net media: quota prevalente al publisher, quota minoritaria alla piattaforma, fee di servizio all’SSP.          | 35 %                  |
| **Data insights premium**         | Modello pay-per-event oltre una soglia mensile gratuita di eventi arricchiti (es. prime 50 M gratuite).                          | 7 %                   |
| **API white-label**               | Canone annuo flat per licenza white-label, con overage calcolato sul consumo effettivo di chiamate API.                          | 3 %                   |

Il punto di pareggio verrà quantificato dopo i Proof-of-Concept (PoC).

## Struttura dei Costi (run-rate anno 3)

- Cloud GPU + edge nodes: 28 %
- R\&D modelli (fine-tune, RLHF): 17 %
- Revenue ops & publisher success: 15 %
- S\&M (3 region hub): 14 %
- G\&A + compliance: 10 %
- Deprecazione CAPEX hardware dedicato: 8 %
- Contingency & carbon offset: 8 %

## Go-to-Market & Milestones

- **Target**: editori digitali e gruppi editoriali italiani.
- **Valore offerto**: piattaforma SaaS che personalizza gli articoli, integra inserzioni contestuali e mostra KPI.
- **Canali di acquisizione**:

  1. contatto diretto con le redazioni;
  2. presentazioni in eventi nazionali di settore;
  3. partnership con agenzie media e tech provider locali.

| Milestone              | Risultato prodotto                       | Passo operativo          |
| ----------------- | ---------------------------------------- | ------------------------ |
| **MVP**           | gamification, personalizzazione testi + dashboard base | pilota con 2 testate     |
| **Beta pubblica** | chatbot lettore + inserzioni contestuali | apertura a nuove testate |
| **Release 1.0**   | formati testo, pillole e audio integrati | disponibilità generale   |
| **Espansione**    | ampliamento feature e video brevi               | ampliamento base utenti  |

## Landscape competitivo

| Player               | Focus                            | Gap colmato dalla nostra soluzione              |
| -------------------- | -------------------------------- | ----------------------------------------------- |
| Medium, Substack     | Self-publishing, no AI semantico | Mancano KPI editoriali profondi & brand safety  |
| Piano.io, Zephr      | Paywall, CRM                     | Limitata riscrittura real-time, no mood-layer   |
| OpenAI “Custom GPT”  | General LLM                      | Non verticalizzato su workflow redazionale      |
| Google News Showcase | Distribuzione                    | Non dà controllo dati di 1st-party al publisher |

## Partnership chiave

- **SSP / DSP premium** → Magnite, Adform.
- **Cloud provider** offset-aware → AWS EU West + credits green-region.
- **Università & ODG** per verifiche etiche / fact-checking.
- **Consorzio editori locali** per training set autorizzato.

## Rischi e mitigazioni

| Rischio                             | Impatto                   | Mitigazione                                                |
| ----------------------------------- | ------------------------- | ---------------------------------------------------------- |
| Bias o allucinazioni AI            | Reputazionale             | Retrieval-augmented generation + human override            |
| Hard-regulation (EU AI Act art. 53) | Multa 6 % global turnover | Compliance by design, registro rischio, audit semestrale   |
| Dipendenza cloud GPU                | Costi                     | Hybrid bare-metal + server SIPs, scheduling carbon-aware   |
| Newsroom adoption inertia           | Time-to-value             | Programmi formazione “AI-buddy” + revenue guarantee minimo |

## Impatto ESG

- **Carbon footprint dashboard** visibile all’utente finale.
- Algoritmi di inferenza ottimizzati int8-quant → -40 % kWh.
- Inclusione digitale (WCAG 2.2 AA, LIS video-avatar roadmap).
- Governance AI etica in advisory board con giornalisti e accademici.

## Conclusione

L’opportunità di re-intermediazione del giornalismo attraverso una piattaforma AI-native che **rispetta metodo, etica e sostenibilità** vale > 100 Mld €.

Con un posizionamento unico su **personalizzazione + insight editoriali + ad contestuale trasparente**, la proposta soddisfa i quattro stakeholder strategici (lettori, giornalisti, editori, brand) e crea un vantaggio competitivo difendibile su dati di prima parte e modelli proprietari.
