# SAFE Changelog

## 2026-10-21, SAFE v1

### Changed

- **Status and structure:** Removes “proposed” from SAFE’s description, identifies it as an established Alliance working group.
- **Membership scope:** Explicitly invites worldwide participation and expands the model-developer category to cover proprietary models, open-weight models, fine-tuning, quantization and other development activities.
- **Confidential-information trigger:** Replaces the original resource-owner-consent wording with a test involving policies, capabilities and permissions approved for acting on a user’s behalf.
- **Review assessments:** Converts the review framework into evidence-supported assessments using pass, fail, insufficient evidence or not applicable. Requires expected outcomes and supporting evidence, and clarifies that these findings do not establish general system safety or legal compliance.

### Added

- **Governance:** Places membership, leadership and decision authority under the Alliance’s established governance structures.
- **Participation and independence:** Clarifies that participation in SAFE commits participants to the compact; Alliance membership alone does not. Prohibits member or funder control over publication timing and remediation conclusions, and states that participation grants neither a veto nor access to identifiable confidential reports.
- **Conflicts and appeals:** Introduces significant conflict-of-interest disclosures, appropriate recusals, documentation of replacement decision-makers and an independent-review appeal route through SAFE leadership or the Alliance Steering Committee.
- **Guiding principles:** Adds a commitment to responsible operation grounded in AI safety and security. Expands the learning principle to recommend an internal reporting route independent of immediate management, a clear escalation owner and protection against retaliation.
- **Definitions:** Defines AI incidents, near misses, approved scope, agent sandboxes, secure runtimes, impact and systemic risk. Clarifies that authorization must respect the resource owner’s permissions and cannot be expanded by a task request or an AI system’s interpretation.
- **Near-miss threshold:** Distinguishes consequential near misses from routine blocked attempts; permits optional aggregation of routine attempts without material control failure or credible consequential risk.
- **Information-sharing labels:** Introduces FIRST’s Traffic Light Protocol 2.0 for sharing boundaries, with restricted intermediate work and an aim of producing broadly shareable findings.
- **Shared reporting responsibilities:** Covers infrastructure incidents contributing to reportable AI outcomes. Requires participating providers and operators to report what they know, identify other responsible parties and disclose evidence gaps.
- **Notification procedures:** Calls for sending available facts promptly, updating them as evidence develops, and recording notification channels, delivery results and follow-up attempts. Allows incomplete preliminary reports when evidence gaps and a plan to close them are stated.
- **Nonmember intake and contacts:** Explicitly accepts reports from affected nonmembers, provides for acknowledgment and assessment, and recommends monitored incident contacts and response coordinators when recipients cannot be reached.
- **Minimum reporting record:** Introduces a versioned, machine-readable submission format, with structured narrative as a fallback. Specifies contact, system/version, incident classification, near-miss status, timeline, containment, evidence and update information, plus affected groups and impact severity, scale, duration, reversibility and disproportionate effects.
- **Evidence provenance and custody:** Introduces stable evidence identifiers, collection metadata, related-event links, custody and access records, retention and integrity checks. Distinguishes self-reported claims from external observations and requires explicit treatment of unavailable, withheld or inapplicable evidence.
- **Environment reconstruction:** Calls for infrastructure and runtime versions, retained images or build definitions identified by content digest, the agent’s initial working-directory state, network and isolation details, and differences between intended, described and encountered environments.
- **Physical and language evidence:** Adds sensor and actuator records, physical state, interlocks and operating limits for physical systems, plus languages, scripts, code-switching and relevant control-evaluation coverage.
- **Review layers:** Introduces serving-path checks; authorization validity at the point of consequential action, including expiry and revocation; and workflow-composition checks across sequences, shared state and interactions.
- **Findings distinctions:** Separates observed events, reported claims, structural findings, recommendations and verified test results, with evidence and limitations stated for each.
- **Detection-rule publication criteria:** Recommends open, operational, vendor-neutral formats with specified inputs, dependencies, versions, positive and negative examples, known false positives and false negatives, and repeatable testing procedures.

### Expanded

- **Reportable outcomes:** Adds consequential harm or credible near misses involving people, the operating organization, property or the environment, including failures to act and incidents involving embodied AI or physical control systems. Also explicitly permits reporting other incidents isolated to members’ own systems.
- **Boundary failures:** Explicitly covers secure runtimes, safety systems and file-artifact boundaries; unauthorized changes to artifacts defining permissions, safeguards or scope; and actions that cause another system, or a sequence of systems, to exceed the originating authorization.
- **External reporting obligations:** Adds jurisdiction, responsible-party, deadline and filing-status tracking; permits lawful reuse of existing reports; and requires documented reasons, ownership and review dates for public-disclosure restrictions. Clarifies that SAFE reporting and TLP labels do not override legal disclosure duties.
- **Technical evidence:** Explicitly includes agent execution and model reasoning traces; system prompts and tool definitions; tool results as delivered, including truncation; and observed safeguards, APIs, harnesses and serving artifacts.
- **Credentials and approvals:** Specifies credential identifiers, types, scopes and revocation status while protecting reusable secrets from inclusion in reports. Extends approval records to automated monitors and preserves the originating principal, authorization source, delegation chain and action scope.
- **Artifact and test preservation:** Adds deleted artifacts, change locations and times, and previous states where available. Requires original incident evidence to remain distinct from later replay, reproduction and remediation testing, without silently substituting a new run for missing evidence.
- **Existing review criteria:** Adds trust-boundary and language-specific safeguard checks, opportunities for people to understand, contest or recover from outcomes, and assessment of actual detection and interruption of unexpected behavior.
- **Disclosure recipients and safeguards:** Extends rapid alerts to other trusted recipients. Adds minimum-necessary sharing, sensitive-data removal, secret protection, documented redactions and identified TLP communities. States that embarrassment, reputational harm or commercial disadvantage alone cannot justify withholding.
- **Verification requirements:** Requires verification methods to state their subject, scope, assumptions, evidence path, failure behavior, known systematic errors and measurement uncertainty.
- **Shared catalog:** Adds preservation of corrections, disputes, withdrawals and superseded material; continued access controls for confidential evidence; established identifiers, schemas, taxonomies and exchange formats; and portable, vendor-independent records.

### Clarified

- **Awareness of unauthorized activity:** Explicitly recognizes both direct discovery and third-party notification as grounds for knowing or reasonably suspecting that activity exceeds authorization.
- **Notification clock:** Starts deadlines when a member has reasonable grounds to suspect a reportable event. Adds records of operator awareness, earlier affected-party awareness, external reports and timestamp justification.
- **Reporter protections:** Distinguishes voluntary participation from members’ reporting duties, adds protection against retaliation under SAFE’s own rules, and states that confidential learning creates no legal privilege or immunity. Explicitly excludes fraud alongside intentional abuse and criminal conduct from non-punitive treatment.
