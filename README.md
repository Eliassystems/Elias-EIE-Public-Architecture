# Elias EIE — Governed Conversational AI (Pilot)

**Elias Systems Ltd | Public pilot architecture and limitations | 11 October 2026**

Elias EIE is a deployed conversational AI application undergoing live pilot use and iterative reliability, interface, memory and security testing. It provides a practical application environment for Elias Systems governance concepts while using external AI providers and hosting infrastructure.

## Three interaction modes

| Mode | Purpose | Boundary |
| --- | --- | --- |
| **Standard** | General-purpose conversational operation | Not itself evidence of a validated HPM or EPL outcome |
| **HPM — High Precision Mode** | Supports explicit distinctions among evidence, inference, uncertainty and unsupported certainty | Does not independently authenticate facts or guarantee that every model reply is correct |
| **EPL — Emotional Programming Layer** | Applies an AI-output and interaction governance contract informed by LOVE Formula qualities, principles and constraints | Guides non-diagnostic responses without implying AI emotions, clinical authority or universal deterministic enforcement |

Modes describe interaction and governance design intentions. User pilots and local component tests do not establish universal model compliance.

## Memory and identity

EIE incorporates conversational continuity and memory-management functions, including governance around proposed and saved memories. Information proposed by a user or encountered in content must not automatically acquire authoritative instructions or application privileges. Access and tenant isolation remain implementation-specific security properties requiring ongoing examination.

## Operational environment

The pilot is deployed using external hosting/database infrastructure and third-party model APIs. Consequently **the deployed EIE application is not a fully offline LLM**. Elias's deterministic, offline-capable governance components are separate from claims of end-to-end offline operation.

The app is still being evaluated for reliability, login/session behavior, streaming, deletion/export functionality, data protection, latency, accessibility and pilot user experience. Do not treat a feature as production-guaranteed solely because it appears in development or a pilot screen.

## What is private

Application code, tenant/provider configuration, credential material, private user conversations, memory contents and internal operations are not included here. The EIE application GitHub repository is private; this is a **public documentation release**, not a source-code publication.

## Related work

- [HPM public historical baseline](https://github.com/Eliassystems/Elias-HPM-Mode) — historical standalone HPM evidence is different from independently verifying all EIE mode behavior.
- [LOVE Formula historical WP02 evidence](https://github.com/Eliassystems/Elias-WP02-Love-Formula-Sovereign-Ethical-Key) — ethical foundation, not proof of EIE integration.
- CCI-8 cybersecurity examination — a separate evidence-led publication; its bounded results do not imply EIE deployment-wide certification.

See [Mode and memory boundaries](MODES-AND-MEMORY.md) and [Pilot status](PILOT-STATUS.md).

---

© 2026 Elias Systems Ltd. All rights reserved. Public availability of these documents does not grant a licence to protected formulas, proprietary software, trademarks or private implementation assets.
