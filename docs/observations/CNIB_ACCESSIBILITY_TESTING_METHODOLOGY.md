# CNIB Accessibility Testing Methodology and Contexts

## Overview

Accessibility testing at CNIB occurs in multiple contexts for different purposes, with varying levels of formality, scope, and expertise depending on the situation. This document outlines the various testing scenarios, methodologies, and levels of rigor applied across CNIB and CNIB AccessLabs.

---

## Testing Contexts: Why CNIB Tests

### 1. Vendor Procurement Testing

**Purpose**: Evaluate accessibility before purchasing new products or platforms

**Context**:
- Organization considering new software, platform, or tool
- Need to determine if product meets accessibility requirements
- Decision-making depends on testing results
- Procurement decisions may be delayed or cancelled based on findings

**Examples**:
- Evaluating expense management systems (like SAP Concur)
- Testing new HR platforms
- Assessing communication tools (email, messaging, video conferencing)
- Evaluating learning management systems

**Typical Testing Level**: Tier 2 (Expert Manual Review) minimum; Tier 3 (User Testing) for mission-critical systems

**Stakeholders**: Procurement, IT, department requesting system, IDEA Team, potential end users

---

### 2. Vendor Update Testing

**Purpose**: Ensure updates to existing platforms maintain or improve accessibility

**Context**:
- Vendor releases update to platform CNIB already uses
- Updates may introduce new accessibility barriers
- Updates may break existing assistive technology compatibility
- Need to verify update is safe to deploy

**Examples**:
- Office 365 updates
- ERP system patches
- CRM updates
- Operating system updates affecting assistive technology

**Typical Testing Level**: Varies by criticality
- Minor updates: Tier 1 (Automated) + spot checking
- Major updates: Tier 2 (Expert Review)
- Updates affecting known accessibility-sensitive features: Tier 3 (User Testing)

**Stakeholders**: IT, system administrators, IDEA Team, users who rely on assistive technology

**Challenge**: Often reactive—vendor pushes update without advance warning, requiring rapid testing

---

### 3. Partnership Due Diligence Testing

**Purpose**: Protect CNIB's reputation by ensuring partner organizations meet accessibility standards

**Context**:
- CNIB considering partnership, collaboration, or public affiliation with another organization
- Partner's accessibility reflects on CNIB
- Testing occurs before public announcement
- May be deal-breaker if significant accessibility barriers found

**Examples**:
- Corporate partnership announcements
- Co-branded initiatives
- Technology partnerships
- Vendor relationships where CNIB endorses or recommends products

**Typical Testing Level**: Tier 2 (Expert Review) minimum for public-facing materials; Tier 3 (User Testing) if partnership involves client-facing services

**Stakeholders**: Partnerships team, Marketing/Communications, IDEA Team, Executive Leadership

**Confidentiality**: Often requires NDA or confidential testing before public announcement

---

### 4. Client Advocacy Testing

**Purpose**: Investigate accessibility barriers affecting CNIB clients in broader ecosystem

**Context**:
- Product, service, app, or website comes to CNIB's attention as having accessibility problems
- CNIB clients (blind and low vision individuals in Canada) report barriers
- Testing documents barriers for advocacy purposes
- May lead to direct advocacy with organization or public awareness campaigns

**Examples**:
- Banking apps with accessibility barriers
- Government services websites
- Retail e-commerce platforms
- Transportation booking systems
- Healthcare portals
- Educational platforms

**Typical Testing Level**: Tier 2-3 (Expert Review + User Testing with clients)
- Document specific barriers encountered by real users
- Gather evidence for advocacy conversations
- Test with multiple assistive technologies
- Document impact on user tasks and independence

**Stakeholders**: Advocacy team, clients who reported barriers, IDEA Team, AccessLabs (if formal testing needed)

**Outcomes**:
- Direct communication with organization about barriers
- Public advocacy if organization unresponsive
- Case studies for systemic advocacy (e.g., banking sector accessibility)
- Training material ("here's what not to do")

---

### 5. CNIB AccessLabs Commercial Testing Services

**Purpose**: Revenue-generating social enterprise providing professional accessibility testing and consulting

**Context**:
- External clients (corporations, governments, non-profits) hire CNIB AccessLabs
- Testing as paid service
- Professional deliverables: formal reports, remediation guidance, WCAG conformance statements
- 100% of revenue reinvested into CNIB charitable programs

**Service Offerings**:
- **Comprehensive digital audits**: Websites, mobile apps, software platforms, documents
- **Built environment assessments**: Physical space accessibility
- **Lived experience testing**: Real users with disabilities test products/services
- **Customer journey mapping**: End-to-end accessibility evaluation
- **WCAG conformance audits**: Formal evaluation against WCAG 2.1 AA or AAA
- **Accessibility consulting**: Strategy, training, roadmap development
- **Accessible design services**: Creating accessible content, templates, systems

**Typical Testing Level**: Full spectrum depending on client needs
- Tier 1 (Automated) as baseline
- Tier 2 (Expert Review) standard for most engagements
- Tier 3 (User Testing) when client requests or for comprehensive audits
- Formal conformance audits use all three tiers

**Deliverables**:
- Professional testing reports
- WCAG violation documentation with severity ratings
- Remediation recommendations with code examples
- Accessibility Conformance Reports (ACRs)
- Executive summaries for leadership
- Training for client teams

**Stakeholders**: AccessLabs team, external clients, CNIB program beneficiaries (through reinvested revenue)

**Quality Standards**: Professional-grade testing following industry best practices, IAAP standards, W3C methodologies

---

### 6. Internal Product Development Testing

**Purpose**: Ensure CNIB-developed products and customizations are accessible

**Context**:
- CNIB develops some of its own software
- CNIB themes/customizes UI of platforms used internally
- CNIB creates digital products for clients (apps, tools, resources)
- Born accessible principle: build accessibility in from start, test throughout development

**Examples**:
- CNIB-developed mobile apps
- Custom SharePoint themes
- Internal tools and utilities
- Client-facing digital resources
- Branded interfaces for third-party platforms

**Typical Testing Level**: Integrated throughout development lifecycle
- **Design phase**: Design reviews for accessibility
- **Development**: Tier 1 (Automated) in CI/CD pipeline
- **QA**: Tier 2 (Expert Review) before release
- **Pre-launch**: Tier 3 (User Testing) with staff/volunteers
- **Post-launch**: Ongoing monitoring and user feedback

**Best Practice**: Shift-left testing—test early and often, not just at end

**Stakeholders**: Development team, product managers, IDEA Team, QA, end users (staff or clients)

---

### 7. Vendor Documentation and Training Material Testing

**Purpose**: Ensure vendor-provided documentation and training materials are accessible to CNIB staff and clients

**Context**:
- Vendors provide user guides, help documentation, training videos, tutorials
- If documentation inaccessible, CNIB staff/clients can't learn to use product
- Documentation accessibility equally important as product accessibility

**Examples**:
- Software user manuals
- Training videos (captioning, audio description)
- Quick start guides
- Help system content
- Webinar materials
- Certification courses

**Typical Testing Level**: Varies by importance
- **Critical training materials**: Tier 2 (Expert Review)
- **Reference documentation**: Tier 1 (Automated) + spot checking
- **Video content**: Manual review for captions, transcripts, audio description

**Common Issues**:
- PDFs without accessible structure
- Videos without captions or transcripts
- Help systems with poor keyboard navigation
- Searchable documentation that doesn't work with screen readers
- Training platforms that aren't accessible

**Stakeholders**: Training team, IDEA Team, end users who need to learn the system

---

### 8. CNIB Internal Documentation and Training Material Testing

**Purpose**: Ensure CNIB's own documentation and training materials are accessible to diverse staff and volunteers

**Context**:
- CNIB creates extensive internal documentation (policies, procedures, training, communications)
- Staff have diverse accessibility needs (not all vision-related)
- Volunteers need accessible materials
- "Practice what we preach"—if CNIB can't create accessible documents, credibility suffers

**Examples**:
- Policy documents
- Employee handbooks
- Training modules (Impact Training, onboarding, professional development)
- Internal communications (newsletters, announcements, memos)
- Forms and templates
- Presentation materials
- Reports and data visualizations

**Typical Testing Level**:
- **High-visibility materials** (Impact Training, employee handbook): Tier 2 (Expert Review)
- **Routine communications**: Tier 1 (Automated) + Clear Print guidelines
- **Templates**: Tier 2 (Expert Review) once, then used organization-wide
- **Training videos**: Manual review for captions, transcripts

**Quality Standards**: Clear Print guidelines, CNIB's own accessibility standards, WCAG 2.1 AA

**Challenge**: Volume—CNIB creates hundreds of documents monthly; can't formally test everything

**Stakeholders**: Document creators (Communications, HR, Training, all departments), IDEA Team, Accessibility Hub

---

## Testing Levels: Spectrum of Rigor

CNIB employs a spectrum of testing methodologies ranging from informal/rapid to formal/comprehensive. Testing level selected depends on:
- **Purpose**: Procurement decision vs. routine document review
- **Risk**: Mission-critical system vs. nice-to-have feature
- **Audience**: All staff vs. small team
- **Resources**: Time, budget, tester availability
- **Stakes**: Public partnership vs. internal process

---

### Level 0: Basic Informal Inspection

**Description**: Internal staff briefly inspect content with their assistive technology

**Who**: Any staff member using assistive technology (screen reader, magnification, voice control)

**Process**:
1. Staff member opens document/page/app
2. Tries to complete relevant task
3. Notes if anything doesn't work or is confusing
4. Reports to creator or Accessibility Hub (informal)

**Tools**: Staff member's own assistive technology (JAWS, NVDA, ZoomText, VoiceOver, etc.)

**Time**: 5-15 minutes

**Output**: Informal feedback ("this PDF doesn't work with my screen reader")

**Appropriate For**:
- Quick sanity check
- Routine documents
- Internal drafts
- Early feedback before formal testing

**Limitations**:
- Not comprehensive
- Depends on individual's expertise
- May miss issues that affect other disabilities
- No formal documentation
- Not replicable or auditable

**Value**: Fast, free, real-world perspective from actual AT users

---

### Level 1: Structured Informal Testing

**Description**: More systematic approach with specific tasks and multiple testers

**Who**: Multiple staff members using different assistive technologies

**Process**:
1. Define 3-5 key tasks to test (e.g., "fill out form," "find contact info," "watch video")
2. Multiple staff test with different AT (screen reader, magnification, keyboard-only)
3. Document what works and what doesn't using simple template
4. Consolidate findings
5. Report to stakeholders

**Tools**:
- Staff members' own assistive technology
- Simple testing checklist
- Basic documentation template

**Time**: 30-60 minutes per tester

**Output**: Informal report listing barriers found, severity assessment

**Appropriate For**:
- Internal documents and platforms
- Moderate-importance materials
- Pre-testing before formal testing
- Rapid feedback cycles

**Limitations**:
- Not comprehensive WCAG audit
- Informal documentation
- May miss technical issues not apparent to users
- Limited reproducibility

**Value**: More thorough than Level 0, still relatively quick, captures diverse AT perspectives

---

### Level 2: Formalized Structured Testing

**Description**: Systematic testing with expertise, following structured methodology

**Who**: Accessibility specialists (IDEA Team, AccessLabs team, IAAP-certified professionals)

**Process**:
1. Test plan created with scope, tasks, success criteria
2. Automated testing (Tier 1) first pass
3. Manual expert review (Tier 2):
   - Keyboard-only navigation
   - Screen reader testing (JAWS, NVDA, VoiceOver)
   - Screen magnification testing
   - Color contrast verification
   - WCAG 2.1 checklist
   - Mobile responsiveness
4. Document findings using standardized report template
5. Severity ratings applied (Critical, High, Medium, Low)
6. Remediation recommendations provided
7. Formal report delivered

**Tools**:
- Automated testing tools (axe, WAVE, Lighthouse)
- Multiple screen readers
- Screen magnification software
- Color contrast analyzers
- WCAG 2.1 checklist
- Standardized reporting templates

**Time**: 4-8 hours depending on complexity

**Output**: Formal accessibility testing report
- Executive summary
- Methodology
- Findings with WCAG violations
- Severity ratings
- Screenshots/screen recordings
- Remediation recommendations
- Priority roadmap

**Appropriate For**:
- Vendor procurement decisions
- Partnership due diligence
- Internal mission-critical systems
- Moderate-stakes AccessLabs engagements

**Limitations**:
- Expert perspective, not necessarily end-user perspective
- May miss subtle usability issues that don't violate WCAG
- Resource-intensive

**Value**: Professional-grade, credible, actionable, defensible

---

### Level 3: Lived Experience Accessibility Testing

**Description**: Real users with disabilities test products/services in realistic scenarios

**Who**: CNIB staff, volunteers, or clients who use assistive technology daily (expert users, not just experts in testing)

**Process**:
1. Recruit participants with diverse disabilities and AT usage
2. Create realistic task scenarios (not abstract WCAG testing)
3. Think-aloud protocol: users narrate experience as they work
4. Observe and document:
   - Task completion rates (can they do it?)
   - Time to complete (efficiency)
   - Errors and frustrations
   - Workarounds employed
   - Satisfaction ratings
   - Quotes capturing experience
5. Severity ratings from user perspective (not just WCAG)
6. Consolidate findings across participants
7. Report includes both technical issues and user experience insights

**Tools**:
- Participants' own assistive technology
- Screen recording software
- Note-taking and observation forms
- Post-test questionnaires

**Time**: 1-2 hours per participant; 3-5 participants typical

**Output**: User testing report
- Participant demographics (AT used, experience level, tasks attempted)
- Task completion results
- Key findings and pain points
- User quotes
- Recommendations prioritized by user impact
- Video clips if applicable (with consent)

**Appropriate For**:
- High-stakes procurement decisions
- Client-facing products/services
- AccessLabs comprehensive engagements
- Client advocacy testing
- Validating that "WCAG compliant" actually means "usable"

**Compensation**: Participants must be compensated (hourly rate, gift cards, professional development funds)—this is expertise, not volunteer work

**Limitations**:
- More expensive and time-consuming
- Requires participant recruitment and coordination
- Small sample size (3-5 participants can't represent all disabilities)
- Qualitative insights supplement but don't replace technical testing

**Value**:
- Real-world validation
- Uncovers usability issues WCAG testing misses
- Authentic user voice and perspective
- "Nothing About Us Without Us" principle in action

---

### Level 4: Formal Conformance Audit

**Description**: Comprehensive, professional audit for WCAG 2.1 conformance statement, combining all testing approaches

**Who**: AccessLabs team (for external clients) or equivalent professional accessibility auditors

**Process**:
1. **Scoping**: Define what's being tested (full site, specific workflows, representative sample)
2. **Automated Testing** (Tier 1): Baseline scan of all pages/screens
3. **Manual Expert Review** (Tier 2): Comprehensive WCAG 2.1 evaluation
   - All WCAG success criteria tested
   - Multiple assistive technologies
   - Code-level inspection
   - Multiple devices and browsers
4. **Lived Experience Testing** (Tier 3): Real users validate findings
5. **Documentation**:
   - Accessibility Conformance Report (ACR) / VPAT
   - Detailed findings report
   - Remediation roadmap
   - Executive summary
   - Evidence package (screenshots, code samples, videos)
6. **Quality Review**: Second auditor reviews findings
7. **Client presentation**: Walkthrough of findings and recommendations

**Tools**: Full professional toolkit
- Multiple automated testing tools (cross-validation)
- All major screen readers (JAWS, NVDA, VoiceOver, TalkBack, Narrator)
- Screen magnification (ZoomText, OS-native)
- Voice control (Dragon, Voice Control)
- Browser developer tools
- Color contrast analyzers
- Code inspection tools
- Screen recording and annotation software

**Time**: 40-80+ hours depending on scope

**Output**: Professional audit package
- Accessibility Conformance Report (ACR) with WCAG conformance level
- Comprehensive findings report (100+ pages typical for large sites)
- Remediation roadmap with priorities
- Executive summary
- Remediation code examples
- Training for client team
- Follow-up support

**Appropriate For**:
- AccessLabs commercial engagements where client needs conformance statement
- Legal compliance requirements
- High-profile partnerships
- Mission-critical systems with large user base
- Organizations seeking WCAG certification

**Deliverable Standards**:
- Meets industry standards for professional audits
- Defensible for legal purposes
- Sufficient for procurement requirements
- Actionable for development teams

**Cost**: Significant (requires 2-3 accessibility specialists, multiple weeks)

**Value**: Gold standard—comprehensive, professional, legally defensible, actionable

---

## Testing Tier Summary Table

| Level | Name | Who | Time | Cost | Appropriate For | Output |
|-------|------|-----|------|------|-----------------|--------|
| **0** | Basic Informal | Any AT user | 5-15 min | Free | Quick checks, drafts | Verbal feedback |
| **1** | Structured Informal | Multiple AT users | 30-60 min | Low | Internal docs, rapid feedback | Simple report |
| **2** | Formalized Structured | Accessibility specialists | 4-8 hours | Medium | Procurement, partnerships, moderate stakes | Professional report |
| **3** | Lived Experience | Real users with disabilities | 1-2 hrs × 3-5 people | Medium-High | High-stakes, client-facing | User testing report |
| **4** | Formal Conformance | Professional auditors | 40-80+ hours | High | Legal compliance, WCAG certification | ACR/VPAT + comprehensive audit |

---

## Decision Framework: Which Testing Level When?

### Questions to Guide Decision

**1. What are the stakes?**
- Low (internal draft): Level 0-1
- Medium (vendor procurement, partnership): Level 2-3
- High (legal compliance, large user base, mission-critical): Level 3-4

**2. Who is the audience?**
- Small team, internal use: Level 0-1
- Department-wide, moderate visibility: Level 1-2
- Organization-wide, external partners: Level 2-3
- Public-facing, large user base: Level 3-4

**3. What resources are available?**
- Minimal time/budget: Level 0-1
- Moderate resources: Level 2
- Substantial resources: Level 3-4

**4. What's the purpose?**
- Quick feedback: Level 0-1
- Go/no-go decision: Level 2-3
- Legal defensibility: Level 4
- User validation: Level 3

**5. Is this reversible?**
- Easy to change/fix: Lower level okay
- Locked in (contract, partnership): Higher level needed
- Reputation on line: Higher level needed

---

## Testing Workflow: Integration Across Organization

### Entry Points for Testing Requests

**Accessibility Hub** serves as central intake for testing requests (per Recommendations):
1. Staff submit testing request via form
2. Hub triages based on:
   - Purpose (procurement, partnership, advocacy, internal development, client service)
   - Urgency (blocking decision, upcoming launch, periodic review)
   - Scope (full platform, specific feature, document, etc.)
3. Hub assigns appropriate testing level
4. Hub coordinates testers and schedules
5. Hub delivers results and tracks follow-up

### Who Does What Testing

**Level 0-1 (Informal)**:
- Any staff with AT
- Accessibility Champions
- Department teams
- Coordinated by: Accessibility Hub or department

**Level 2 (Formalized Structured)**:
- IDEA Team members
- IT accessibility specialists
- AccessLabs team (internal work)
- Trained accessibility champions (advanced)
- Coordinated by: Accessibility Hub

**Level 3 (Lived Experience)**:
- CNIB staff/volunteers who use AT
- CNIB clients (for client-facing testing)
- AT user community of practice
- Compensated for time and expertise
- Coordinated by: Accessibility Hub or AccessLabs

**Level 4 (Formal Conformance)**:
- AccessLabs team exclusively (professional service)
- IAAP-certified auditors
- May include IDEA Team for internal context
- Coordinated by: AccessLabs project managers

---

## Integration with Born Accessible Principles

### Prevention Over Remediation

Testing throughout lifecycle prevents expensive post-launch remediation:
- **Design phase**: Level 0-1 testing of mockups, prototypes
- **Development**: Level 1-2 automated testing in CI/CD, manual spot checks
- **Pre-launch**: Level 2-3 comprehensive testing before release
- **Post-launch**: Ongoing monitoring and user feedback

### Vendor Accountability

Testing is key mechanism for vendor accountability:
- **Pre-purchase**: Level 2 testing validates vendor VPAT claims
- **Contract requirement**: Vendor must pass Level 2 testing
- **Update testing**: Level 1-2 testing before deploying vendor updates
- **Issue tracking**: Document vendor responsiveness to accessibility bugs

### Lived Experience Leadership

CNIB's testing methodology embodies "Nothing About Us Without Us":
- AT users do Level 0-1 testing (democratized, not just experts)
- Level 3 explicitly centers real users with disabilities
- Testing as paid work, not unpaid labor (respects expertise)
- Testers influence tools they use daily

### Continuous Improvement

Testing feeds organizational learning:
- Barrier reports identify systemic issues
- Testing trends inform procurement policies
- Vendor responsiveness tracked over time
- Internal testing identifies training gaps

---

## Challenges and Opportunities

### Current Challenges

**Challenge 1: Volume vs. Capacity**
- CNIB creates hundreds of documents, uses dozens of platforms
- Can't formally test everything
- Need to prioritize strategically
- Risk: important things fall through cracks

**Opportunity**:
- Democratize Level 0-1 testing (train more staff to do basic testing)
- Use automated testing (Level 1) more extensively
- Reserve Level 2-4 for highest priorities

**Challenge 2: Vendor Unresponsiveness**
- Testing identifies barriers (e.g., SAP Concur)
- Vendor slow or unwilling to fix
- CNIB stuck with inaccessible product
- Limited leverage with large vendors

**Opportunity**:
- Test before purchase (don't get stuck)
- Include remediation timelines in contracts
- Collective advocacy with other organizations
- Public accountability (name vendors in advocacy)

**Challenge 3: Informal Testing Lacks Documentation**
- Level 0-1 testing provides valuable feedback
- Often communicated verbally or via quick email
- Hard to track patterns or systemic issues
- Can't prove "we tested this" if challenged

**Opportunity**:
- Accessibility Hub as central logging system
- Even informal testing gets ticket number
- Simple templates make documentation faster
- Trends become visible over time

**Challenge 4: Tester Burnout**
- Relying on small group of staff with AT for all testing
- Unpaid emotional labor
- Same people asked repeatedly
- Risk of burnout and turnover

**Opportunity**:
- Formalize and compensate testers (Level 3)
- Distribute Level 0-1 testing more widely
- Rotate tester requests
- Recognize and appreciate testers publicly

**Challenge 5: Testing Without Remediation**
- Testing identifies barriers
- No accountability for fixing them
- Testing becomes exercise in documentation, not improvement
- Testers become discouraged

**Opportunity**:
- Link testing to accountability (barrier reporting system)
- Track remediation rates, not just testing rates
- Celebrate barriers fixed
- Show impact: "Your testing led to this improvement"

---

## Future State: Mature Testing Ecosystem

In fully realized born accessible CNIB:

**1. Testing Throughout Lifecycle**
- Every new platform/product/document tested before deployment
- Regular testing cycles (not just one-time)
- Continuous automated monitoring
- User feedback loops

**2. Clear Pathways**
- Staff know how to request testing (Accessibility Hub)
- Transparent prioritization
- Predictable timelines
- Results accessible to requestors

**3. Distributed Capability**
- Many staff can do Level 0-1 testing
- Accessibility Champions trained for Level 2
- AT user community formalized for Level 3
- AccessLabs professional capacity for Level 4

**4. Accountability Integration**
- Testing results link to barrier reporting system
- Ownership assigned for remediation
- Progress tracked and visible
- Metrics reported (testing done, barriers found, barriers fixed)

**5. Vendor Accountability**
- All vendor contracts require Level 2 testing
- Pre-purchase testing standard practice
- Update testing before deployment
- Vendor communications tracked
- Vendor responsiveness measured

**6. Resource Sustainability**
- Testing resourced as infrastructure, not project
- Testers compensated for expertise
- Tools and training provided
- Career pathways for accessibility specialists

---

## Conclusion: Testing as Born Accessible Practice

CNIB's multi-level testing approach demonstrates born accessible maturity:

**Prevention**: Testing before problems arise (vendor procurement, internal development)

**Proportionality**: Right level of rigor for the stakes (informal for low-risk, formal for high-risk)

**Lived Experience**: Real users with disabilities central to testing, not afterthought

**Systematization**: Moving from ad hoc to systematic testing processes

**Accountability**: Testing linked to remediation, not just documentation

**Continuous**: Testing throughout lifecycle, not one-time

**Resourced**: Recognition that quality testing requires investment

The journey from current state (ad hoc, inconsistent, under-resourced) to future state (systematic, integrated, sustainable) exemplifies the born accessible principle: **accessibility requires continuous vigilance, systematic processes, and organizational commitment**, not just good intentions.

---

*Document created: November 2025*
*Based on: CNIB staff expertise, AccessLabs professional practice, Task Force discussions, Born Accessible framework*
