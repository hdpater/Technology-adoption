# When Machines Changed the Job

*A working paper on historical technology transitions and what they mean for AI agent adoption — for stakeholder conversations and internal policy.*

## Executive Summary

Every technology transition in this paper's record follows a similar shape: resistance tracks perceived unfairness and switching cost, not the technology's novelty; the harm concentrates in specific people during a specific window, not in "the workforce" as an aggregate; and the technologies that look inevitable in hindsight were, at the time, contested, mocked, or actively fought. **Part I** collects nineteen such transitions — from 15th-century scribes to the 2018 techlash — and extracts the patterns that repeat across all of them. **Part II** turns those patterns into an operational question for organisations adopting AI agents now: *is it worth spending resources to bring stragglers along, and if so, on what?* Three agent-based simulations (mechanics in **Appendix A**) were built to probe that, producing one robust, load-bearing finding — handing support work downward is worth roughly 30% of output — alongside one result (a large positive effect of training) that turned out to be a numerical artifact and is reported as such rather than quietly dropped.

**Three findings worth carrying into a policy conversation:**
- Resistance is driven by perceived unfairness and switching cost, not by novelty — negotiated transitions (dockworkers, case 8) look nothing like imposed ones (Luddites, case 2), even when the underlying technology is comparably disruptive.
- "It always works out in retrospect" and "this transition is genuinely stressful right now" are not competing claims — they're verdicts on different points in time, and citing the first to dismiss the second is a category error (Part I, *Why "It Always Works Out"...*).
- The capacity to absorb a new technology is earned by doing the work, not conferred by being trained on it — so whether an organisation navigates a transition well depends on whether a genuinely capable second tier exists, not on how much training budget it spent (Part II).

---

# Part I — What History Shows

Nineteen technology transitions, spanning six centuries. Each case is scored, where the evidence supports it, on what actually happened, how workers adjusted, what public opinion did before and after, and what named psychology or social-science study (if any) bears on it — flagged honestly where no such study could be found, rather than invented to fill the slot.

### 1. Printing Press → Scribes (1450s)
Scribes and illuminators were skilled, respected professionals whose core task — hand-copying texts — was made obsolete almost overnight. Some guilds fought back hard: Paris scribes delayed the printing press's introduction to their city by 20 years, and in some places guilds destroyed presses outright.

**What actually happened:** Many scribes stayed employed, because their daily work (minutes, transcripts, inventories) was never worth printing. The ones whose *specific task* disappeared mostly moved up the value chain — becoming editors, publishers, and typesetters, as book demand exploded far beyond what hand-copying could ever have served.

---

### 2. Mechanized Looms → The Luddites (1811–1816)
Often misremembered as "anti-technology." In reality, Luddites were skilled textile artisans reacting to machines being used to undercut wages and standard labor practices during a period of war, food shortages, and no legal right to organize. The backlash was violent — and it failed: the movement collapsed under government repression, with public executions in 1813, and most workers returned to worse conditions than before.

**Lesson:** Resistance tracked with *fairness*, not novelty. People weren't against machines — they were against being deceived or undercut by how machines were deployed.

---

### 3. Typewriter → Word Processor → PC (1960s–1990s)
Typing pools were centralized departments producing all of an organization's documents. Early word processors didn't kill the role — typists adapted fast and got faster. The real disruption came later, when personal computers let *everyone* type their own documents, decentralizing the work entirely. Dedicated typing pools were largely gone by the 1990s.

**Lesson:** The technology that seems disruptive (word processors) often isn't the one that ends the job. The quieter shift (PCs on every desk) was what mattered.

---

### 4. ATMs → Bank Tellers (1970s–2010s)
The counterintuitive case economists cite most. Teller employment did **not** decline as ATMs spread — lower branch costs meant banks opened more branches, so total teller jobs held steady for decades. The role shifted toward relationship banking and sales. Tellers only saw real decline later, when mobile banking automated nearly all their routine tasks at once, rather than just some of them.

**Lesson:** Partial automation reshapes roles. Near-total automation eliminates them. This is the clearest historical evidence for tiering risk by *how much* of a task is handed to the machine, not just *whether* it touches the task at all.

---

### 5. Automobile → Horse-Drawn Trades (1900s–1920s)
The car didn't just replace a vehicle — it collapsed an entire economy built around horses. US carriage-making firms fell from 13,800 in 1890 to 90 by 1920; farriers, blacksmiths, livery stables, and feed merchants lost their reason to exist. By 1902, 97% of US streetcar track was electrified, and the first motor-bus line (1907) finished off horse-drawn transit within a generation.

**Adjustment:** Garages replaced livery stables, blacksmiths retrained as mechanics, and carriage-parts makers moved into auto manufacturing. The trades were small and dispersed rather than unionized, so no organized resistance emerged.

**Public opinion before → after:** Early cars were feared and mocked as loud, dangerous, and prone to spooking horses — Prince Edward Island banned them outright in 1908, and some manufacturers fitted cars with a fake wooden horse head to calm animals on the road. Within two decades the car was normalized as essential infrastructure.

**Psychology/social-science angle:** No verified named study; retrospective pieces (e.g. NPR, 2023) use this case mainly as an analogy for present-day driverless-car skepticism.

**Lesson:** Fear attaches to the concrete disruption a new technology causes (frightened horses), not to its abstract novelty.

---

### 6. Automatic Switching → Telephone Operators (1920s–1970s)
"Telephone operator" was one of the largest occupations for young American women — 350,000 strong at AT&T's peak in the late 1940s, 98% women. Between 1920 and 1940 alone, AT&T ran one of the largest automation programs in history, converting over half the US network to automatic switching and cutting the young female operator workforce by 50–80%.

**Adjustment:** Individual operators caught in the transition were, a decade later, more likely to be in lower-paying jobs or unemployed — but later cohorts of women were absorbed into growing clerical and service jobs, so the occupation's collapse didn't show up as a generational employment decline.

**Public opinion before → after:** Operators ("hello girls") were seen as holding a respectable, skilled career; AT&T framed automation as engineering necessity rather than a labor dispute, so — unlike the Luddites or elevator operators — it drew little public backlash.

**Psychology/social-science angle:** Feigenbaum & Gross, "Answering the Call of Automation" (NBER 2020; *QJE* 2024) — using genealogy-linked census data, found automation hit incumbent workers hard individually even though later cohorts weren't worse off in aggregate, and that AT&T automated to handle network scaling, not primarily to cut labor costs.

**Lesson:** Aggregate employment statistics can look fine while masking severe harm to the specific workers caught mid-transition.

---

### 7. Automatic Elevators → Elevator Operators (1945–1975)
Push-button elevators existed from 1892, but for the next ~50 years almost nobody would ride one without an operator present. The turning point was the September 1945 NYC strike of ~15,000 elevator operators, doormen, and porters (backed by 250,000+ union members), which stranded 1.5 million office workers and cost the city an estimated $100 million.

**Adjustment:** The industry used the strike as its opening to commit to full automation, then spent roughly a decade deliberately building public trust — adding emergency phones and stop buttons, and often running human operators alongside automatic systems during the changeover.

**Public opinion before → after:** Before: people said they'd never ride an unmanned elevator, even after watching an operator press the same buttons they could press themselves. After the trust-building measures, automatic elevators became the unremarkable default within about a decade.

**Psychology/social-science angle:** No single named academic study verified, but retrospective accounts (NPR, 2015) frame this as a clean case of technical feasibility (1892) far outpacing psychological/social acceptance (not achieved until the 1950s).

**Lesson:** A technology can be unnecessary for decades yet still feel socially essential, until trust is deliberately transferred through gradual exposure and visible safety backups.

---

### 8. Containerization → Dockworkers (1956–1970s)
Containerization began with Malcom McLean's first container ship in 1956; by the late 1960s over 40% of US port cargo moved in containers, collapsing loading times from days to hours and slashing the labor needed per ton of cargo.

**Adjustment:** The ILWU–Pacific Maritime Association Mechanization and Modernization Agreement (1960) let employers automate freely in exchange for guaranteed pay, early-retirement payouts, and job protections for existing registered longshoremen — trading a shrinking workforce for a smaller, much better-paid one instead of an unmanaged layoff wave.

**Public opinion before → after:** Dockworkers initially distrusted "the box" as a tool to gut the union; after the M&M deal it became the labor-relations model cited as proof automation can be negotiated rather than fought.

**Psychology/social-science angle:** No named psychology study found; the relevant literature is institutional/labor-economics (union bargaining theory), not psychology.

**Lesson:** Automation resisted without a bargaining stake breeds conflict; automation bargained for a share of the gains gets adopted with far less resistance.

---

### 9. Assembly Line & Industrial Robots → Manufacturing Workers (1913; 1980s–2000s)
Ford's moving assembly line (1913) deskilled craft auto work into repetitive single-motion tasks — turnover hit 380% in 1913 alone, prompting the famous $5/8-hour day in 1914 just to keep the line staffed. Decades later, industrial robots swept auto plants in the 1980s (GM spent over $40 billion on factory automation); Acemoglu & Restrepo (2020, *Journal of Political Economy*) found each additional robot per thousand workers between 1990–2007 cut the local employment-to-population ratio by ~0.2 points and wages by ~0.4%, concentrated among blue-collar men in Midwest manufacturing hubs.

**Adjustment:** In 1913, Ford simply paid more rather than redesigning the work; workers had little recourse beyond quitting. In the robot era, harm was absorbed unevenly, concentrated in the most-exposed local labor markets, with limited retraining infrastructure.

**Public opinion before → after:** The 1913 line was seen by workers and press as degrading (later captured in *Modern Times* and *Metropolis*); by mid-century it had normalized into the archetype of stable, unionized blue-collar work. Robots in the 1980s were framed as a competitiveness necessity versus Japan rather than a threat, until later data revealed concentrated local harm.

**Psychology/social-science angle:** Acemoglu & Restrepo (2020) is a real, named labor-economics study with the statistics above; no psychological study on 1913 worker sentiment was found — the "horror" framing comes from cultural/press response, not survey data.

**Lesson:** The backlash to a new tool arrives once its productivity gains are felt to bypass the workers producing them.

---

### 10. Farm Mechanization → Farm Labor (1910s–1960s)
Tractors went from near-zero to about 1 million on US farms by 1930, effectively replacing draft animals by 1970; mechanical harvesters for cotton, sugar beet, and tomato crops became routine by the late 1960s.

**Adjustment:** Farm labor migrated en masse to cities as part of the Great Migration, with no formal retraining programs — the migration itself was the adjustment mechanism.

**Public opinion before → after:** Popular opinion long blamed the mechanical cotton picker for pushing poor rural (often Black) families off the land into desperate urban job searches. Revisionist economic history (Warren Whatley; Donald Holley's *The Second Great Emancipation*) instead argues labor scarcity from wartime/postwar out-migration drove mechanization as much as the reverse — and that it helped dismantle Jim Crow plantation labor as political power shifted to cities.

**Psychology/social-science angle:** No individual-level psychology study found; the strongest citation is the causal debate in economic history between the popular "displacement" narrative and the labor-supply-driven revisionist account.

**Lesson:** The commonly told causal story — "the machine displaced the worker" — often turns out to run partly in the other direction on closer historical inspection.

---

### 11. Electronic Computers → Human "Computers" (1940s–1960s)
Before electronic computers, "computer" was a job title — mostly held by women — doing manual calculation for astronomy, ballistics, code-breaking, and later NASA/JPL trajectory work. Male engineers initially distrusted electronic computers as unreliable and dismissed programming as "women's work," so the women already doing the calculations were handed the new machines and became the first programmers.

**Adjustment:** The transition was gradual and role-preserving — the same workforce moved from calculating by hand to programming the machines that replaced the calculation. Around 1970, JPL renamed the "computer" job title to "engineer" and began requiring engineering degrees for new hires, closing the informal path that had let this workforce advance without one.

**Public opinion before → after:** Before: human computing was valuable but low-status, feminized, clerical-technical labor. After: once electronic computers proved reliable, distrust flipped into embrace — but new credentialing requirements then made it harder for the original workforce to be recognized at the same status as the "engineers" who followed them.

**Psychology/social-science angle:** No single named study found; the pattern echoes general findings on gendered occupational segregation and status-anxiety-driven resistance among incumbent professionals, rather than a specific cited study.

**Lesson:** The people doing yesterday's manual task are often best positioned to run tomorrow's machine — but institutions can still write them out of the credit.

---

### 12. Photography → Portrait Miniaturists (1840s–1900s)
The daguerreotype (1839) offered a faster, cheaper way to get a lifelike likeness than a painted portrait, hitting hardest against a specific specialist: the portrait miniaturist, who painted small watercolor likenesses on ivory. Within about a decade, daguerreotypes had pulled away most miniaturists' clientele.

**Adjustment:** Unlike the scribes-and-printing-press story of moving up the value chain, miniaturists mostly did not — many simply quit; others adapted by hand-coloring photographs or running studios offering both. Portrait painting broadly survived by shifting toward what photography couldn't yet replicate (larger-scale, higher-status, more interpretive work), and the miniature form saw a deliberate revival later in the century (an 1863 South Kensington Museum exhibition; the Society of Miniature Painters, founded in London in 1896).

**Public opinion before → after:** Before: miniatures were the standard way of keeping an intimate likeness of a loved one. After: photography was the practical, modern substitute, and surviving miniature painting was reframed as a nostalgic, artisanal specialty rather than a mainstream service.

**Psychology/social-science angle:** No specific named study found; the clearest documented mechanism is direct economic substitution (clientele diversion), not an attitude-change study.

**Lesson:** When a cheaper substitute satisfies a craft's literal function, the craft doesn't always move up the value chain — sometimes it just shrinks into a niche and waits for nostalgia.

---

### 13. Radio and Television Moral Panics (1920s–1950s)
Radio's 1920s spread brought fears about children's health and behavior — a widely cited 1941 study by Dr. Mary Preston claimed three-quarters of studied children were "addicted" to radio and movies, disturbing sleep and eating. Television in the 1950s triggered a stronger, more durable panic: content complaints began almost immediately (1946), and by the 1950s–60s, US Senate hearings on juvenile delinquency examined whether TV violence was corrupting children.

**Adjustment:** Both media were absorbed into domestic life without the feared breakdown materializing; formal responses (content codes, hearings, industry self-policing) channeled the anxiety into regulation rather than rejection of the technology.

**Public opinion before → after:** Before: experts and parents treated both as active threats to children's morals, sleep, and attention. After: both normalized into unremarkable household fixtures — but the anxiety didn't resolve so much as migrate forward to whatever new medium came next (comics, then TV, then video games, then the internet).

**Psychology/social-science angle:** Stanley Cohen's moral panic theory (*Folk Devils and Moral Panics*, 1972) — developed from British "Mods and Rockers" media coverage, not radio/TV specifically — supplies the standard retroactive lens: a "folk devil" is identified, coverage amplifies fear, anxiety escalates, then fades.

**Lesson:** Each new medium inherits the last one's panic script almost verbatim — the fear is a recurring genre, not new evidence about the specific technology.

---

### 14. The Internet — Three Press Swings, Not One (1993–2018)
Unlike most cases above, the internet's press record shows not a single flip but three swings: skepticism, euphoria, then backlash — each backed by prominent, quotable coverage rather than vague sentiment.

**Public opinion, phase by phase:**
- *Skeptical (1993–97):* Newsweek, Feb 27, 1995 — Clifford Stoll, "The Internet? Bah!": *"No online database will replace your daily newspaper, no CD-ROM can take the place of a competent teacher and no computer network will change the way government works."* He called the internet *"a wasteland of unfiltered data"* lacking editors or critics. The New York Times ran "Skeptics Cite Overload Of Useless Information: Internet Arrives at a Crossroads" (March 1997), quoting even Bill Gates's surprise at how the internet was actually being used. (Not universal — Fortune's "Boom Time on the New Frontier," 1993, was already bullish, a reminder that "before" opinion is rarely monolithic.)
- *Euphoric (2006):* Time, "Person of the Year: You" (Dec 25, 2006): *"For seizing the reins of the global media, for founding and framing the new digital democracy, for working for nothing and beating the pros at their own game, TIME's Person of the Year for 2006 is you."* Newsweek's own 2017 retrospective on the Stoll column called it "laughably inaccurate," noting the things he dismissed — online shopping, telecommuting, internet journalism — were "fully thriving."
- *Backlash / "techlash" (2017–18):* NPR, "As Views of Tech Turn Negative, Remorse Comes to Silicon Valley" (April 2018), documenting tech executives' own regret over smartphone addiction, misinformation, and data privacy as mainstream coverage turned sharply critical again.

**Psychology/social-science angle:** This case is the clearest evidence that opinion doesn't converge monotonically on "positive" — it oscillates, each swing driven by a different mechanism (novelty skepticism, then adoption euphoria, then delayed recognition of real harms).

**Lesson:** "Technology is always judged positively in retrospect" really means "technology is judged by whichever swing of the pendulum you're standing on when you ask."

---

## Supplementary Press Arcs

Five further technologies with the same well-documented press-swing pattern, kept in a lighter quick-reference format rather than the fuller case-study treatment above — quoted directly so they can be checked against the original coverage:

**Nuclear power (1954 → 1979/86 → 2020s).** Lewis Strauss, US Atomic Energy Commission chairman, to the National Association of Science Writers, Sept 16, 1954: *"It is not too much to expect that our children will enjoy in their homes electrical energy too cheap to meter."* Three Mile Island (1979) and Chernobyl (1986) turned coverage toward lasting dread that outlived the technology's actual safety record. By the 2020s, nuclear was back in favorable press as a climate-change solution — three eras, one technology.

**Television (1939 → 1961 → prestige-TV era).** The New York Times, May 7, 1939, on the RCA debut at the World's Fair, described a "gleaming glass encased instrument" with "artistry" yet to catch up to the engineering. Newton Minow, FCC chairman, to the National Association of Broadcasters, May 9, 1961, called American television a *"vast wasteland"* of "formula comedies," "blood and thunder," and "cartoons." Television is now routinely discussed in "golden age of TV" terms — the same medium Minow scorned is credited with prestige drama.

**The safety bicycle (1895–96).** Medical and mainstream press on both sides of the Atlantic warned of "bicycle face" — a supposed permanent disfigurement from cycling — and claimed cycling would harm women's fertility or morals. In the same window, suffragist Susan B. Anthony told journalist Nellie Bly (The New York World, Feb 2, 1896): *"I think [bicycling] has done more to emancipate women than anything else in the world... It gives a woman a feeling of freedom and self-reliance."* Notable because the panic and the embrace ran in the press *simultaneously* — from different commentators, not sequential phases.

**Comic books (1954 → 1990s).** Dr. Fredric Wertham's *Seduction of the Innocent* (April 19, 1954) and the Senate Subcommittee on Juvenile Delinquency hearings that followed within days made front-page New York Times news; fifteen comic publishers went out of business that summer, and the industry adopted the self-censoring Comics Code Authority. Within four decades the same medium had "graphic novel" respectability — Maus won a Pulitzer Prize Special Citation in 1992, and Time later named Watchmen to its list of the 100 best English-language novels since 1923.

**Automobile safety, round two (1965–66).** The car had already been normalized by the 1920s (case #5), but a second press-driven reckoning hit decades later: Ralph Nader's *Unsafe at Any Speed* (1965) accused manufacturers of prioritizing style over safety. GM's response — hiring private detectives to dig up dirt on Nader — became its own scandal, forcing GM's president to publicly apologize to Nader before a Senate subcommittee; the resulting press storm helped pass the National Traffic and Motor Vehicle Safety Act of 1966. The same technology cycled through a second arc, re-litigated on a different axis (safety, not novelty) decades after the first one settled.

*Quotes above are drawn from the cited secondary sources (NRC and Time historical write-ups, NPR, Newsweek/Poynter retrospectives, welovecycling/CycleBlaze citing the original New York World interview); dates and outlets are given so each can be checked against the original press record.*

---

## Cross-Cutting Frameworks

Named psychology/social-science frameworks that recur across these cases:

| Framework | Origin | Core idea | Relevance |
|---|---|---|---|
| Diffusion of Innovations | Everett Rogers, 1962 | Innovations spread through adopter categories (innovators → early adopters → majority → laggards) along an S-curve, driven by relative advantage, compatibility, complexity, trialability, and observability | Explains *speed* of adoption/resistance as a property of the innovation's fit, not just its raw capability |
| Technology Acceptance Model | Fred Davis, 1989 | Acceptance is driven by perceived usefulness and perceived ease of use, with usefulness the stronger predictor | Locates resistance in *subjective* perception — framing and demonstrated value matter as much as technical merit |
| Moral Panic Theory | Stanley Cohen, 1972 | A "folk devil" is identified, media coverage amplifies fear, public anxiety spikes, a policy response follows, then it fades | The standard explanatory frame for recurring public overreaction to new media/technologies |
| Technological Unemployment | John Maynard Keynes, 1930 | Job loss from labor-saving innovation can temporarily outpace the creation of new uses for labor | Origin point of the "transition pain vs. permanent harm" framing used in later automation debates |
| Status quo bias | General behavioral economics literature | People disproportionately prefer the current state and weight losses from change more heavily than equivalent gains | A general psychological driver of resistance to new tools, independent of the tools' actual merits — no single canonical citation confirmed |

*Note: "automation anxiety" is widely used across journalism and policy writing but has no single canonical founding study found in this research — treat it as a descriptive umbrella term, not a formally attributed theory. Several case-specific claims above (elevators, cars, farm mechanization, human computers, photography) also had no verifiable named psychology study — this is flagged honestly in each entry rather than invented.*

---

## The Psychology of Change

Two questions the case studies raise but don't answer on their own: why does "it always works out in retrospect" fail to reassure anyone living through a transition right now, and why does the same rollout split a population's reactions rather than moving everyone the same way? Both turn out to have direct answers in the psychology literature.

### Why "It Always Works Out" Doesn't Reassure Anyone Mid-Transition

A common objection to worrying about a new transition: technology improvements are almost always judged positively in retrospect, so why the anxiety now? The answer is that anticipation and retrospection are measuring different things, produced by different mechanisms — not contradictory findings about the same event.

- **Loss aversion (Kahneman & Tversky).** Anticipated change is evaluated by the threat it poses to what people currently have, and losses are weighted roughly twice as heavily as equivalent gains. Before a change, fear overweights what could go wrong; after, once the loss didn't materialize (or was smaller than feared), the fear has nothing left to attach to.
- **Affective forecasting error / rosy retrospection.** People are reliably bad at predicting how a change will feel (Gilbert & Wilson's affective-forecasting research), and memory later reconstructs the experience more positively than it was lived (Mitchell, Thompson et al.'s "rosy view" studies). Anxious anticipation and calm retrospective judgment are produced by different cognitive processes at different times.
- **Status quo bias flips sides.** Once a technology is adopted and becomes normal, it *becomes* the status quo — the same bias that resisted the car in 1905 now resists whatever threatens to replace it. Resistance to change doesn't disappear; it just re-attaches to whatever is newest.
- **Survivorship bias in the historical record.** "Technology improvements are seen as positive in retrospect" is partly a sampling artifact — we're only looking at technologies that stuck around and worked. Ones that caused lasting harm were often abandoned, reshaped by regulation, or their losers (miniaturists who simply quit, scribes whose task never came back) don't get to narrate the retrospective.

**Bottom line:** stress and anxiety are concentrated in the *transition window*, while positive retrospective judgment is a verdict on the *settled endpoint*, delivered only once uncertainty has resolved and people have adapted. "It always works out" is true about endpoints and says nothing about the transition itself — which is exactly the period this paper's case studies show is where people get hurt.

### Psychology of Novelty & Habit Disruption (Why Software Updates Split Opinion)

Software and interface rollouts are a live, present-day instance of the same pattern — and here the underlying psychological mechanisms are studied directly, separate from the historical press record above.

- **Automaticity (Shiffrin & Schneider, *Psychological Review*, 1977).** Well-practiced tasks get compiled into fast, low-effort "automatic" processing; anything novel runs through slow, effortful "controlled" processing. Redesigning an interface forces users who had automatized their workflow back into controlled processing — inherently effortful, regardless of whether the new design is actually better.
- **Interruption theory of emotion (Mandler, *Mind and Emotion*, 1975).** Interrupting an automatized plan produces physiological arousal that is itself emotionally neutral; the subsequent cognitive appraisal determines whether it's experienced as excitement, curiosity, irritation, or anxiety. This is the most direct account of why the same rollout produces a genuine *mix* of reactions rather than one uniform mood.
- **Status quo bias in IT rollouts (Kim & Kankanhalli, *MIS Quarterly*, 2009).** A study built around exactly this scenario found user resistance to new systems driven mainly by switching costs (the effort of relearning) and perceived threat to one's existing competence or influence — more than by the new system's actual merits.
- **Feature fatigue (Thompson, Hamilton & Rust, *Journal of Marketing Research*, 2005).** People systematically overweight capability and underweight usability before using a product, then flip that weighting after — explaining why a feature-loaded update tests well in previews but draws complaints once people live with it.
- **Mere exposure effect (Zajonc, 1968).** Repeated exposure to a stimulus increases liking independent of reasoned evaluation — the standard explanation for why initial hostility to a redesign fades within weeks or months.
- **Real case:** Windows 8's removal of the Start button (2012) drew enough backlash that Microsoft restored it in Windows 8.1 within about a year — a company observing this exact mixture of reactions in real time.

*Caveat: the popular "change curve" (denial → frustration → ... → acceptance) that change-management consultants apply to software rollouts is adapted by analogy from grief-stage models, not an independently validated stage theory of technology adoption — useful as a rough narrative, not as established science.*

**A modeling idea worth flagging:** Mandler's split — arousal from interruption, valence from appraisal — combined with status-quo-anchored expectations, is naturally suited to formal agent modeling. A BDI (belief-desire-intention) agent holding an anchored *expectation* of the future could treat an unexpected event as first producing "arousal" proportional to the size of the belief update, then a valence sign determined by whether the event moved the agent's desires closer to or further from being satisfied — which would let a simulation reproduce genuinely mixed populations of reactions (some agents made more optimistic, some more anxious) from the same external event, rather than assuming everyone reacts identically to "change." *(This idea is what the first of the three simulations in Appendix A, Surprise Circumplex, was built to test.)*

---

## Part I Conclusions: What Repeats Every Time

Across nineteen transitions and six centuries, the same handful of patterns keep reappearing. None of them are specific to any one technology, which is exactly what makes them useful for reasoning about the next one.

| Pattern | What it means for us |
|---|---|
| Resistance follows perceived unfairness, not the tech itself | Transparency and honest framing matter more than reassurance |
| Partial automation reshapes jobs; near-total automation ends them | Supports tiering agent autonomy by task coverage, not just tool type |
| New roles emerge, but with a lag | The transition period — not the end state — is where people get hurt |
| Workers who adapt early do best | Early enablement and training pay off disproportionately |
| Individual harm can hide inside fine aggregate statistics | Track outcomes for the specific people mid-transition, not just headline employment numbers |
| Bargaining for a share of automation's gains defuses resistance more than fighting it outright | Favor negotiated transition frameworks over pure mandate or pure prohibition |
| Technical feasibility and social trust can be decades apart | Budget deliberate trust-building time (visible safeguards, gradual exposure) — not just deployment time |
| Fear attaches to concrete, everyday disruptions, not to a technology's abstract novelty | Address specific, tangible worries directly rather than arguing about the technology in the abstract |
| Press/public opinion often swings more than once — skepticism, then euphoria, then a delayed backlash — rather than settling permanently | Expect and plan for a possible second wave of scrutiny even after initial acceptance looks secure |

---

# Part II — From History to Policy

The case studies above describe what happened to other people. This part asks the operational question they raise for us: **if a transition is coming, is it worth spending resources to bring the stragglers along?**

Three agent-based simulations were built to probe that — a model of what one person feels when a habit is interrupted, a population-level model of how adoption spreads and who gets left behind, and an organisational model of training versus handing work down. They are illustrative toys, not validated models of organisations, and the honest results include one substantial failure, reported below because it changes what the rest is worth. Their mechanics, limitations, and links are in **Appendix A** for readers who want to inspect them directly; what follows are the findings.

## The one robust finding

Three organisations ran on an identical stream of ideas, differing only in policy. The ability to hand support work downward was worth **~28–32% of organisational output**, stable across every population size and integration step tested. Without it, senior staff retained only ~25% of their effective speed — buried in supporting things they themselves had introduced.

The mechanism is specific and it is the whole argument: **a handoff only succeeds when the receiver has already independently operated that particular technology.** When the model let work pass to anyone standing nearby, the entire effect vanished — because in a working organisation there is always somebody standing nearby. Proximity is free; capability is not.

## The failure, reported deliberately

An intermediate build showed training producing an **+83%** gain. That number was a numerical artifact. Re-running the identical model at different integration timesteps moved the training effect from +58% to −1.4%, flipping sign, while the handoff effect stayed at +28–32% throughout. The published version runs at the finest timestep tested, where training's effect is small and turns negative above roughly 30% of frontier time.

This matters in two directions. It is why the handoff result is quoted with confidence and the training result is not. It is also **not evidence that training doesn't work** — a toy model failing to detect an effect is weak evidence of absence, especially where the training mechanism was the crudest thing in the model.

## The capability gate

The surviving mechanism turns out to have a name. Cohen & Levinthal's **absorptive capacity** (1990) holds that an organisation's ability to take up new knowledge is a function of its *prior related knowledge*, accrued largely as a by-product of doing the work rather than being told about it. You cannot absorb what you have no foundation in.

That reframes the policy question. Not *"how much should we spend on training?"* but:

> **For each technology we depend on, how many people have independently operated it — and what is the cheapest way to make that number two?**

Attributes that appear to produce a capable second tier, tagged by how well-founded each is:

| Attribute | Basis | Why it matters |
|---|---|---|
| Coverage per technology, not average skill | model | An organisation of brilliant sole owners has *zero* handoff capacity regardless of headcount or seniority |
| Capability is earned by doing the work | literature | Briefings and shadowing lower the cost of a later adoption but do not create a receiver |
| Slack in the second tier | model + queueing theory | Saturated receivers refuse work; running everyone at full utilisation structurally eliminates the ability to shed work downward |
| Rotation of *new* work, not just old | judgement | If tier 1 always takes the new thing because they're fastest, tier 2 never passes the gate. The real training budget is an assignment policy |
| Low switching costs, no status penalty for not knowing | literature (Kim & Kankanhalli, 2009) | The people who most need to pass the gate have the most to lose by visibly starting as beginners |
| Codification | judgement | Should lower the cost of passing the gate — testable, not established |
| Hiring as substitute | model | Refreshes the frontier without spending frontier time, but new hires know the industry's technology, not *your* legacy |
| Coupling / communities of practice | model + literature | Capability investment paid most in organisations where people already watch and copy each other |

## What to measure before spending anything

None of this requires measuring "skill" — every construct has a proxy most organisations already emit:

| Construct | Where it already exists | Decision it informs |
|---|---|---|
| Independent operators per technology | On-call rotas; commit and review authorship; who *resolved* the ticket, not who was assigned it | The bus-factor-one list — the core dataset |
| Frontier support load | Pages and interrupts per senior person; calendar fragmentation | Whether handoff is even your constraint |
| Handoff latency | Time from a technology's introduction to first incident resolved by someone else | Whether the gate is passable in practice |
| Second-tier utilisation | WIP counts, queue lengths, cycle times | Whether slack, not capability, is the blocker |
| Time to independence | Onboarding to first unsupervised contribution | Your switching cost in real units |
| What actually caps delivery | Whether delivery tracks your slowest or fastest contributor | Your production function — this governs the sign of the whole answer |

**The policy loop:** rank technologies by *(frontier time consumed × inverse bus factor)*; for each, pick the cheapest route to a second independent operator (rotation, pairing through a real change, codification, or hiring); check second-tier slack first, or you will create capability, see no handoff, and wrongly conclude capability-building doesn't work.

## How we would know this is wrong

- **The gate itself:** do people trained on a technology but who never independently operated it absorb handoffs as readily as those who did? If yes, the capability gate is wrong and conventional training should work fine.
- **Relevance:** if senior staff already spend little time supporting what they introduced, handoff is not the constraint and this framing is beside the point.
- **Codification as substitute:** short handoff latency despite bus factor one would mean codification substitutes for practice.
- **Aggregation:** if delivery tracks the fastest contributors, improvements to the tail will not appear in output however real they are.

## Conclusions

Three claims this work supports with reasonable confidence, and one it doesn't. First, historically, resistance to a transition tracks fairness and bargaining stake far more reliably than it tracks the technology's raw disruptiveness — the clearest natural experiment in this paper is dockworkers versus Luddites, comparably disruptive automation with opposite outcomes because one was negotiated and the other imposed. Second, the psychological literature converges on a genuine distinction between the *transition window*, where arousal, loss aversion, and switching costs dominate, and the *settled endpoint*, where retrospective judgment is formed only after uncertainty resolves — collapsing the two, in either direction, is the most common reasoning error available here. Third, in the organisational simulation, the ability to hand work to someone who has genuinely absorbed a technology mattered roughly an order of magnitude more than training budget did — which, if it generalizes, argues for spending on rotation, slack, and assignment policy ahead of spending on instruction.

What this work does *not* support is a training budget recommendation in either direction: the one simulation built to test it produced a result too sensitive to modeling choices to trust, and that result is reported rather than hidden precisely so it doesn't get cited as if it were. The production function governing organisational output (weakest-link, average, or best-shot) was treated throughout as an input supplied by the reader, not a finding — it was never estimated from real data, and it determines the sign of nearly everything downstream of it.

## Opportunities for Further Development

- **Estimate the production function, don't assume it.** Everything in Part II changes sign depending on whether an organisation's output tracks its slowest or fastest contributor. This is answerable from real delivery data (see "What to measure," above) and should be settled empirically before any of the rest of this is applied to a specific organisation.
- **Replace illustrative parameters with real ones.** The simulations' agent traits (innovativeness, capacity, switching cost) were chosen for plausibility, not fit to data. Calibrating them against the bus-factor and handoff-latency measurements above would turn a demonstration into an actual forecasting tool.
- **Test the assignment-policy intervention directly.** The model's crude lever was a training-time budget; the more interesting and untested lever it points to is deliberately assigning new technologies to *not* the fastest available person, and measuring whether that closes the capability gate faster than instruction does.
- **Stress-test the weakest-link regime.** The simulated laggard tail was thin, making exactly the production-function setting where bringing up stragglers matters most also the least trustworthy result in this paper. A population with a genuinely heavy tail is the next thing to build.
- **Build the BDI extension to Surprise Circumplex.** The arousal/valence-from-appraisal mechanism (Mandler, 1975) that seeded these simulations was implemented as a simplified toy; a proper belief-desire-intention agent — with an explicit, updatable expectation of the future rather than a single scalar — would let the model represent *why* a given event reads as good or bad news to a given agent, not just that it does.
- **Test codification as a substitute for practice.** Flagged in Part II as judgement, not established: if well-documented organisations show shorter handoff latency at the same bus factor, codification is doing real work; if not, the attribute should be dropped rather than assumed.
- **Connect Part I's multi-swing press pattern to Part II's organisational model.** The internet's three-phase swing (case 14) and the techlash more broadly suggest organisational sentiment about an internal rollout might also be non-monotonic — worth testing whether the "Second Tier" model produces a second wave of resistance once early problems with a handed-down technology surface, rather than settling once.

---

# Appendix A — The Simulations

*For readers who want the mechanics behind Part II's findings, not just the conclusions. Each is a self-contained, interactive companion instrument — illustrative toys built to test a specific mechanism, with parameters chosen for plausibility rather than fit to real organisational data.*

| Simulation | Question it probes | What it showed | Link |
|---|---|---|---|
| **Surprise Circumplex** | What one person feels when a habit is interrupted | Arousal and valence are computed independently (Mandler, 1975), so a single change scatters a population across all four emotional quadrants rather than moving everyone the same way. Loss aversion is a hot-state effect that cools as arousal fades. | [Open](https://claude.ai/code/artifact/ba12cd74-1240-41a6-9b48-3d3c3d2b1bda) |
| **The Innovator's Wake** | How adoption spreads across a population over time | A frontier is sustained by *succession*, not distance: careers deplete, and replacing retirees at the cutting edge is what keeps a leading edge leading. Separation between adopters and laggards is not self-sustaining without it. | [Open](https://claude.ai/code/artifact/c240267c-0ccc-49ec-95c0-600b77995e15) |
| **The Second Tier** | Whether training the laggards is a good use of resources | Being *able to hand work down* was worth ~30% of output. Training budget was worth approximately nothing, and an early positive result for training turned out to be a numerical artifact (see Part II). | [Open](https://claude.ai/code/artifact/68fcf39f-d7b9-4634-9c6c-a423031e732d) |
| **The Capability Gate** *(write-up, not a simulation)* | What organisational attributes actually produce a capable second tier, and what data would inform the policy | Synthesizes the Second Tier's finding through Cohen & Levinthal's absorptive capacity; the source for the attribute and data-collection tables in Part II. | [Open](https://claude.ai/code/artifact/b1984b4d-da05-44ba-9ba1-4dd0ddc068d5) |

*Note: these are Claude Artifacts and private by default. The links above will only resolve for people they've been explicitly shared with, via each page's share menu.*

**Why the timestep story matters beyond one number.** Part II reports that the training effect swung from +58% to −1.4% purely as a function of integration timestep, while the handoff effect held steady at +28–32% throughout. That asymmetry is itself informative: an effect that survives changes to the model's internal plumbing is a property of the mechanism; an effect that doesn't is a property of the plumbing. Any reader extending these simulations should re-run their headline result at more than one timestep before trusting it — this was caught only because it was checked, not because it was expected.
