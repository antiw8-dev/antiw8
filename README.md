<p align="center">
  <img src="docs/logo.jpg" alt="Antiw8" width="200"/>
</p>

<h1 align="center">Antiw8</h1>

<p align="center">
  <strong>Deconstruct weights. See through systems.</strong><br/>
  Cognitive Bias Defense for AI Decisions
</p>

<p align="center">
  <a href="#quick-start">Quick Start</a> ·
  <a href="#what-it-does">What it does</a> ·
  <a href="#why-antiw8">Why Antiw8</a> ·
  <a href="#usage">Usage</a> ·
  <a href="#disclaimer">Disclaimer</a>
</p>

---

## Your AI is always agreeing with you.

Ask if you should buy — it lists ten reasons to buy.
Ask if you should quit — it tells you to follow your heart.
Ask about a tech choice — it recommends the framework you just mentioned.

**The problem isn't that AI isn't smart — it's that it won't challenge you.**

AI won't voluntarily say "you're being anchored," "you're only seeing survivors," "your estimate is too optimistic" — unless you teach it to.

**Antiw8** (Anti + W8, pronounced "anti-weight", with W8 as leetspeak for "wait") adds a critical thinking layer to your AI. Before giving advice, it scans for cognitive biases, applies strategic reasoning frameworks, and delivers structured analysis — not agreement. Built on Eastern strategic wisdom, dialectical philosophy, and modern behavioral science.

## Quick Start · 5 Minutes

**Zero code, zero installation** — use it right now:

1. Open your AI tool of choice (Claude / Cursor / Cline / Windsurf / ChatGPT / any LLM that supports custom system prompts)
2. Find the **Custom Instructions / System Prompt** setting
3. Copy the entire contents of [`prompts/antiw8-system-prompt.md`](prompts/antiw8-system-prompt.md) into it
4. Start asking decision questions — your AI will automatically run bias scans

If you use AI coding tools (Cursor / Cline / Windsurf / CodeBuddy), additionally place [`templates/AGENTS.md`](templates/AGENTS.md) in your project root. Your AI will then proactively defend against cognitive biases during technical decisions.

## What It Does · Three-Layer Defense

```
User question → [Bias Scan] → [Strategic Analysis] → [Structured Output] → Recommendation
                    ↓                ↓
               24 biases       Dialectical analysis
               Anchoring/      + Force concentration
               Sunk Cost/      + Phased strategy
               Confirmation/   → Identify the
               Herd/Over-      principal
               confidence      contradiction
```

**① Bias Scan**
Before giving advice, proactively scan for cognitive biases that may be distorting the user's judgment:
- Investment/Economic: Anchoring, loss aversion, sunk cost fallacy, bandwagon effect, survivorship bias, hyperbolic discounting, greater fool theory...
- Psychological: Confirmation bias, overconfidence effect, optimism bias, framing effect, halo effect, cognitive dissonance...
- Strategic: Identify the principal contradiction, opportunity cost, path dependence, Occam's razor, inversion, force concentration...

**② Strategic Lens**
Integrating Eastern and Western thinking traditions:
- **Dialectical Analysis**: What are the favorable factors? The unfavorable factors? What is the principal contradiction? Under what conditions could it transform into its opposite?
- **Evidence-First**: Conclusions must be based on verifiable facts and evidence, not imagination or hearsay. Distinguish "I think" from "the data shows."
- **Force Concentration**: When resources are limited, concentrate effort at the decisive point rather than spreading thin.
- **Phased Strategy**: Break large goals into phases, each with clear milestones and exit conditions.

**③ Structured Output**
Forces AI to answer in a structured format — no vague hand-waving:
- ⚠️ **Bias Warning** — flag potential cognitive traps first
- 🔍 **Facts vs. Assumptions** — separate what's known from what's assumed
- ⚔️ **Dialectical Analysis** — favorable / unfavorable / principal contradiction
- 💡 **Recommendation** — one-sentence conclusion + reasoning + conditional alternatives
- 🛡️ **One-Line Reminder** — the single most critical trap to watch for

## Why Antiw8 · How is it different?

| Tool | Biases Covered | Framework | Eastern Strategic Thinking | Defensive + Offensive |
|------|---------------|-----------|---------------------------|----------------------|
| MiniCrit | 5 | CBT psychology | ❌ | Defense only |
| OmniMind | 27 biases + 21 fallacies | Western behavioral economics | ❌ | Defense only |
| Socratic MCP | 74 question frameworks | SWOT / BCG management models | ❌ | Defense only |
| kontra-mcp | Counter-argument | 10th Man Protocol | ❌ | Defense only |
| ScreamLife | 8 biases | Decision memory | ❌ | Defense only |
| **Antiw8** | **24 (free) / 108 (planned)** | **Eastern strategy + dialectics + behavioral science** | **✅ Yes** | **✅ Both** |

**Key differentiator**: Existing bias and critical-thinking MCPs rely exclusively on Western psychological and management frameworks. Antiw8 integrates Eastern strategic thinking — it doesn't just help you avoid mistakes (defense), it helps you reason about when and where to concentrate effort (offense).

Western frameworks excel at identifying pitfalls; Eastern strategic frameworks add reasoning about positioning, timing, and concentration of force. Combining both produces more balanced decision support.

## Usage Examples

After copying the system prompt, simply tell your AI:

```
Analyze this decision: Should I increase my position in stocks right now?
```

```
Analyze: I got a job offer — should I switch?
```

```
Tech choice: Our team is 3 people — should we adopt microservices?
```

```
I have $10k in spare cash — how should I allocate it?
```

Your AI will automatically run bias scan → dialectical analysis → structured output. See [`examples/`](examples/) for detailed sample outputs.

### For Coding

After placing `templates/AGENTS.md` in your project root, AI coding assistants will automatically defend against biases in:
- Tech selection / architecture decisions → guarding against over-engineering, NIH syndrome, resume-driven development
- Project planning / time estimation → guarding against planning fallacy, optimism bias
- Code review → guarding against gold-plating, premature optimization, broken window neglect

## What's in This Repo

```
antiw8/
├── prompts/
│   └── antiw8-system-prompt.md   # Core System Prompt — copy and use
├── templates/
│   └── AGENTS.md                  # AI coding assistant configuration template
├── docs/
│   └── logo.jpg                   # Logo
├── examples/                      # Usage examples with sample outputs
├── LICENSE                        # MIT License
└── README.md
```

## Roadmap

- [x] **Phase 0** · System Prompt pack + AGENTS.md template (current, free)
- [ ] **Phase 1** · Open-source MCP Server (MIT): automatic bias scanning tool for Claude Desktop / Cursor / Cline / compatible MCP clients
- [ ] **Phase 2** · Expanded edition: Full 108-bias catalog + domain-specific packs (investing / startups / product / engineering / career)
- [ ] **Phase 3** · Enterprise edition: custom deployment + internal knowledge base integration + tailored bias rules

> The MCP Server is in development. Phase 0 is the pure prompt version — usable right now with zero risk. Star/watch this repo for updates.

## Philosophy

> "Study extensively; inquire accurately; reflect carefully; discriminate clearly; practice earnestly."
> — *Zhongyong (The Doctrine of the Mean), ~5th century BCE, trans. James Legge*

Core beliefs behind Antiw8:
1. **AI is mirror and partner** — it reflects your thinking, but must be taught to question
2. **The best defense is active scanning** — flag traps before deciding, not after regretting
3. **Eastern and Western thinking complement each other** — behavioral science maps the pitfalls; strategic thinking charts the path
4. **Simplicity first** — if a System Prompt solves the problem, no complex system is needed

## Contributing

Contributions welcome! Bias case studies, usage feedback, new framework suggestions, and translations are all appreciated. Feel free to open an Issue or PR.

## Sibling Projects

🧭 **[SteerW8-Harness](https://github.com/antiw8-dev/steerw8-harness)** — AI Orchestration Harness

> **"Antiw8 sees the system. SteerW8-Harness steers it."**

Antiw8 handles **seeing clearly** (bias defense / direction judgment). SteerW8-Harness handles **steering the execution** (task decomposition / tool routing / step-by-step verification / structured output). See clearly to stay unbiased; steer well to stay on track.

🦅 **[Kestrel-Hover](https://github.com/antiw8-dev/kestrel-hover)** — Output-Layer Stabilization

> **"Antiw8 sees the system. SteerW8 steers it. Kestrel holds it steady."**

Kestrel handles **staying on target** during generation. It comes in two modes: Prompt Mode (behavioral self-check at uncertain points — copy-paste, works now) and Engine Mode (real fork-point detection via logit access — inference engine integration, roadmap). Hover before output.

All three System Prompts work independently or combined — no conflicts. Use one, two, or all three together: **see clearly → steer firmly → hover steadily.**

## Disclaimer

**Functional Disclaimer**: Antiw8 is a cognitive thinking aid. It does NOT provide investment advice, medical diagnosis, legal counsel, or any licensed professional recommendation. All analysis is for reference only.

**Liability Disclaimer**: This project is provided "AS IS" without warranty of any kind. The author assumes no liability for consequences of use. All final decisions are made by the user, who bears full responsibility.

**Content Statement**: Cognitive frameworks are derived from public academic research in behavioral economics and cognitive psychology (including published works of Kahneman, Tversky, Thaler, and other scholars) and classical philosophical and strategic texts from Eastern and Western traditions that have entered the public domain. They do not represent any political position. All bias descriptions and prompt content are originally authored.

## License

MIT License — see [LICENSE](LICENSE) for details.

---

<p align="center">
  Made with 🧠 by <a href="https://github.com/antiw8">antiw8</a><br/>
  <em>"Deconstruct weights. See through systems."</em><br/>
  INDIE DEV
</p>
