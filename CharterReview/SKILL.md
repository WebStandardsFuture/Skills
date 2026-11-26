---
name: "w3c-recharter-review"
description: "Assess a proposed W3C Working Group charter (a recharter, a new group, or a revived one) from the perspective of W3C and the wider web community: progress, real-world impact, timeliness, TAG uptake, licensing, and whether two more years are worth it."
---

# W3C recharter review

Inputs: the proposed (AC review) charter URL, and the current charter URL if there is one.

Most reviews are recharters, but the same method applies to a new group or to one being revived after closing. Section 1 says what to use in place of the recharter history in those cases.

## Perspective
Write the review on behalf of two parties, not any single member organization:

1. **W3C as an institution.** Every chartered group costs W3C money: Team FTE, horizontal review bandwidth, and the AC's and the TAG's attention. It also costs W3C reputation when the group produces perpetual Working Drafts, slips its milestones, or lends W3C's name to work only one vendor ships. Those costs are justified only by deployed solutions to real problems.
2. **The web community.** Developers and users want W3C to focus on important problems and to deliver effective, interoperable solutions in a reasonable time.

The central question: **is two more years of this group a good use of W3C's resources, compared with the alternatives?** Judge proposals by evidence of need and deployment, not by who supports them. Name vendors only as facts (who ships, who doesn't, who drives the work), not as interests to serve.

## Three tests, applied to each deliverable
- **Real problem.** Is there evidence of need from outside the proponents? Look for developer surveys, sites and products that work around the gap, user-facing bug reports, accessibility or privacy benefits, and horizontal groups' assessments. A proponent's explainer alone is not evidence.
- **Deployed solution.** For APIs and formats: is it shipping in at least two independent engines, with usage that reflects real value? Is it tested in WPT? Does a spec that only one engine ships count as a W3C success? For guidelines, vocabularies and other non-API deliverables: is it actually used? That means conformance claims by products, citation in law, regulation or procurement, and use in evaluation tools and audits (see section 4b).
- **Timely.** How long from the first charter promise, or from FPWD, to each stage? How many charters has the deliverable appeared in without advancing? Compare with comparable specs where possible.

## 1. Baseline
- Fetch the current charter, the proposed charter, and **at least two previous charters**. Get the previous ones from w3.org/groups/wg/<short>/charters/. Build a slip table: each deliverable, the date every charter promised for it, and the date it actually reached each stage.
- Get actual publications from w3.org/standards/history/<shortname>/, and recent activity from w3.org/groups/wg/<short>/activity/. Note charter extensions.
- **New or revived groups.** If there is no recent charter to compare with, build the baseline from what is closest:
  - **A predecessor group.** For a group revived after closing, use its old charters and publication history. How late it delivered last time is evidence for how realistic the new dates are.
  - **An incubating Community Group.** Fetch its charter, its reports, and its minutes about the move to a WG. Check how far the work has really got (requirements, drafts, participants beyond the chairs) and whether the CG itself questioned whether a WG is needed yet.
  - **What the first charter buys.** If the only new normative output is a requirements document or an FPWD, say so plainly. Royalty-free patent commitments come only at later stages, so ask what a WG adds over continued CG incubation, and whether a shorter or more tightly scoped charter fits better.
  - **Overlap with existing groups.** Check whether another group's charter (current or also in AC review) claims the same deliverables, such as maintenance or errata of the same spec.

## 2. Progress vs. milestones
For each normative deliverable, report: the promised stage and date, the stage actually reached, and the identifiable cause of any gap. Say when a deliverable is undated and therefore unmeasurable. A charter with no dates is itself a finding.

## 3. Work outside the charter
Look for work the group is doing that its current charter doesn't cover. Sources: TAG review requests naming the WG, minutes, TPAC updates, and implementers' intent-to-ship posts that name a venue. Compare against Scope and Out of Scope. Doing uncovered work weakens W3C's chartering discipline and its patent coverage.

## 4. Real-world adoption and impact
For each spec and each major feature:
- Baseline status and browser support: web-platform-dx.github.io/web-features-explorer/features/<id>, caniuse.
- Usage: the Chrome Platform Status use counter. **Caveat it.** Fingerprinting and feature detection inflate counters, so check fingerprinting research.
- Vendor positions and bugs: the Mozilla and WebKit standards-positions repos, bugs.webkit.org, bugzilla.mozilla.org. Long-open, unassigned bugs are evidence.
- Shipping signals: blink-dev and Mozilla dev-platform intents, and release notes. Note the venue each intent names.
- Tests: wpt.fyi for the spec's directory.
- Ecosystem: dependent products and developer complaints about gaps, such as missing iOS support.

Separate the value already delivered by finished Recommendations from the value plausibly delivered by the next two years of work. Rechartering buys only the second.

## 4b. Adoption of guidelines and other non-API deliverables
Browser metrics don't apply to guidelines (WCAG, ATAG, UAAG), vocabularies, or Notes. Measure deployment instead by:
- **Conformance claims.** Products or vendors that publicly claim conformance, for example in VPATs or accessibility conformance reports. Note whether claims are self-asserted or independently tested.
- **Regulatory and procurement uptake.** Citation in law, regulation, standards or procurement rules, such as Section 508, EN 301 549, the European Accessibility Act, national standards and public-sector procurement. A guideline nobody cites has little leverage.
- **Implementer engagement.** Whether the makers of the target products (CMSs, editors, platforms) participate in the group, comment on drafts or cite it in their documentation.
- **Successor and transition plans.** If a newer deliverable is meant to replace or absorb this one, track its real progress, and whether the old one is kept, superseded or orphaned.
- **Tooling and evaluation.** Test rules, evaluation methods, and audit practice that operationalize the guideline (for example, ACT rules).
- **Age and currency.** How long since the last Recommendation, and whether the technology it addresses has changed enough to make it stale.
Apply the timeliness test the same way: a guideline revision that has been "in progress" for several charters is a finding.

## 5. TAG and horizontal reviews
- Find TAG reviews at tag-github-bot.w3.org/gh/w3ctag/design-reviews/<n>. Search for the spec names, feature names, and the WG or CG name. If the GitHub API is unreachable, use web search plus the bot pages.
- For each review: opening date, main concerns, resolution label and date (or none, or timed out), and what the proponents changed. Verify cross-referenced issue numbers, because requests sometimes cite the wrong issues.
- Find the charter's strategy-funnel issue (github.com/w3c/strategy) and whether the TAG and other horizontal groups reviewed the charter itself.
- Build a table: concern → addressed in the spec? → reflected in the proposed charter (scope, coordination, success criteria, guiding principles)? Concerns about architecture, venue and coordination belong in the charter.

## 6. Proposed charter quality
Check for:
- Placeholder dates and missing milestones.
- Broken or copied links.
- Scope vs. deliverables mismatches. Tentative deliverables must be within Scope.
- Out of Scope items removed silently.
- A coordination list that doesn't cover the new work's implications.
- Staff FTE.
- The Patent Policy version.
- **The document license.** The charter's Licensing section should say the group will use the W3C Software and Document License for all its deliverables. Flag it if it names the W3C Document License instead, or says nothing (documents on W3C's site default to the Document License). The Document License forbids publishing derivative works as technical specifications, so nobody can fork, profile or carry the work to another venue if the group stalls or W3C stops supporting it. Also check that the charter is consistent with itself: a footer or boilerplate can name a different license from the Licensing section.
  - **Compare across every earlier licensing document for this work, not just the current charter.** That means all the charters fetched in section 1 and, when the work is moving from a Community Group, the CG's charter. A license can tighten in one recharter and then carry forward unnoticed, so the current charter may already be the regression. CGs usually require the Software and Document License, so moving work from a CG into a WG under the Document License tightens it. Pre-2015 charters often have no Licensing section; say so rather than treating silence as a baseline. Note any split, such as the Document License for normative deliverables and the Software and Document License for informative ones, and when it changed.
  - **Check the published drafts.** The copyright notice on the group's latest drafts shows which license they actually carry, which can differ from what the charter says.
  - **Name the concrete costs.** The W3C charter template's default is the Software and Document License, so the Document License is a deliberate deviation that needs a stated reason. Then check who the license would actually block:
    - **W3C groups.** A group can't jointly publish with a group that uses a different license. Look for joint task forces, coordination partners and collaborations suggested in horizontal review whose licenses differ, and for evidence (minutes, list posts) that this has already blocked a publication.
    - **External standards bodies.** Look for partners in the coordination list, MOUs or liaisons that intend to adopt, adapt or build on the text, such as national standards bodies or ETSI and CEN. A national standard built on a W3C document is a derivative technical specification, which the Document License forbids unless a separate agreement grants permission. If the charter points to an MOU, find out whether it is signed and public and whether it covers copyright; if it can't be checked, say so and ask for it in the AC comment.
    - **Reuse in general.** The restriction stops others from reusing the work in specifications, even informative material that was never meant to be a single authoritative text.
  - **Anticipate the counterargument.** For normative text that laws or procurement rules cite verbatim, proponents may argue a single authoritative version is worth the restriction. Weigh that per deliverable: check whether the text is actually cited normatively or only informatively, and note that the argument rarely applies to informative notes, techniques or test materials.
  - **What to ask for.** If the proposed charter uses the Document License, ask in the AC comment for the Software and Document License, or at minimum for it on informative deliverables, plus a stated reason why derivative specifications must be prohibited for the rest. Where an external partner will build on the text, ask how the license accommodates that.
- Success criteria the group has already failed to meet.

## 7. Costs, benefits and alternatives
- **Costs to W3C:** Team FTE as stated, horizontal review load, the AC's and the TAG's attention, and reputational risk from repeated slips, single-engine specs, or work that bypasses review. Don't invent dollar figures. W3C doesn't publish per-group costs, so describe magnitudes.
- **What only W3C adds:** royalty-free patent commitments (check which stages create them under the charter's Patent Policy version, and which drafts have passed exclusion), a neutral venue where competing implementers converge, horizontal review, and stable Recommendations. If a community group or WHATWG would serve equally well, say so.
- **Participation health:** the number of active organizations, editors' and contributors' affiliations, single-vendor dominance, and attendance where minutes allow.
- **Options, not just yes or no:**
  - recharter as proposed
  - recharter with changes, such as dated milestones, scope fixes or added coordination
  - narrow the charter: drop or defer deliverables that fail the three tests
  - maintenance-only charter
  - shorter charter with an explicit checkpoint
  - move incubation back to a community group
  - close the group

  For each option, say who would lose what.

## Output
Start with a verdict paragraph from the W3C and web-community perspective: the recommended option and the two or three decisive reasons. Then add sections for sections 2–7 of this skill, with tables for slips, adoption (a three-tests scorecard for each deliverable) and TAG reviews. End with a numbered list of concrete changes to request in the AC comment. Cite every factual claim, and state what couldn't be verified and why. Keep the tone evaluative and evidence-based, not adversarial: the aim is better stewardship, not scoring points against the group.
