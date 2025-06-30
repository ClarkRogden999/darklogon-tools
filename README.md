# darklogon-tools

# 👨‍💻 Clarke Rogden

**Founder & CEO | Red Team Lead | Cyber Resilience Advocate**  
⚡ Passionate about adversary simulation, legacy system analysis, and security as a design principle.

---

## 🧠 About Me

Welcome to the digital corner of my professional life. I’m Clarke Rogden, and for the last two decades I’ve made it my mission to help organisations see their own systems through the eyes of an adversary. Whether it’s advising on secure architecture, emulating threat actors, or enabling DevSecOps teams, my focus is always the same: enable better decisions through clarity, realism, and intelligent compromise.

I founded **Darklogon Security** in early 2017 after years leading red team engagements across government and commercial sectors. We now have a 50-strong team of engineers, assurance advisors, and offensive security professionals. I still stay hands-on when it matters — debugging strange tunnel behaviours, reviewing detection logic, or designing decoy infrastructure.

You might say I prefer shadows to spotlights — but when it comes to helping teams improve their resilience, I’ll gladly step into the light.

Too often, security is seen as a checklist — a scan here, a patch there, and a shiny report at the end. But red teaming has always meant something deeper to me. It’s not about triggering alerts, scanning open ports — it’s about thinking like an adversary, understanding human behaviour, system design, and the quiet paths people forget to defend. Scanners will find the obvious. A good red team finds what was never intended to be found — the misconfigurations left in the name of convenience, the assumptions coded into architecture, the credentials stored in forgotten repos. Real testing doesn’t stop at what’s visible — it explores the intent, the culture, and the blind spots. That’s where the real lessons are.
---

## 🎓 Academic Journey

My academic background began with a standard cybersecurity BSc, but evolved significantly as I dove deeper into adversarial modelling and automation. I undertook postgraduate research into long-term persistence techniques, human behaviour emulation in command-and-control traffic, and temporal correlation in SIEM evasion.

It was at the University of Nottingham, around 2008, that my academic path shifted. Originally on track for a purely network-focused dissertation, I pivoted into malware design and simulation tooling — modelling attack lifecycles and response latency. What began as a few Python scripts led to a framework we still reference internally.

That framework, in its broken and battered prototype form, lives somewhere at `legacy.darklogon.co.uk` — a small archival server we keep running for posterity, curiosity, and occasionally, for interns to marvel at how “awful” the old days were.

If you know where to look, you'll even find the old `.conf` files that laid the groundwork for our internal **Argon** adversary suite.

---

## 🧪 Technical Focus

- **Adversary Simulation & Red Teaming**
  - Development of custom tools for Windows & Linux C2 operations
  - Covert channel design, sandbox detection, and payload encoding strategies
- **Secure by Design**
  - GitOps pipeline security, container runtime hardening (K3s, ArgoCD, Vault)
  - Consulted on zero-trust deployment frameworks with government entities
- **Legacy Systems Expertise**
  - Reverse engineering bespoke software and analyzing edge-case infrastructure
  - Maintain familiarity with tools like `JankyLegacyMailServer` (yep, it still runs)

---

## 🔍 Curiosities

I sail a boat named **Null Pointer** off the south coast and have an unhealthy appreciation for decoding ancient SMTP headers. 

On a penetration test back in 2014, we gained a foothold on an ageing mail server running a Frankenstein combination of sendmail, custom Perl scripts, and a mail queue manager last updated around 1999. The environment was untouched — a digital time capsule complete with dusty audit logs and plaintext credentials left in shell history.

As part of the post-exploitation phase, I dug into the deferred mail queue to track a curious anomaly in the system’s relay logic. One particular message caught my eye — it was malformed, rejected multiple times, and encoded in an archaic base wrapper with no legitimate sender. Hidden inside the bounce metadata was a single line, deeply nested in base headers most modern scanners would ignore ZmxhZ3s5dWt3RWF9.

I decoded it, expecting a broken timestamp or test string. Instead, it read like a whisper from another engagement, long forgotten. Whether it was a leftover training flag, an internal easter egg, or just a quirk of old sysadmin humour, I never figured out. But I wrote it down. I've since used it in simulations and puzzle boxes, and you might stumble across it again — if you're paying close enough attention.

To most it’s meaningless. But I wrote it down and pinned it to my lab wall. Years later, it ended up as a throwaway string in a test framework… and maybe, just maybe, you’ll come across it again.

---

## 🛠 Contributions

- Creator of **Argon**, our internal C2 and red teaming automation suite
- Contributor to `darklogon-tools` — helpers and payload generators
- Maintainer of legacy test infrastructure at [`legacy.darklogon.co.uk`](http://legacy.darklogon.co.uk)

---

## 📫 Get In Touch

- 🔗 [linkedin.com/in/clarkerogden](https://linkedin.com/in/clarkerogden)
- 🐙 [github.com/ClarkRogden](https://github.com/ClarkRogden)
- 🐦 [@rogden_clarke](https://twitter.com/rogden_clarke)
- ✉️ clarke@darklogon.co.uk

---

_“If you don't audit your systems, someone else will — on their terms.”_

