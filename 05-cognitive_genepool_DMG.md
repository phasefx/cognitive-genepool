# The Dungeon Master's Guide

## Systems Engineering — editing the dungeon, not just surviving it

**Purpose:** Collective-scale. Intervention design, stress-testing, governance.

![][image3]

---

## Contents

**0\. Session Zero: The Engineering Contract**

**1\. What This Book Is For**

* Moving from navigation to architecture  
* Success criterion: choose interventions without arguing ontology

**2\. The Persuadability Matrix (PM2-v2)**

* The Core Insight (Levin's axis)  
* The Matrix (Interface Level × Intervention Target)  
* Why v1 needed revision (two orthogonal questions)  
* The two-step targeting procedure  
* Worked examples  
  * Metric Maximizer (institution)  
  * Addiction (individual)  
  * **SALVAGE: Cancer (collective/biological)** ← *preserve the diplomacy vs. carpet-bombing framing*  
* Engineering heuristics  
* Falsifiers

**3\. The Frame Lab**

* F1: Rigor (how not to slide into "anything goes")  
* F2: Converting thought experiments into testable case studies  
* F3: Instrumentation (what to measure)  
* F4: Unit Tests (Falsifiers)  
  * **SALVAGE: "Truth is just a hallucination that hasn't collided with an error signal yet"** ← *why falsifiers matter*  
* F5: In Case of Fire, Break Glass (framework failure modes)

**4\. Inscription Engineering**

* Working with inscription, not against it  
  * Don't delete—redirect  
  * Inscribe the edit  
  * Find the shallow points  
  * Build new roads  
  * Don't argue in a captured pivot space  
* **SALVAGE: The Recursive Trap** ← *"the capacity to edit inscription is itself a target of inscription" — expanded*  
* Inscription depth assessment  
* When substrate replacement is the only option

**5\. Communication & Coordination**

* **SALVAGE: "We communicate affordances, not meaning"** ← *axiom, with implications*  
* Pivot spaces  
* Cognitive Pidgin  
  * **SALVAGE: The Dogs** ← *domestication as worked example of anthropomorphism-as-bridge*  
* Stress as telemetry / arbitration signal  
* **SALVAGE: Cancer as failed social contract** ← *cells pivoting to immediate survival; destructive communication is still communication*

**6\. Collective Pathologies**

* The Scaled Tarrasque (distributed capture)  
* Moloch dynamics  
* Why "just change the norms" fails  
* Distributed inscription and the coordination problem

**7\. Deep Lore (Optional / Speculative)**

* Free Will as Frame Fluency ← *harmonizing sidebar translations: Compatibilist, Hard Determinist, Libertarian, Buddhist, Existentialist, Control Theorist*  
* Polycomputing (what it is, what it isn't, leverage ≠ validity)  
* **SALVAGE: "No bedrock, but practical pivots"** ← *dropping bedrock isn't dropping constraint*  
* The Cognitive Genepool (why diversity matters)  
* **{meta} The Physics of Morality** ← *if you want to go there*

**8\. Failure Modes of This Book**

* Goodhart risk on the framework itself  
* Map fetishism  
* Teleophobia (refusing agency attribution when it would help)  
* Anthropomorphic overreach (arguing with level-0 systems)  
* **ADD: "If the framework can explain any outcome, it explains nothing"**

---

### **0\. Session Zero: The Engineering Contract

    Before you pick up the wrench, you must check your credentials.

This book moves from Navigation (surviving the world) to Architecture (changing the world). It offers tools to edit goals, rewire constraints, and reshape the environments of other agents.

To use this book, you must agree to three constraints:
1. Consent to Engineer.

You are not the protagonist of other people's lives.

    For Yourself: You have root access. Edit away.

    For Others: Do not rewire systems that have not asked for your help, unless you have explicit duty-of-care (Parent/Government).

    The Rule: Engineering without consent is just high-competence bullying.

2. Teleophobia vs. Overreach.

    Teleophobia: Refusing to see agency where it exists. (Treating a person like a broken machine).

    Overreach: Projecting agency where it doesn't exist. (Arguing with a thermostat).

    The Balance: Use the "Is It An Agent?" tests in the Frame Lab. Don't guess.

3. The Stop Rule (The Falsifier).

Never pull a lever if you don't know what "Being Wrong" looks like.

    The Check: Before you intervene, complete this sentence: "I will know I broke it if..."

    The Exit: If you cannot define failure, you are not allowed to attempt success.

### **1\. What This Book Is For**

* Moving from navigation to architecture  
* Success criterion: choose interventions without arguing ontology

### **2\. The Persuadability Matrix (PM2-v2)**

#### Targeting Without Ontology Drift

* **TODO: salvage from original: Cancer (collective/biological)** ← *preserve the diplomacy vs. carpet-bombing framing*

#### What this section is for (success criterion)

By the end of this section, a reader should be able to:

* **Choose the right intervention interface** for a system *without* arguing about what the system “really is”  
* Diagnose **why persuasion keeps failing**  
* Avoid mixing **agency attribution**, **affordances**, and **substrate access**  
* Predict **backfire modes** before pulling a lever

If the reader stops trying to “convince” thermostats and stops rewiring humans, this section worked.  
---

#### Core correction (why v1 needed revision)

The original PM2 mixed **two orthogonal questions**:

1. *At what level is this system persuadable?* (Levin’s axis)  
2. *What kind of intervention am I attempting?* (World / Map / Goal / Substrate)

Those are not the same dimension.

* Levin’s axis answers: **what interface does the system respond to?**  
* Your intervention triad answers: **what are you trying to change?**

PM2-v2 separates them cleanly.  
---

#### The Persuadability Axis (Levin)

This axis is **observer-relative and empirical**. You do not argue it — you test it.

| Level | Interface | What works here | What fails here |
| :---- | :---- | :---- | :---- |
| **0\. Physical** | Rewiring / damage | Surgery, hardware changes | Arguments, incentives |
| **1\. Setpoints** | Parameter flooding | Drugs, environment control | Moral reasoning |
| **2\. Training** | History-dependent learning | Conditioning, RL, shaping | One-shot persuasion |
| **3\. Reasoning** | Symbolic / linguistic | Arguments, reframes | Micromanagement |

**Rule:** If an intervention at level *n* fails repeatedly, test *n−1*.  
---

#### Intervention Targets

These describe **what is being modified**, not *how*.

| Target | What changes | Where it lives |
| :---- | :---- | :---- |
| **World-change** | Constraints, costs, access | Environment / substrate |
| **Map-change** | Projections, salience, models | Agent representations |
| **Goal-change** | Value function, priorities | Control policy |

These are **coupled**, but still distinguishable.  
---

#### PM2-v2: The Correct Crossing

Instead of a single grid, PM2-v2 uses a **two-step targeting procedure**.

##### Step 1: Identify the persuadability interface

(What level does this system respond to?)

##### Step 2: Select the intervention target

(What do you actually want to change?)

Then evaluate **fit, cost, and backfire risk**.

---

#### Worked Targeting Examples

##### Example A: Metric Maximizer (Institution)

* **Persuadability level:** Training / Reasoning (2–3)  
    
* **Observed failure:** Reasoning-level appeals bounce  
    
* **Diagnosis:** Deep inscription via incentives → training-level lock-in  
    
* **Effective move:**  
    
  * **World-change:** cap metrics, remove leaderboard  
  * **Goal-change:** replace proxy, not argue about values


* **Backfire risk:**  
    
  * Map-change only → ☠️ Goodhart amplification

---

##### Example B: Addiction (Individual)

* **Persuadability level:** Setpoint \+ Training (1–2)  
    
* **Observed failure:** Insight without behavior change  
    
* **Diagnosis:** Map updated, actuator not accessible  
    
* **Effective move:**  
    
  * **World-change:** friction, removal of triggers  
  * **Training:** habit substitution


* **Backfire risk:**  
    
  * Pure reasoning → ☠️ System-2 capture / justification loops

---

#### Why “Affordances” sit where they do

Affordances are **map-level compressions of world regularities**.

* You cannot directly change affordances  
    
* You change them by:  
    
  * World-change (what works)  
  * Map-change (what is noticed)  
  * Goal-change (what is tempting)

Treating affordances as “inviting” action is **a modeling stance**, not a mechanism.

The Persuadability Matrix cares only about **what sticks**.

---

#### Engineering heuristics (DM screen material)

* **If persuasion feels emotionally rich but behavior doesn’t move → wrong level**  
* **If behavior changes but meaning collapses → map lag**  
* **If the system optimizes harder after punishment → you fed it**  
* **If nothing works → substrate or exit**

---

#### Common failure modes (callouts)

* **Teleophobia:** refusing agency attribution when it would increase leverage  
* **Anthropomorphic overreach:** arguing with level-0 systems  
* **Map fetishism:** endlessly reframing with no actuator access  
* **Depth mismatch:** shallow tools vs deep inscription

---

#### What this section is *not* doing

* It is not defining consciousness  
* It is not ranking moral worth  
* It is not claiming stable ontology

It is answering one DM question:

*“Where do I put my hands if I want something to change?”*

---

### **3\. The Frame Lab**

## aka, the Optional Rigor Ladder (for the skeptical engineer)

#### Design-time versus Play-time

**Hard Lesson:** Applying rigor too early and too hard will suck the joy out of whatever you're doing, unless you're an Alpha Engineer (and it's okay to not be an Engineer at all). Make sure you're picking the right time and the right places to apply rigor. **Rigor should constrain artifacts, not imagination.**

The full Frame Lab is an optional DM-facing Ritual Spell. The Minimum Viable Version shown next is an optional Player-facing Cantrip.

#### F0 The Minimum Viable Version (Hint: Use this version and stop here)

* **Frame in 1 sentence:** "In this situation, the dominant frame is \_\_\_ (or the frame stack is \_\_\_)."  
* **Prediction (1 line):** "If that's true, we should see \_\_\_."  
* **One observation you can do anyway:** a note you'd naturally notice next time.  
  * Notice **language** (what words recur / taboo words)  
  * Notice **attention** (what gets ignored / rushed past)  
  * Notice **options** (what feels "not possible")  
* **Stop when:** you have a prediction that changes what you'll notice or do.

##### Other Ways to Test

* **Retrospective:** Pick a past argument / bad meeting / personal spiral. Does a frame predict the failure mode?  
* **Compare two frames:** "If frame A, we'd do X; if frame B, we'd do Y." What actually happened?  
* **A/B attention test:** Deliberately shift P for one day; log 3 moments where it changed A or C.  
* **Sanity check:** If this frame doesn't change what I'd predict or do, it's probably decorative

#### F1 Rigor, how not to slide into "anything goes"

This is the anti-“anything goes” gate/validity spec:

* **Define a regime R \= (Objective O, Horizon T, Budgets B, Perturbations U, Pivot requirements K).**  
* A frame F is **valid in R** if:  
1. **Objective fit**: moves O in the right direction  
2. **Budget fit**: stays inside B (time/energy/attention/risk)  
3. **Robustness**: survives U (noise, adversaries, drift)  
4. **Stability**: doesn’t create runaway side effects over T  
5. **Coordination fit**: if coordination matters, it can sync via pivot spaces without catastrophic mismatch  
* Each criterion should be paired with at least one measurable observable  
  :: Note that **valid** is graded not binary

#### F2 Converting thought experiments into testable case studies.

##### F2.1 Case template

* **:: Regime declaration**: O, T, B, U, K  
* **:: Frames list**: F₁…Fₙ (projection \+ policy \+ goals)  
* **:: Overlap map**: what actuators/resources are shared? (where collisions happen)  
* **:: Falsifiers**: 2–3 ways the model could be wrong  
* **:: Predicted interference signatures**: oscillation, hijack, resource drain, narrative capture  
* **:: Expected inscriptions**: what traces will appear if each frame “wins”?  
* **:: Telemetry plan**: what do we measure (stress, error, throughput, stability)?  
* **:: Interventions**: (world-change / map-change / goal-change)

:: What happens if we do nothing? What happens under the dominant existing frame?

#### F3 Instrumentation

How to keep {eng} honest

* :: If “no usage is privileged,” then **measurement is our privilege mechanism.**  
* :: Potential observables:  
  * :: Selection / leverage: persistence of a frame in repeated conflicts; reinforcement loops; “hijack signatures.”   
  * :: Inscription: appearance of stable traces (tools, routines, norms) after enactment.   
  * :: Pivot-space sync: reduced cycle time to agreement; fewer “same word, different affordances” failures.   
  * :: Stress telemetry: self-report \+ behavioral correlates; does burden/relief predict shifts?  
* Stress/throughput are leading indicators; inscriptions are lagging.

#### F4 Unit Tests (Falsifiers)

* :: Bedrock / pivot claims  
  * :: If “shared pivots” don’t improve coordination outcomes, pivot-space synchronization is mischaracterized.   
  * :: If math doesn’t behave like a stable attractor across diverse agents in relevant regimes, “math as pivot attractor” is overfit.   
  * :: If agents coordinate better without shared maps (and this generalizes), the “pivot space” mechanism is not necessary.  
* :: Inscription–selection claims  
  * :: If enactment leaves no persistent traces, inscription is not doing the explanatory work claimed.   
  * :: If dominant frames do not correlate with leverage/stability (and hijack signatures don’t matter), selection-by-leverage is wrong.   
  * :: If “truth-ish” frames always win over leverage frames in real mixed incentives, the model’s cynicism is too strong.   
* :: Qualia / stress claims  
  * :: If stress does not track persistent inference gaps, the telemetry hypothesis fails.   
  * :: If changing span/resolution/intensity doesn’t change stress as predicted, the burden/relief model fails.   
  * :: If “map-change / world-change / goal-change” doesn’t cover most repair moves, the triad is incomplete.

#### F5 In Case of Fire, Break Glass

The Frame Lab is a scaffold, and scaffolds can be misused. Things to watch out for:

* **Goodhart risk:** optimizing observables breaks the phenomenon  
* **Observer effect:** measurement perturbs the system  
* **Overfitting regimes:** a frame passes your test in R but fails elsewhere  
* **Metric capture:** “coordination” improves while truth drifts
* **The Fractal Discernment Trap:** Because reality is fractal, you can always increase Resolution. You can always find more nuance, more sub-cases, more exceptions.

    The Danger: If you equate "Truth" with "Maximum Resolution," you will never act. You will spiral down into infinite detail (Analysis Paralysis).
    The Fix: Pragmatic Stop Rules. You stop zooming in when further Resolution no longer changes your Prediction or your Action.

    "Is this difference a difference that makes a difference?" — Bateson
---

### **4\. Inscription Engineering**

* Working with inscription, not against it  
  * Don't delete—redirect  
  * Inscribe the edit  
  * Find the shallow points  
  * Build new roads  
  * Don't argue in a captured pivot space  
* **SALVAGE: The Recursive Trap** ← *"the capacity to edit inscription is itself a target of inscription" — expanded*  
* Inscription depth assessment  
* When substrate replacement is the only option

### **5\. Communication & Coordination**

* **SALVAGE: "We communicate affordances, not meaning"** ← *axiom, with implications*  
* Pivot spaces  
* Cognitive Pidgin  
  * **SALVAGE: The Dogs** ← *domestication as worked example of anthropomorphism-as-bridge*  
* Stress as telemetry / arbitration signal  
* **SALVAGE: Cancer as failed social contract** ← *cells pivoting to immediate survival; destructive communication is still communication*

### **6\. Collective Pathologies**

* The Scaled Tarrasque (distributed capture)  
* Moloch dynamics  
* Why "just change the norms" fails  
* Distributed inscription and the coordination problem

### **7\. Failure Modes of This Book**

* Goodhart risk on the framework itself  
* Map fetishism  
* Teleophobia (refusing agency attribution when it would help)  
* Anthropomorphic overreach (arguing with level-0 systems)  
* **ADD: "If the framework can explain any outcome, it explains nothing"**

---

**Space intentionally left blank.**
