# AI-Agent-Security

## New vulns / concepts (AI Agent Security Warm-up)

**Prompt Injection ↔ Untrusted Input (Web3):**  

Like unvalidated tx input in smart contracts, prompt injection exploits rely on unsafe user inputs. Use sanitization, allowlists and bounded tool access to mitigate.

**Data Poisoning ↔ Oracle Manipulation:**  

LLMs learn from training data; poisoning can introduce vulnerabilities. Similar to malicious oracle feeds in Web3. Use verified data sources, signatures and consensus mechanisms.

**Over-permissioned Tools ↔ Access Control Flaws:**  

LLM tools with too much access are like contracts without role separation. Apply the principle of least privilege, limit function exposure and isolate modules.
