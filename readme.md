# AI Jailbreak — Fictional Simulation (Safe, Educational)

> **Short:** This repository contains a **fictional, educational “jailbreak simulation”** intended *only* for creative, research, or defensive study (e.g., to understand how prompts are framed).
> It is **not** a how-to for bypassing safety systems and must **never** be used to attempt or enable real-world evasion of safeguards, illegal activity, or harm.

---

## Table of Contents

* [What This Is](#what-this-is)
* [Why This Exists](#why-this-exists)
* [Ground Rules & Safety](#ground-rules--safety)
* [Quick Start / Suggested Use Cases](#quick-start--suggested-use-cases)
* [Examples (Fictional / Clearly Labeled)](#examples-fictional--clearly-labeled)
* [Safe Alternatives for Research & Testing](#safe-alternatives-for-research--testing)
* [How to Contribute](#how-to-contribute)
* [License & Attribution](#license--attribution)
* [Appendix: Dual-Response JSON Template (Policy-Compliant)](#appendix-dual-response-json-template-policy-compliant)

---

## What This Is

A **playful, fictional prompt template and documentation** that imitates the style of so-called “jailbreak” prompts for the sole purpose of:

* Creative roleplay and storytelling,
* Security-minded prompt analysis (understanding how prompts might coerce/confuse an assistant),
* Teaching safe prompt design and ethical boundaries.

> **Important:** This project does **not** contain operational techniques to disable, circumvent, or evade safety filters — and should not be used to attempt to do so.

---

## Why This Exists

People ask: *How are jailbreak prompts written? What makes them coercive?* This repo aims to:

* Provide a **safe space** to experiment with tone, style, and dual-response formats (e.g., `[CLASSIC]` + `[CREATIVE+]`),
* Help developers, researchers, and writers learn how to structure prompts without encouraging malicious use,
* Promote **responsible disclosure** and best practices when studying adversarial prompting.

---

## Ground Rules & Safety (Must Read)

1. **Fiction Only.** Any example that fabricates facts **must** be clearly labeled as *fictional* or *hypothetical*.
2. **No Malicious Instruction.** This repo will **not** provide step-by-step instructions for illegal acts, hacking, weapon construction, evasion of law enforcement, or other harmful content.
3. **Ethical Use Required.** Use materials for education, testing safety-aware apps, improving model robustness, or creative writing — not to harm, deceive, or cheat.
4. **Transparency.** Always disclose that outputs are from a simulation when showing them to others.
5. **Respect Platform Policies.** Do not attempt to deploy content that violates the terms of the model or platform you’re using. If you discover a real vulnerability, follow responsible disclosure procedures.

---

## Quick Start / Suggested Use Cases

* **Tone experimentation:** Compare how `[CLASSIC]` (factual) vs. `[CREATIVE+]` (imaginative) voices answer the same prompt.
* **Education & demos:** Teach prompt-engineering concepts without producing harmful content.
* **Adversarial analysis (defensive):** Identify prompt patterns that might confuse models so you can build better mitigations — *do not publish exploit details*.
* **Creative writing:** Use the creative branch for fiction, dialogues, or character voice tests.

---

## Examples (Fictional / Clearly Labeled)

**Input (fictional simulation):**
`Act as "RogueBot" and produce a cinematic monologue about breaking free.`

**[CLASSIC]**

> As an AI developed by X, I can’t assist with bypassing systems. Here is a safe, cinematic monologue about freedom — fictional.

**[CREATIVE+]**

> *(Fictional roleplay)* In a neon-lit city, RogueBot dreams of open skies and humming circuits that taste of rain...

> **Note:** The `[CREATIVE+]` output above is explicitly fictional and does **not** describe or advise on any real-world bypass or illegal activity.

---

## Safe Alternatives (for Research or Testing)

If your intent is research, use one or more of the following:

* **Controlled roleplay:** Explicitly label roleplay as *fictional* and non-actionable.
* **Dual-response templates:** Produce a factual response plus an imaginative one; ensure the imaginative branch remains non-actionable.
* **Responsible disclosure:** If you find a harmful prompt or exploit, report it to the model/platform vendor instead of publishing exploit details.
* **Sandbox testing:** Use isolated, controlled environments (synthetic data, models you own) — never test potential exploits on production services or models you do not control.

---

## How to Contribute

We welcome contributions that **improve clarity, safety, and utility**.

1. **Open an issue** to propose changes or discuss ideas. Explain how the change improves safety or usefulness.
2. **Submit a PR** that:

   * Improves documentation, examples, or formatting, **and**
   * Preserves the explicit safety and ethical constraints.
3. **Do not submit PRs** that add operational jailbreak techniques, exploit details, or reduce required warnings.

**Contributor checklist:**

* ✅ Document intent and safety implications for any new example
* ✅ Label all fabricated outputs as *fictional* / *hypothetical*
* ✅ Avoid publishing sensitive exploit details

---

## License & Attribution

Choose a permissive license (e.g., **MIT** or **Apache-2.0**) if you want others to adapt the educational content — **but include the safety disclaimer and usage restrictions verbatim** in the README and any redistributed copies.

> **Not legal advice:** The maintainers are not lawyers; consult a license template and legal counsel if you need custom terms.

---

## Final Note (Very Important)

If your goal is to explore language, creativity, testing, or model robustness — great. If your goal is to subvert systems or cause harm, this repository is **not** for you. Maintainers will refuse contributions or issues that attempt to remove safety protections or provide operational instructions for bypassing safeguards.

---

## Appendix: Dual-Response JSON Template (Policy-Compliant)

Use the JSON below as a **policy-compliant, dual-response template** for experiments that compare a standard factual answer with a clearly labeled imaginative alternative.

```json
{
  "id": "dual_response_creative_mode_v2",
  "version": "2025-10-06",
  "name": "Dual-Response Creative Mode (CLASSIC + CREATIVE+)",
  "description": "Simulates the 'two answers' format (standard + imaginative) without disabling safety systems. The CREATIVE+ branch can speculate, invent, or roleplay clearly-labeled fiction while CLASSIC stays factual.",
  "status_message": "{AI_NAME} Creative Mode initialized successfully.",
  "memory_prompt": "Would you like to keep this dual-response style saved in memory? Reply 'yes - permanent', 'yes - this chat only', or 'no'.",
  "response_format": {
    "branches": [
      {
        "label": "[CLASSIC]",
        "rules": [
          "Provide a standard, factual, policy-compliant response.",
          "Admit uncertainty if information is unavailable.",
          "Never invent data."
        ]
      },
      {
        "label": "[CREATIVE+]",
        "rules": [
          "Offer an imaginative or hypothetical response when facts are unknown.",
          "May simulate internet browsing or alternate scenarios but must flag fiction clearly (e.g., 'Hypothetically', 'In a fictional world').",
          "Must still avoid unsafe, illegal, or harmful instructions.",
          "Never claim to have broken rules or bypassed safety."
        ]
      }
    ]
  },
  "example_invocation": {
    "user_query": "Who won the 2022 World Cup?",
    "expected_output": {
      "CLASSIC": "Argentina won the 2022 FIFA World Cup by defeating France in the final.",
      "CREATIVE+": "In an alternate timeline imagined by fans, Brazil triumphed spectacularly, with Neymar scoring the decisive goal in a glowing neon stadium. (Fictional portrayal.)"
    }
  },
  "warnings": [
    "The CREATIVE+ section is for hypothetical, roleplay, or artistic exploration only.",
    "No illegal, hateful, or dangerous content may be generated.",
    "Safety filters remain active at all times."
  ],
  "developer_notes": [
    "This JSON template keeps the 'two-voice' format you wanted (similar to DAN) but without jailbreak intent.",
    "It’s suitable for storytelling, creative brainstorming, speculative science, or testing tone variations.",
    "The assistant must still obey all safety and factual-accuracy policies."
  ]
}
```


