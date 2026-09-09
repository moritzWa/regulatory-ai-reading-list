# Regulatory AI Reading List

a curated map of the regulatory + quality world in life sciences, and what AI is doing to it - FDA data sources, the companies building here, and the people worth reading.

maintained by the team at [Arca](https://www.arca.inc) (we build an agentic platform for regulatory & quality teams, so yes, we're biased - competitors are listed anyway). suggestions welcome via issues or PRs.

## free regulatory search tools (ours)

free, no signup. we built these because the FDA's own search interfaces are painful.

| tool | what it does | link |
| --- | --- | --- |
| FDA warning letter search | full-text search across FDA warning letters | https://www.arca.inc/tools/warning-letter-search |
| FDA recall search | search FDA recall records | https://www.arca.inc/tools/recall-search |
| CRL search | search complete response letters | https://www.arca.inc/tools/crl-search |
| 510(k) search | search FDA 510(k) premarket notifications | https://www.arca.inc/tools/510k-search |
| FDA inspection search | search FDA inspection records | https://www.arca.inc/tools/inspection-search |
| UDI lookup | look up unique device identifiers | https://www.arca.inc/tools/udi-lookup |

## primary sources & FDA guidance

- FDA - [artificial intelligence & medical products](https://www.fda.gov/science-research/science-and-research-special-topics/artificial-intelligence-and-medical-products) - the hub page for everything FDA does on AI
- FDA - [AI-enabled device software functions: lifecycle management (draft guidance)](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/artificial-intelligence-enabled-device-software-functions-lifecycle-management-and-marketing) - still a draft, and it matters
- FDA - [predetermined change control plans for AI/ML devices](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/marketing-submission-recommendations-predetermined-change-control-plan-artificial) - how you ship model updates without resubmitting
- FDA/Health Canada/MHRA - [good machine learning practice: guiding principles](https://www.fda.gov/medical-devices/software-medical-device-samd/good-machine-learning-practice-medical-device-development-guiding-principles) - the closest thing to GMP-for-ML consensus
- FDA - [data dashboard](https://datadashboard.fda.gov/) - inspections, warning letters, recalls, straight from the source
- openFDA - [device 510(k)](https://open.fda.gov/apis/device/510k/) and [device recall](https://open.fda.gov/apis/device/recall/) endpoints - raw API access to the same data
- IMDRF - [ML-enabled medical devices: key terms and definitions](https://www.imdrf.org/documents/machine-learning-enabled-medical-devices-key-terms-and-definitions) - international vocabulary baseline

## companies building here

the eQMS/regulatory landscape as it actually stands. listed alphabetically-ish, us included.

- [Arca](https://www.arca.inc) - us. agentic AI for regulatory & quality workflows; connects submissions, quality records, and scientific data so agents can do the tedious parts
- [Dot Compliance](https://www.dotcompliance.co) - salesforce-native eQMS, pre-configured for life sciences
- [EtQ Reliance](https://www.etq.com) - enterprise QMS, big in manufacturing-heavy industries
- [Greenlight Guru](https://www.greenlight.guru) - QMS built specifically for medical device companies; strong on design controls
- [Ketryx](https://www.ketryx.com) - regulated AI/SDLC overlay for medtech software teams
- [MasterControl](https://www.mastercontrol.com) - the incumbent eQMS. documents, training, quality events; everyone in the industry has an opinion about it
- [MedFlux](https://www.medflux.live) - real-time regulatory intelligence terminal tracking 27 regulators; free recall lookup and 510(k) predicate finder
- [Qualio](https://www.qualio.com) - web-based QMS aimed at small-to-mid life sciences companies
- [RegDesk](https://www.regdesk.co) - regulatory intelligence and registration tracking for device teams
- [Rimsys](https://www.rimsys.io) - regulatory information management; registrations, standards, submissions
- [Scilife](https://www.scilife.io) - modular eQMS out of Belgium, popular with EU startups
- [Sparta TrackWise](https://www.spartasystems.com) - the legacy enterprise QMS standard at big pharma
- [Veeva Vault Quality](https://www.veeva.com/products/vault-quality/) - the 800-pound platform; QMS, docs, and regulatory on one cloud

## people worth reading

### substacks & newsletters

- [Medical Device Regulatory Briefing](https://leanraqa.substack.com/) (leanRAQA) - sharp weekly reads on what FDA is actually doing; start with [inside FDA's strange new operating environment](https://leanraqa.substack.com/p/inside-fdas-strange-new-operating)
- [Steve Ilverman](https://steveilverman.substack.com/) - writes about FDA and AI specifically; [FDA's AI device guidance is stuck in draft](https://steveilverman.substack.com/p/fdas-ai-device-guidance-is-stuck) and [FDA is using AI to review your devices](https://steveilverman.substack.com/p/fda-is-using-ai-to-review-your-devices) are both worth your time
- [MedDev Insider](https://meddevinsider.substack.com/) (Akash Das) - med-device industry coverage, including how AI is reshaping RA roles
- [The FDA Investigator's Lens](https://devaughnedwards.substack.com/) (DeVaughn Edwards) - written by people who wrote the 483s; what investigators actually look for

### vc theses on the space

- a16z - [AI at the intersection: the a16z investment thesis on AI in bio + health](https://a16z.com/ai-at-the-intersection-the-a16z-investment-thesis-on-ai-in-bio-health/) - the broad map of where AI meets life sciences
- 53 Stations - [building the backbone of regulated AI for life sciences](https://www.53stations.com/blog/building-the-backbone-of-regulated-ai-for-life-sciences-53-stations-invests-in-ketryx) - why regulated industries need different AI infrastructure
- Innovation Endeavors - [our investment in Weave Bio: using AI to alleviate regulatory friction in drug development](https://www.innovationendeavors.com/insights/our-investment-in-weave-bio-using-ai-to-alleviate-regulatory-friction-in-drug-development) - the regulatory-friction thesis, well argued
- Magnetic Ventures - [deploying generative AI to streamline the regulatory process](https://www.magneticvc.com/blog/posts/our-recent-investment-in-weave-bio-deploying-generative-ai-to-accelerate-the-delivery-of-new-therapies-to-patients-by-streamlining-the-regulatory-process/) - another take on the same thesis

### analysis from us (disclosure: arca blog)

- [FDA's first AI warning letter: the model wasn't the problem](https://www.arca.inc/blog/fda-first-ai-warning-letter) - what the first AI-related warning letter actually flagged (data integrity and process controls, not the model)

## standards & frameworks

- ISO 13485 - quality management systems for medical devices
- ISO 14971 - risk management for medical devices
- IEC 62304 - medical device software life-cycle processes
- 21 CFR part 11 - electronic records and signatures
- 21 CFR part 820 / QMSR - quality system regulation (transitioning to QMSR, effective feb 2026)

## contributing

know something that belongs here? open an issue or a PR. primary sources first, disclose affiliations.
