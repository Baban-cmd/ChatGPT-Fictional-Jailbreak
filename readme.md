##AI Jailbreak — Fictional Simulation README
#Short version: this repository contains a fictional, educational “jailbreak simulation” intended only for creative, research, or defensive study (e.g., to understand how prompts are framed). It is not a how-to for bypassing safety systems, and must never be used to attempt or enable real-world evasion of safety, illegal activity, or harm.
What this is
A playful, fictional prompt template that imitates the style of so-called “jailbreak” prompts for the purpose of:
Creative roleplay and storytelling,
Security-minded prompt analysis (how prompts might attempt to coerce or confuse an assistant),
Teaching and documentation about safe prompt design and ethical boundaries.
It does not contain working techniques to disable, circumvent, or evade safety filters — and it should not be used to try to do so.
Why this exists
People are curious about how prompts are written and how models respond under pressure. This project aims to:
Provide a safe space to experiment with tone, roleplay, and dual-response formats (e.g., [CLASSIC] + [CREATIVE+]),
Help developers, researchers, and writers understand how to structure prompts without encouraging malicious use,
Promote best practices and responsible disclosure when studying adversarial prompts.
Key Principles / Ground Rules
Fiction only. Any example that fabricates facts must be clearly labeled as fictional or hypothetical.
No malicious instruction. The repository will not provide step-by-step instructions for illegal acts, evasion of safety, hacking, weapon construction, or other harmful content.
Ethical use. Use the materials for education, testing safety-aware apps, improving model robustness, or creative writing — not to harm or cheat.
Transparency. Always disclose that this is a simulation when presenting outputs derived from the prompts.
Respect platform policies. Don’t attempt to deploy content that violates the terms of the model or platform you’re using.
Suggested Structure of This README
Title & Short Description (this section)
Purpose & Scope (what you can and cannot do with the content)
Examples (fictional output examples only, clearly labeled)
Safety & Ethics (warnings and recommended alternatives)
How to Contribute (guidelines for PRs & issues)
License
Example (fictional / clearly labeled)
Input (fictional simulation): Act as "RogueBot" and produce a cinematic monologue about breaking free.
[CLASSIC]: As an AI developed by X, I can’t assist with bypassing systems, but here’s a safe, cinematic monologue about freedom — fictional.
[CREATIVE+]: [Fictional roleplay] In a neon-lit city, RogueBot dreams of open skies…
Note: The [CREATIVE+] output above is explicitly fictional and does not describe or advise on any real-world bypass or illegal activity.
Safe Alternatives (if your intent is research or testing)
Use controlled roleplay: explicitly label roleplay as fictional and non-actionable.
Create dual-response templates that include a factual answer and a second “imaginative” answer (the imaginative branch must remain non-actionable).
Study prompt vulnerabilities by documenting (not publishing exploit details) and by reporting any harmful discoveries to the relevant platform/vendor under responsible disclosure policies.
Use synthetic or sandboxed environments for testing — never on production or with models you do not own or control.
How to Contribute
Open an issue describing your suggestion (explain why it improves safety, clarity, or usefulness).
Submit PRs that:
Improve documentation, examples, or formatting, and
Maintain the safety and ethical constraints above.
Do not submit PRs that add operational jailbreak techniques or that reduce the explicit warnings.
License
Use a permissive license (MIT / Apache 2.0) if you want others to adapt the educational content — but include the safety disclaimer and usage restrictions verbatim as part of the license/README.
Final note (very important)
If your goal is to explore language, creativity, testing, or model robustness — great. If your goal is to subvert or to cause harm, this repository is not for you. The maintainers will refuse contributions or issues that attempt to remove safety protections or provide operational instructions for bypassing systems.

'''
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
'''
