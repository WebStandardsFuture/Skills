# Review: Proposed Authoring Tool Accessibility Guidelines Working Group Charter

Charter reviewed: <https://www.w3.org/2026/11/proposed-atag-wg-charter.html>
Review date: 25 November 2026
Method: the `w3c-recharter-review` skill, from the perspective of W3C as an institution and the wider web community.

**This isn't a normal recharter.** It revives a group that closed on 15 December 2015. Its last charter period was 2010–2015. So the comparisons below use the group's old charters and the ATAG Community Group (CG) that has been incubating the work since September 2025.

## Verdict

**Charter it, but with changes.** There is a real problem to solve: accessibility of AI- and automation-driven authoring tools and the content they produce. The planned joint development with Accessibility Standards Canada (ASC) also needs a Working Group, because a Community Group can't enter that kind of partnership. But as proposed, the charter has three problems:

- **It would deliver little in two years.** Its only new normative output is a First Public Working Draft (FPWD) at the end of the charter period.
- **It is thinly staffed.** W3C Team support totals under a tenth of a person (0.09 FTE), and both chairs are Invited Experts.
- **Its license works against its own partnership.** It uses the restrictive W3C Document License. The CG's work is under the permissive W3C Software and Document License, and ASC intends to build a national standard on ATAG. The Document License forbids derivative technical specifications.

## Progress and timeliness

| Deliverable | Promised | Actual |
|---|---|---|
| ATAG 2.0 (2010 charter) | CR Sep 2010; PR Mar 2011; Rec May 2011 | Rec Sep 2015 (FPWD was Mar 2003) |
| Next version of ATAG (proposed) | Use cases and requirements Q3 2027; FPWD Q2 2028 | Draft state: "No draft" |
| ATAG 2.0 and Implementing ATAG 2.0 (proposed) | Editorial revision Q2 2027 | — |

- **ATAG 2.0 was more than four years late.** It took about 12 years from FPWD to Recommendation.
- **The new deliverable has no real completion target.** Its "expected completion" is listed as "Working Draft", which is an early milestone, not a completion state.
- **The proposed timeline:**
  - December 2026: first teleconference
  - Q2 2027: editorial revision of ATAG 2.0 and Implementing ATAG 2.0
  - Q3 2027: use cases and requirements
  - Q2 2028: First Public Working Draft
- **What two years buys.** At best a requirements document and one FPWD. Royalty-free patent commitments come only at later stages, so none of W3C's distinctive patent value arrives this charter period.

## The three tests

| Test | Next version of ATAG | Notes |
|---|---|---|
| Real problem | Yes, plausibly | The new scope covers requirements for AI- and automation-driven authoring tools and their output. Accessibility Standards Canada has started its own national standard, CAN-ASC-6.3 ("ATAG 3.0"), which "will build upon" ATAG 2.0. That is outside evidence of need. |
| Deployed solution | Modest (for ATAG 2.0) | EN 301 549 refers to ATAG 2.0 only informatively, as a resource for those who want to go beyond its requirements. Australia's Human Rights Commission advises organisations creating tools that accept user contributions to conform with ATAG 2.0. I found no public lists of products claiming ATAG conformance. |
| Timely | No | The last revision took 12 years from FPWD to Recommendation. This charter's dates stop at FPWD. |

## Licensing

- **The charter uses the Document License for everything.** Its Licensing section reads: "This Working Group will use the W3C Document license for all its deliverables." The W3C charter template's default is the W3C Software and Document License, so this is a deliberate deviation, and the charter gives no reason for it.
- **It contradicts itself.** The footer cites the "permissive document license" with a link to the software license, while the Licensing section names the Document License.
- **What the Document License prohibits.** It expressly prohibits publishing derivative works of the document for use as a technical specification. Nobody can fork, profile or carry the work to another venue if the group stalls.
- **The old charters don't help as a comparison.** The 2010 charter has no Licensing section at all.
- **Against the incubating CG, it's a regression.** The ATAG CG's charter says: "Specifications created in the Community Group must use the W3C Software and Document License", and other documents should use it where possible. Moving the work from the CG into the WG would tighten its license.
- **It undercuts the ASC partnership.** The charter lists ASC as a partner for joint development under an MOU. ASC's planned CAN-ASC-6.3 will build on ATAG 2.0, which makes it a derivative technical specification. That is exactly what the Document License forbids, unless the MOU grants separate permission. The charter links only to a "proposed" MOU page, so I couldn't check its terms.
- **It blocks joint work with APA.** In its review, the TAG suggested collaborating with the APA Research Questions Task Force. APA uses a different license from the AG WG, and that mismatch already stopped the COGA task force from publishing jointly, because W3C doesn't allow joint publication between groups with different licenses. ATAG would hit the same wall.
- **The counterargument is weak here.** For text that laws cite verbatim, such as WCAG, one can argue a single authoritative version is worth the restriction. EN 301 549 cites ATAG only informatively, so that argument carries much less weight for ATAG.
- **Nobody seems to have raised it.** The TAG's review doesn't mention licensing, and neither do the CG's February 2026 minutes on the charter.

## TAG and horizontal review

| Review | Opened | Concerns | Resolution |
|---|---|---|---|
| [w3ctag/design-reviews#1241](https://tag-github-bot.w3.org/gh/w3ctag/design-reviews/1241) (strategy issue [w3c/strategy#552](https://github.com/w3c/strategy/issues/552)) | 29 June 2026 | The only question was when the work would be done. Matthew noted there was no expected date yet for the first draft of the next ATAG, and suggested working with the APA Research Questions Task Force. | Closed as satisfied on 13 July 2026: a date wasn't needed for architectural considerations. A TAG member later added "We are happy to see this work progress." |

The TAG review did not address licensing, the overlap with the AG WG, the joint development with ASC, or whether the group is viable. Those are governance questions, so the AC needs to raise them.

## Overlap with the AG WG

Two charters in AC review both claim ATAG maintenance:

- **The proposed AG WG charter** says it will "maintain errata for content developed by predecessor groups", naming the Authoring Tool Accessibility Guidelines as an example.
- **This charter** lists ATAG 2.0 as a maintained normative specification.

The CG knew about the clash. In its 13 February 2026 meeting, its chair reported rough consensus with the AG chairs that ATAG should go ahead on its own, and that the group may need to ask the AG WG to remove authoring tools from its errata. The proposed charters haven't resolved it yet.

## Charter quality

- The start and end dates are placeholders ("[dd monthname yyyy]"), and so are the dates in the charter history table.
- The Patent Policy licensing link contains an unfilled placeholder: `https://www.w3.org/groups/wg/%5Bshortname%5D/ipr/`.
- The Motivation section says "The Accessibility Guidelines Working Group will explore these developments", where it means the ATAG WG.
- The change log has a heading but no entries.
- The Media WG, Audio WG and Timed Text WG coordination entries repeat the same sentence.
- The footer's license statement contradicts the Licensing section (see Licensing above).
- The Accessibility Standards Canada MOU link points to a "proposed" page.
- The success criteria are template-standard: two independent implementations per feature, plus testing plans, security, privacy and accessibility sections. They aren't adapted to guidelines, where an "implementation" means a conforming authoring tool.

## Costs, benefits and alternatives

- **Costs to W3C:**
  - Team support is Rémi Bétin (0.08 FTE) and Shawn Lawton Henry (0.01 FTE).
  - Horizontal review and AC attention go to a charter whose main output is a requirements document and an FPWD.
  - There is reputational risk if the last revision's 12-year pace repeats.
- **Participation health:** Both chairs (Miriam Fukushima and Wendy Reid) are W3C Invited Experts, so no Member organization is leading. The charter expects at least 6 active participants. CG attendance in early 2026 was roughly 8–12 people per meeting.
- **What only a WG adds:** the formal joint development with ASC, horizontal review, and eventually royalty-free patent commitments and a stable Recommendation. None of the patent value arrives in this charter period.
- **The CG questioned the timing itself.** In February 2026, one participant asked whether a charter focused on discovery work might be wiser than a full charter now.

| Option | Who loses what |
|---|---|
| Charter as proposed | W3C spends Team time and AC attention for a requirements document and an FPWD; ASC and others can't build on the text under the Document License. |
| **Charter with changes (recommended)** | Proponents must fix the license, clarify the MOU, resolve the AG overlap and set real milestones before starting. |
| Shorter charter with a checkpoint | Proponents carry the cost of a second AC review sooner; the AC gets a decision point after requirements. |
| Keep incubating in the CG for now | The joint development with ASC can't be formalized, and ASC may go ahead with CAN-ASC-6.3 on its own, so the work risks splitting. |
| Don't charter | ATAG 2.0 maintenance falls back to the AG WG; W3C cedes AI authoring-tool guidance to ASC and others. |

## Changes to request in the AC comment

1. **Licensing.** Use the W3C Software and Document License for all deliverables, matching the incubating CG's charter. Confirm the license accommodates ASC's planned CAN-ASC-6.3, and correct the footer's contradictory license statement.
2. **The ASC MOU.** Publish the W3C–ASC MOU, or at least its terms on IPR and copyright, before the charter is approved, and replace the link to the "proposed" page.
3. **Maintenance overlap.** Resolve who maintains ATAG 2.0 and its errata, in both this charter and the AG WG charter.
4. **Milestones.** Replace "Expected completion: Working Draft" with a real target stage and date. If FPWD in Q2 2028 is the honest target, add a 12-month checkpoint report to the AC, or consider a shorter, scoped charter.
5. **Editorial fixes.** Fill in the start and end dates, the history table and the change log; fix the `[shortname]` placeholder link, the wrong group name in Motivation, and the duplicated coordination text.

## What couldn't be verified

- **The W3C–ASC MOU.** The charter links only to a "proposed" page, so I couldn't see whether it is signed or whether it covers copyright and derivative works.
- **ATAG conformance claims.** I found no public lists of authoring tools claiming ATAG 2.0 conformance; there may be some in procurement documents I didn't search.
- **ATAG 2.0's own copyright notice.** I didn't check which license the published Recommendation links to.

## Sources

- [Proposed ATAG WG charter (AC review)](https://www.w3.org/2026/11/proposed-atag-wg-charter.html)
- [ATAG WG charter history](https://www.w3.org/groups/wg/atag/charters/) and [group page (closed 15 December 2015)](https://www.w3.org/groups/wg/atag)
- [2010 ATAG WG charter](https://www.w3.org/WAI/AU/2010/auwg_charter)
- [ATAG Community Group](https://www.w3.org/community/atag/) and [its draft charter](https://raw.githack.com/w3c-cg/atag/charter-draft/ATAG_Charter.html)
- [ATAG CG minutes, 13 February 2026](https://www.w3.org/2026/02/13-atag-minutes.html)
- [TAG review w3ctag/design-reviews#1241](https://tag-github-bot.w3.org/gh/w3ctag/design-reviews/1241)
- [Proposed AG WG charter (June 2026)](https://www.w3.org/2026/06/ag-wg-charter.html)
- [Accessibility Standards Canada: CAN-ASC-6.3 (ATAG 3.0) notice of intent](https://accessible.canada.ca/creating-accessibility-standards/NoticeIntent-can-asc-63-3)
- [W3C Document License (2023)](https://www.w3.org/copyright/document-license-2023/)
- [EN 301 549 criteria including the ATAG 2.0 reference (digitalbarrierefrei.at)](https://www.digitalbarrierefrei.at/de/verstehen/barrierefreiheitskriterien/kriterien-fuer-websites-ab-ende-2026)
- [Australian Human Rights Commission: standards and guidelines on digital accessibility](https://humanrights.gov.au/our-work/disability-rights/chapter-3-standards-and-guidelines-digital-accessibility)
- Evidence that different licenses blocked COGA joint publication: from the AG WG charter review earlier in this session.
