# CNIB Accessibility Testing Methodology and Contexts

## Overview

Accessibility testing at CNIB occurs in multiple contexts for different purposes, with varying levels of formality, scope, and expertise depending on the situation. This document outlines the various testing scenarios, methodologies, and levels of rigor applied across CNIB and CNIB AccessLabs.

**Important Note**: This document represents evolving understanding. Testing practices at CNIB are more structured than initially documented, with most formal testing (all except informal staff testing) falling under AccessLabs for design and execution.

---

## CNIB Testing Structure: Five Primary Approaches

CNIB employs five distinct testing approaches, differing in formality, methodology, and organizational ownership:

### 1. Informal Siloed Testing by Staff (Distributed, Not AccessLabs)

**Description**: Individual CNIB staff members test content or platforms using their own assistive technology, often in response to immediate needs

**Characteristics**:
- Conducted by any staff member, not coordinated centrally
- Often siloed (findings may not be shared beyond immediate context)
- No standardized methodology or reporting
- Quick and responsive but inconsistent
- Documented in Task Force feedback as problematic pattern

**Examples**:
- Staff member opens PDF, notices it doesn't work with screen reader, reports to document creator
- Team member tests internal form with keyboard navigation, finds issues
- Manager reviews PowerPoint with magnification, provides feedback

**Organizational Ownership**: Distributed (not AccessLabs)

**Challenge**: Identified by Task Force as gap—lack of consistency, documentation, and systemic learning

---

### 2. Smoke Testing (AccessLabs-Designed and Executed)

**Description**: Quick, focused testing to verify basic functionality and catch major accessibility issues before deeper testing

**Context**:
- **Internally developed products**: CNIB-created software, themes, customizations
- **External third-party apps and websites**: Vendor products, platforms, partner sites

**Methodology**:
- Rapid pass-through key user workflows
- Check critical accessibility features (keyboard navigation, screen reader basics, color contrast)
- Automated testing tools for quick scan
- Not comprehensive—designed to catch "deal-breakers" quickly
- Typically 1-2 hours

**Who Tests**:
- Generally lived experience based testing (staff with disabilities using their own AT)
- Sometimes sighted or partially sighted staff testing with screen readers that are not part of their normal lived experience
- May use professional AccessLabs staff for technical assessment
- Mixed approach: authentic lived experience + technical expertise

**Purpose**:
- Determine if product warrants deeper testing
- Catch major issues early in procurement/development
- Quick go/no-go assessment
- Triage to appropriate testing level

**Organizational Ownership**: AccessLabs (design and execution)

**Typical Output**: Brief report or verbal feedback—"proceed with deeper testing" or "major barriers, do not proceed"

---

### 3. Lived Experience Accessibility Testing (AccessLabs-Designed and Executed)

CNIB employs two models of lived experience testing, both designed and executed by AccessLabs.

**AccessLabs Evidential Testing Methodology**:

AccessLabs operates on the principle of **evidential testing**: everything tested is recorded on video, usually as screen recordings. This methodology provides:

**Process**:
1. **Record**: Testers record screen activity while testing with assistive technology
2. **Think-aloud protocol**: Testers narrate experience as they interact ("I'm trying to click this button, but my screen reader isn't announcing it")
3. **Analyze**: AccessLabs staff review recordings for usability and accessibility concerns
4. **Report**: Structured feedback provided to clients through AccessLabs online portal
5. **Evidence package**: Video recordings, screenshots, code samples available for developers

**Benefits of Evidential Testing**:
- **Concrete evidence**: Not just "this doesn't work" but video showing exactly what happens
- **Developer understanding**: Developers see and hear tester experience firsthand
- **Reproducibility**: Video documentation enables developers to recreate issue
- **Training value**: Recordings educate developers about how AT users interact with systems
- **Accountability**: Evidence creates shared understanding of severity and impact
- **Historical record**: Testing iterations documented over time

**Application Across Testing Types**:
- **External paid testing**: Comprehensive video documentation standard practice
- **Internal CNIB testing**: Applied as far as practicable (same principle, sometimes limited by timeline/scope)
- **Developer Assistance Package**: Portal provides developers login access to video recordings, screen recordings, evidence packages

**Where AccessLabs Misses the Mark: Document Accessibility**:

One area where evidential testing methodology is **not consistently applied**: **document accessibility testing**.

**The Gap**:
- **Web/app testing**: Fully recorded with think-aloud protocol, analyzed, evidence provided
- **Document testing**: Often less rigorous, may lack video evidence, think-aloud not always captured
- Documents (PDFs, Word, PowerPoint, Excel): Should receive same evidential rigor as web/app testing
- Testers should think aloud as they interact with electronic documents through assistive technology
- Screen recordings should capture:
  - Navigation through document structure (headings, lists, tables)
  - Reading order issues
  - Alt text availability and quality
  - Form field accessibility
  - Table navigation with screen readers
  - Link purpose and context
  - Color contrast and visual readability

**Why Document Accessibility Matters**:
- **Volume**: CNIB creates hundreds of documents monthly (policies, training, communications, forms, reports)
- **Staff impact**: Inaccessible documents create daily barriers for staff with disabilities
- **Client impact**: CNIB provides resources and services via documents to clients with disabilities
- **Legal requirements**: AODA applies to documents, not just websites
- **Organizational credibility**: "Practice what we preach"—CNIB should model accessible document creation

**Current Document Testing Practice**:
- **Ad hoc**: Document testing often informal, not systematically recorded
- **Limited expertise**: Not all staff know how to test documents accessibly
- **No remediation process**: When barriers found, unclear who fixes them or how
- **Inconsistent standards**: Lack of organizational templates and guidelines
- **Training gap**: Document creators not trained in accessible document creation

**Task Force Hope: Document Accessibility Testing and Remediation Processes**

One of Bob Dodd's primary hopes for Accessibility Task Force: **Address document accessibility testing and remediation processes comprehensively.**

**What This Means**:
1. **Extend evidential testing to documents**: Same rigor as web/app testing
   - Video screen recordings of document testing
   - Think-aloud protocol captured
   - Structured feedback through AccessLabs portal or Accessibility Hub
   - Evidence package for document creators

2. **Document testing protocol**: Standardized methodology
   - Checklist for document accessibility (headings, alt text, reading order, tables, forms, contrast)
   - Testing with multiple assistive technologies (screen readers, magnification, voice control)
   - Testing document types (PDF, Word, PowerPoint, Excel, etc.)

3. **Remediation process**: Clear workflow for fixing barriers
   - Who fixes documents? (Creator, centralized team, AccessLabs?)
   - Timeline for remediation based on priority
   - Retesting after fixes
   - Quality assurance before publication

4. **Preventive approach**: Accessible document creation from start
   - **Templates**: Organization-wide accessible templates (Word, PowerPoint, Excel, InDesign)
   - **Training**: Document creator training on accessible document creation
   - **Tools**: Accessibility checkers integrated into creation workflow (Office Accessibility Checker, Adobe Acrobat Pro)
   - **Guidelines**: Clear Print guidelines, CNIB document standards, WCAG 2.1 AA for documents

5. **Accountability**: Ownership and tracking
   - Document accessibility requirements in job descriptions
   - Accessibility Hub tracks document testing requests
   - Metrics on document testing volume, pass rates, remediation time
   - Quality assurance: sample documents tested before organization-wide rollout

**S2 Recommendation: Document Accessibility Framework**:
- **Testing**: Extend evidential testing methodology to documents
- **Remediation**: Clear process and ownership for fixing inaccessible documents
- **Prevention**: Templates, training, tools, guidelines to create accessible documents from start
- **Accountability**: Tracking, metrics, quality assurance

**Born Accessible Principle for Documents**:
- Documents born accessible > retrofitting inaccessible documents
- Accessible templates + trained creators = prevention
- Evidential testing = accountability and learning
- Systematic remediation = continuous improvement

---

#### Critical Differences: Internal vs. External Testing Practices

Before detailing the two models of lived experience testing, it's essential to understand **how internal testing differs from external paid testing** in practice at CNIB. These differences significantly impact testing quality, breadth, and representativeness.

**1. Scope of Testing: Features Tested**

**Internal Testing (Approach #3a)**:
- **Tests only features CNIB expects to use** within the organization
- Not comprehensive testing of all vendor features
- Focused on specific workflows relevant to CNIB staff needs
- Example: ADP Recruitment Module tested only for HR staff workflows, not all recruitment features

**External Paid Testing (Approach #3b)**:
- **Tests broader feature set**, especially for client-facing products
- Comprehensive coverage of user-facing functionality
- Not limited to what CNIB staff will use
- Example: Client portal tested for all public-facing features, not just internal admin view

**Why This Matters**:
- Internal testing gives "will this work for us?" answer
- External testing gives "is this accessible for diverse users?" answer
- Procurement decisions based on internal testing may miss barriers for broader user base

**2. Resource Allocation: Number of Testers and Time**

**Internal Testing (Approach #3a)**:
- **Fewer testers** due to cost constraints (points budget)
- **Less time per test** due to timing pressures (unreasonable short timescales)
- Typical: 1-3 testers, 1-2 hours each
- "Bare minimum" approach driven by budget and timeline

**External Paid Testing (Approach #3b)**:
- **More testers** for diverse representation
- **More time per test** for comprehensive evaluation
- Typical: 3-5+ testers, longer test sessions
- Investment matches stakes (client-facing, revenue-generating products)

**Why This Matters**:
- Fewer testers = less diversity of experience captured
- Less time = less depth, may miss issues that emerge with extended use
- Resource constraints on internal testing limit quality and breadth

**3. Tester Pool: Freshness and Professionalization**

**Internal Testing (Approach #3a)**:
- **Re-uses same testers over and over again**
- Same staff testers become familiar faces for AccessLabs
- **"Professional testers in practice"** because used so frequently
- Testers develop expertise in testing itself, not just AT use
- Narrow range of lived experience (same people, same AT configurations, same perspectives)

**External Paid Testing (Approach #3b)**:
- **Strives for "freshness"** with non-professional testers
- Recruits diverse external testers from broader community
- Less likely to re-use same testers repeatedly
- Testers bring external perspective, not CNIB-insider knowledge
- Broader range of lived experience

**Why "Professional Testers in Practice" Is Double-Edged**:

**Not Necessarily Bad**:
- Experienced internal testers know what to look for
- Efficient testing (less time explaining what to do)
- Familiar with CNIB systems and context
- Reliable and available
- Develop testing skills that complement AT expertise

**But Creates Limitations**:
- **Familiarity bias**: Experienced testers may unconsciously work around barriers that would stop new users
- **Narrow lived experience**: Same testers = same AT configurations, same interaction patterns, same cognitive models
- **Less "fresh eyes"**: May miss issues obvious to first-time users
- **Professionalization effect**: Testing becomes job, not authentic user experience
- **Diversity gap**: Small pool of repeat testers limits disability representation

**Example: Internal Tester Familiarity**

> **Experienced internal tester**: "I found a workaround for that navigation issue. You just need to press Tab five times and then Shift+Arrow. It's annoying but works."
>
> **First-time external tester**: "I can't figure out how to get to that section. I tried Tab but ended up somewhere else. I gave up after a few tries."
>
> **Result**: Internal tester reports "works with workaround" (severity: minor). External tester reports "can't complete task" (severity: critical). Both are correct from their perspective, but internal tester's familiarity masks severity for new users.

**4. Context and Bias**

**Internal Testing (Approach #3a)**:
- Testers are CNIB employees (institutional knowledge)
- May be more forgiving of CNIB systems ("we're trying our best")
- Understand CNIB context, mission, constraints
- Testing systems where they work (potential privacy concerns)

**External Paid Testing (Approach #3b)**:
- Testers have no CNIB affiliation (unbiased perspective)
- Hold CNIB to same standards as any other organization
- Don't know internal context or constraints
- External perspective reflects real user expectations

**Why This Matters**:
- Internal testers may unconsciously minimize severity due to organizational loyalty
- External testers provide honest assessment without insider bias
- Client-facing products need external perspective to reflect real user expectations

**5. Summary: When Each Approach Is Appropriate**

**Use Internal Testing (Approach #3a) When**:
- System is staff-only (not public-facing)
- Testing specific features CNIB staff will use
- Budget/timeline constraints require cost-effective approach
- Internal context knowledge is valuable
- Procurement decision needs quick "will this work for us?" answer

**Use External Paid Testing (Approach #3b) When**:
- System is client-facing or public-facing
- Need unbiased external perspective
- Comprehensive feature testing required (not just CNIB use cases)
- Need "freshness" of non-professional testers
- Stakes are high (legal, reputational, revenue)
- Broader disability representation needed
- Testing for diverse AT/device/browser configurations

**Use Both When**:
- Hybrid systems (internal and external interfaces)
- High-stakes internal systems requiring comprehensive testing
- Need both "will this work for us?" AND "is this accessible for diverse users?"

**The Reality**:
- Internal testing is **not inferior**, but it has **different strengths and limitations**
- Cost and timing pressures often drive internal testing choices
- Resource constraints limit breadth (fewer testers, less time, narrower scope)
- Repeat tester use creates professionalization that is both helpful and limiting
- External testing provides freshness and breadth that internal testing cannot

**Task Force Hope**:
- Organizational clarity on when internal testing is sufficient vs. when external testing is necessary
- Realistic budgets and timelines for comprehensive external testing
- Expanded internal tester pool to reduce over-reliance on same individuals
- Clear communication about limitations of internal testing (not "fully accessible", but "works for our staff")

---

#### 3a. Internal Staff Testers (Compensated with Points)

**Description**: CNIB staff with disabilities test products/services using their assistive technology

**Compensation Model**: "Points" system
- Staff earn points for testing participation
- Points redeemable for gifts from catalogue
- Points system used across CNIB for various recognition and participation activities
- Not cash payment but tangible compensation

**Tester Profile**:
- CNIB employees who use assistive technology
- Diverse disabilities represented (blind, low vision, Deafblind, other disabilities)
- Real users, not professional testers
- Using their own AT in authentic contexts

**Testing Approach**:
- Task-based scenarios (realistic workflows)
- Think-aloud protocol (narrate experience)
- Document barriers, frustrations, workarounds
- User perspective on severity and impact

**Advantages**:
- Authentic CNIB staff perspective
- Already familiar with CNIB context and needs
- Available and accessible
- Cost-effective (points vs. external recruitment)

**Considerations**:
- Staff capacity (testing on top of regular duties)
- Potential bias (employees may be more forgiving)
- Privacy (testing internal systems where they work)

**Organizational Ownership**: AccessLabs (design and execution)

---

#### 3b. External Paid Testers (Non-Professional Regular Users)

**Description**: External individuals with disabilities recruited and paid to test products/services

**Compensation Model**: Paid (cash or equivalent)
- Not professional accessibility testers by trade
- Regular users of assistive technology
- Compensated for time and expertise
- Rates appropriate for user testing participation

**Tester Profile**:
- People with disabilities from broader community
- Diverse disabilities, assistive technologies, experience levels
- Not CNIB employees (external perspective)
- Real users, not consultants or auditors

**Testing Approach**:
- Task-based scenarios
- Think-aloud protocol
- Document user experience, not just technical compliance
- Focus on usability and impact

**Advantages**:
- External unbiased perspective
- Don't know CNIB context/workarounds (fresh eyes)
- Can test client-facing products without employee bias
- Broader representation beyond CNIB staff

**Considerations**:
- Recruitment and coordination overhead
- Payment/contracting requirements
- May need more context/training than internal staff
- Scheduling complexity

**Organizational Ownership**: AccessLabs (design and execution)

---

### 4. Formal Audits by Professional Auditors (AccessLabs)

**Description**: Comprehensive WCAG conformance audits conducted by professional accessibility auditors

**Auditor Profile**:
- AccessLabs professional staff
- IAAP certification or equivalent expertise
- Trained in WCAG standards, testing methodologies, assistive technology
- Professional auditors, not just users

**Methodology**:
- Comprehensive WCAG 2.1 evaluation (all applicable success criteria)
- Automated testing baseline
- Manual expert review with multiple assistive technologies
- Code-level inspection
- May include lived experience testing (3a or 3b) as validation
- Professional report with ACR/VPAT

**Deliverables**:
- Accessibility Conformance Report (ACR)
- Detailed findings with WCAG violations
- Severity ratings and remediation recommendations
- Executive summary
- Code samples and implementation guidance

**Context**:
- AccessLabs commercial client engagements
- High-stakes internal projects requiring formal conformance
- Legal compliance requirements
- Partnership due diligence requiring professional opinion

**Organizational Ownership**: AccessLabs (design and execution)

---

### 5. Developer Assistance Package (AccessLabs-Supported Throughout Project Lifecycle)

**Description**: Comprehensive accessibility support embedded throughout internal project development, from concept to UAT (User Acceptance Testing)

**What It Is**:
- AccessLabs partners with internal project teams from initial concept through launch
- Proactive accessibility integration, not reactive testing
- Direct interface with external third-party developers (contracted by CNIB)
- On-demand accessibility expertise and testing throughout development

**Typical Project Context**:
- CNIB contracts external developers to build new platforms, apps, or features
- Custom development projects (not off-the-shelf vendor products)
- Internal systems requiring extensive customization
- Client-facing digital products developed for CNIB

**AccessLabs Role Throughout Lifecycle**:

**Phase 1: Concept and Planning**
- Attend project kickoff meetings
- Review initial requirements and user stories
- Provide accessibility requirements documentation
- Advise on accessible design patterns and frameworks
- Identify potential accessibility risks early

**Phase 2: Design**
- Review wireframes and mockups for accessibility
- Inspect design prototypes (Figma, Adobe XD, etc.)
- Provide feedback on color contrast, layout, navigation patterns
- Advise on accessible UI components and interactions
- Ensure designers understand WCAG requirements
- Attend design review meetings

**Phase 3: Development**
- Provide access to lived experience testing on demand for developers
- Review code commits/pull requests for accessibility issues
- Test incremental builds (not waiting until final product)
- Interface directly with developers via meetings and AccessLabs portal
- Provide technical guidance on ARIA, semantic HTML, keyboard interactions
- Offer code examples and implementation patterns

**Phase 4: Testing and Remediation**
- Conduct formal testing (smoke tests, lived experience testing, audits)
- Document findings in AccessLabs online portal
- Provide login access to developers for test results
- Screen recordings and detailed evidence available through portal
- Remediation support: issues can be retested on demand
- Track remediation progress through portal

**Phase 5: UAT and Launch**
- Final comprehensive testing before production launch
- User acceptance testing with lived experience testers
- Go/no-go recommendation
- Post-launch monitoring and support

**AccessLabs Online Portal**:
- **Test Results Dashboard**: Developers log in to view findings
- **Screen Recordings**: Video evidence of barriers with assistive technology
- **Issue Tracking**: Each barrier tracked with status (open, in progress, fixed, retested)
- **On-Demand Retesting**: Developers request retest when fix deployed
- **Historical Record**: All testing iterations documented
- **Evidence Package**: Screenshots, code samples, WCAG references
- **Communication Hub**: Comments and questions on specific issues

**Communication Channels**:
- **Regular meetings**: Scheduled check-ins with development team
- **Portal-based feedback**: Asynchronous communication through online portal
- **Direct developer interface**: AccessLabs works directly with external developers
- **Project documentation**: Accessibility requirements and guidance documents
- **Code reviews**: Inline feedback on implementation

**Benefits of Developer Assistance Package**:
- **Shift-left accessibility**: Catch issues early when cheaper/easier to fix
- **Reduced remediation costs**: Fix during development, not after launch
- **Developer education**: External developers learn accessible development practices
- **Quality assurance**: Continuous testing throughout lifecycle
- **On-demand support**: Testing when developers need it, not waiting for scheduled audit
- **Transparent tracking**: Portal provides visibility for all stakeholders
- **Iterative improvement**: Retest on demand enables rapid fix cycles

**Typical Use Cases**:
- **MyCNIB application**: Major update to how staff, clients, and volunteers discover CNIB programs, services, and information on vision health and assistive technology
- New CNIB mobile app developed by contracted agency
- Custom donor management platform built by external developers
- Client portal requiring extensive accessibility features
- Internal systems with complex workflows and interactions
- Projects where accessibility is mission-critical from start

**Compensation/Resourcing**:
- Internal CNIB projects: AccessLabs time allocated as internal support
- External client projects: AccessLabs involvement billed as part of development contract
- Developer Assistance Package may be requirement in contracts with external developers

**Organizational Ownership**: AccessLabs (design, execution, coordination throughout)

**Key Distinction from Other Approaches**:
- Not one-time testing at end (like formal audit)
- Not ad hoc (like informal testing)
- Embedded throughout development lifecycle (born accessible principle in practice)
- Proactive accessibility integration, not reactive remediation

---

## Key Insight: AccessLabs as Central Testing Function

**Critical Understanding**: All formal testing at CNIB—smoke tests, lived experience testing, professional audits, and developer assistance—is **designed and executed by AccessLabs**, not distributed across organization.

### What This Means

**AccessLabs Role**:
- Professional testing methodology
- Quality control and consistency
- Tester recruitment and coordination (both internal staff and external)
- Reporting standards
- Expertise and training
- Tools and infrastructure

**Not Ad Hoc**:
- Testing is not random staff members testing randomly
- Even "informal" lived experience testing has AccessLabs methodology and oversight
- Smoke tests follow consistent approach
- Professional standards apply

**Exception**:
- Only informal siloed testing by staff (approach #1) happens outside AccessLabs
- This is precisely what Task Force identified as problematic—lack of structure and consistency
- Task Force goal: Bring more structure to internal testing while preserving AccessLabs professional standards

**Developer Assistance Package (Approach #5)**:
- Represents born accessible principle in action: accessibility embedded from concept, not bolted on at end
- AccessLabs becomes development partner, not just auditor
- Online portal enables continuous collaboration between AccessLabs and developers
- On-demand testing throughout lifecycle (design, development, UAT)
- Example: MyCNIB application development with external contractors

---

## Testing Request Intake: Evolution from Informal to Structured

### Historical Model (Until November 2024)

**How Requests Arrived at AccessLabs**:
- All testing requests came to **Sheetal Kocchar** (prime lead for vendor procurement testing)
- **Completely informal channels**:
  - Email from departments across CNIB
  - Teams direct messages
  - No standardized intake form
  - No request tracking system
  - No formalized prioritization

**Organizational Context**:
- Sheetal's work moved to AccessLabs approximately 12 months ago (late 2023)
- Previously part of CNIB Research Team
- Move to AccessLabs formalized testing as social enterprise function

**Interim Tracking Solution (Past 12 Months)**:
- **Salesforce tracking** implemented after move to AccessLabs
- AccessLabs sales team manually records internal testing requests in Salesforce
- Purpose: Apply nominal internal costing to testing work
- Salesforce dashboards show volume and scale of internal testing to senior CNIB staff
- **Important limitation**: Sales-level tracking, not ERP-style production tracking
- Does not capture:
  - Detailed workflow steps
  - Individual tester assignments
  - Actual hours spent per request
  - Testing methodologies used
  - Remediation cycles

**Problems with Informal Model** (Even with Salesforce):
- **Request intake still informal**: Salesforce entered after-the-fact by sales team, not by requesters
- **No visibility at intake**: Requests still scattered across email threads and DMs before Salesforce entry
- **No tracking during execution**: Impossible to see real-time status, only post-completion logging
- **No prioritization framework**: First-come-first-served or "loudest voice"
- **Unrealistic expectations**: Even significant testing efforts requested with fast turnaround
- **Bottleneck**: All requests funneled through single person (Sheetal)
- **Delayed documentation**: Historical record created retrospectively in Salesforce, not at time of request
- **Capacity issues**: No way to manage workload or allocate resources systematically during execution
- **Sales vs. operations**: Salesforce designed for client sales tracking, not internal operational workflow
- **Lack of structure**: Precisely what Task Force identified as gap

**Typical Scenario**:
> Department head sends Teams message to Sheetal: "We need this new vendor platform tested by Friday for procurement decision. Can you help?"
>
> Reality: Platform requires 20+ hours of comprehensive testing. Sheetal already has 3 other requests in queue. No formal way to push back, negotiate timeline, or make requester aware of trade-offs.

**Impact**:
- AccessLabs team reactive, not proactive
- Testing quality at risk when rushed
- No data to advocate for additional resources
- Requesters frustrated by unclear timelines
- Informal process fed directly into creation of **Systems & Technology Subcommittee (S2)**

### New Model (November 2024 Launch)

**TopDesk Testing Request Form**:
- Formal intake system going live as of this week
- Service Desk / Contact Centre experience for internal testing clients
- Structured request capture with required fields
- Tracking and reporting capabilities

**What TopDesk Form Captures**:
- Requester information (department, contact, urgency)
- What needs testing (platform, document, app, website, etc.)
- Purpose (procurement, partnership, advocacy, internal development, etc.)
- Timeline and business need
- Scope (full platform vs. specific feature)
- Accessibility priority level
- Consequences if testing delayed

**What TopDesk Form Enables**:
- **Request tracking**: Every request has ticket number, status, history
- **Visibility**: Management can see volume, patterns, bottlenecks
- **Prioritization**: Transparent criteria for triaging requests
- **Capacity planning**: Data to justify additional resources
- **Timeline management**: Realistic turnaround based on scope and capacity
- **Accountability**: Clear ownership and status updates
- **Reporting**: Metrics on requests received, completed, average turnaround time

**What TopDesk Form Does NOT Track**:
- **Internal testing processes**: AccessLabs methodologies, tester assignments, detailed test plans
- **Internal planning**: Sprint planning, capacity allocation, professional development
- **Testing execution details**: Who tested, what tools used, how many hours spent
- **Portal activities**: Developer interactions, retest requests, remediation tracking

**TopDesk Scope**: Client-facing intake and tracking, not internal project management

**Integration with Existing Systems**:
- TopDesk form feeds into Salesforce for financial tracking
- Reports exported from TopDesk and sent to AccessLabs sales team
- Sales team continues to use Salesforce for nominal internal costing and dashboards
- **Still sales-level tracking, not ERP-style production tracking**
- Future state might integrate TopDesk directly with financial systems, eliminating manual export step

**Evolution of Tracking**:
1. **Pre-2023**: Informal requests, no tracking (Research Team era)
2. **2023-2024**: Informal requests + retrospective Salesforce logging (early AccessLabs era)
3. **November 2024**: TopDesk form for structured intake + Salesforce for financial tracking (current)
4. **Future (Task Force recommendation)**: Accessibility Hub with integrated request/financial/operational tracking

**What TopDesk Improves Over Salesforce-Only Model**:
- **Requester-initiated**: Requesters fill form themselves, not retrospective by sales team
- **Real-time visibility**: See request status during execution, not just post-completion
- **Operational focus**: Designed for request workflow, not sales pipeline
- **Immediate documentation**: Request captured at time of submission, not after completion
- **Standardized information**: Required fields ensure consistent data capture
- **Triage-ready**: Form structure enables prioritization decisions

**What TopDesk Still Doesn't Capture** (Like Salesforce):
- Internal testing processes and methodologies
- Detailed work breakdown and tester assignments
- Actual hours spent (still sales-level estimates, not ERP-style time tracking)
- Testing execution details
- True production-level operational metrics

**Relationship to Accessibility Hub Recommendation**:
- TopDesk form is **interim solution** for AccessLabs testing requests
- Accessibility Hub (Task Force recommendation) would expand this model organization-wide
- Hub would triage testing requests but also barrier reports, AT support, accommodation requests
- TopDesk testing form proves concept: structured intake reduces chaos
- Future Hub might integrate operational tracking with financial systems (beyond current sales-level approach)

### Why This Matters for Born Accessible Framework

**Maturity Progression**:

**Stage 1: Pre-2023 (Research Team Era) - Ad Hoc Model**:
- Accessibility testing perceived as "favor" or "extra work"
- No organizational visibility into testing as systematic function
- No data to prove need for resources
- Testing happens reactively, when problems arise
- Bolted-on approach: test at end when someone remembers

**Stage 2: 2023-2024 (Early AccessLabs) - Interim Visibility**:
- Move to AccessLabs signals testing as business function, not just research
- Salesforce tracking provides senior leadership visibility (dashboards)
- Nominal internal costing shows value/volume of internal testing
- **But**: Request intake still informal, tracking retrospective, sales-level only
- Improvement: Data exists for advocacy, but operational challenges remain

**Stage 3: November 2024 (TopDesk Launch) - Structured Intake**:
- Testing recognized as **organizational service** with demand, capacity, and value
- Request intake formalized (requesters initiate, not retrospective logging)
- Real-time visibility during execution, not just post-completion
- Data enables continuous improvement (where are bottlenecks? what's most requested?)
- Justification for dedicated resources (X requests per month, Y hours average)
- Proactive capacity planning possible
- Embedded approach: testing part of standard workflow for procurement, development, partnerships
- **Still limitation**: Sales-level financial tracking, not ERP-style production tracking

**Stage 4: Future (Accessibility Hub) - Integrated Model**:
- Hub integrates testing with broader accessibility services
- Potential for operational-level tracking (actual hours, detailed workflows)
- Organization-wide model (not just AccessLabs)
- Full integration with financial and operational systems

**S2 Subcommittee Origin**:
- Informal testing requests to Sheetal → Task Force identified as systemic gap
- S2 formed to create structure around testing, vendor accountability, barrier reporting
- TopDesk form is **direct outcome** of Task Force work
- Sheetal's dual role: AccessLabs testing lead + S2 committee member ensures real-world expertise informs recommendations

**Critical Concerns Driving S2 Formation** (Bob Dodd, Head of Accessibility at AccessLabs):

Two major concerns about internal CNIB testing informed S2 Subcommittee work:

**Concern #1: Scope of Testing**
- **Current practice**: Testing asks "Do you think it will work for our existing blind and low vision staff?"
- **Not comprehensive conformance**: Internal testing doesn't test to legal definition of accessibility conformance (AODA/WCAG)
- **Sampling, not exhaustive**: Testing samples application features requested, seldom entire functionality
- **Limited resources**: Testing done with limited time and resources
- **Narrow disability focus**: Natural focus/bias on blind and low vision means not testing full range of accessibility issues
- **Even within organization**: Testing doesn't cover all disabilities represented on AccessLabs testing team itself
- **Not Sheetal's fault**: Result of what AccessLabs management (Bob as her manager) tells her to do given constraints

**Critical Gap: Narrow Disability Representation in Internal Testing**

One of CNIB's great strengths is focus on what it means to be blind. This expertise is core to CNIB's mission and value. However, this focus creates a significant blind spot (literally and figuratively) in internal testing: **CNIB typically tests internally using only blind and low vision testers.**

**Who CNIB Does NOT Test With Internally**:

1. **Deaf/Deafened/Deafblind Users**
   - CNIB has Deafblind Community Services staff
   - Recent complaints from Deafblind staff about lack of testing with their community
   - Video content, audio alerts, captions, transcripts often untested
   - Deafblind users have unique AT needs (braille displays, tactile interfaces)

2. **Mobility/Dexterity/Kinesthetic Disabilities**
   - Users who cannot use mouse (keyboard-only navigation, switch control, eye-tracking)
   - Users with limited fine motor control (target size, clickable areas, drag-and-drop)
   - Users with tremor or spasticity (time limits, precision requirements)
   - Voice control users (Dragon NaturallySpeaking, Voice Control)

3. **Cognitive/Information Processing Disabilities**
   - Users with learning disabilities (dyslexia, dyscalculia)
   - Users with attention disorders (ADHD)
   - Users with memory challenges
   - Users with language processing difficulties
   - Complex interfaces, jargon, unclear instructions often not tested for cognitive accessibility

**Statistical Reality**:
- CNIB has thousands of staff and volunteers
- Statistically, significant numbers must have disabilities beyond blind/low vision
- Canada: ~22% of population reports disability (not all vision-related)
- Among CNIB staff/volunteers with vision disabilities, many also have other disabilities

**Intersectionality**:
- Being blind does not mean you have no other disability
- People experience blindness differently based on lived experience
- Blind person with mobility disability has different AT needs than blind person without
- Blind Deaf person has profoundly different AT needs than blind hearing person
- Age, language, education, technology access, socioeconomic status all intersect with disability

**Current Testing Practice**:
- Blind/low vision testers: Yes (typically 1-3 testers for internal requests)
- All other disabilities: No
- **Number of testers**: Bare minimum
  - Cost constraint: More testers = more points/payment
  - Timeline constraint: Many requests have unreasonably short timescales
  - Typical internal testing: 1-3 blind/low vision staff testers
  - Not enough testers even within blind/low vision (diverse AT, experience levels)
  - Definitely not enough to cover other disabilities

**Example: Typical Internal Testing Request**

> Request: Test new expense management system (internal staff use only)
>
> Testing done: 2 blind staff testers using JAWS and NVDA
> - Tester 1: Expert JAWS user, Windows, desktop
> - Tester 2: Intermediate NVDA user, Windows, laptop
>
> Not tested:
> - Keyboard-only navigation (mobility)
> - Voice control (mobility)
> - Cognitive load (information processing)
> - Captions on training videos (Deaf/Deafblind)
> - Mobile responsiveness (diverse devices)
> - VoiceOver on Mac/iOS (different screen reader)
> - ZoomText without screen reader (low vision only)
> - Beginner screen reader users (experience level diversity)

**Why This Matters**:

1. **Legal Compliance**
   - AODA requires accommodation for all disabilities, not just vision
   - Testing only blind/low vision = incomplete legal due diligence
   - System may be accessible for blind users but not for Deaf or mobility-disabled users

2. **CNIB Staff Equity**
   - CNIB staff with non-vision disabilities excluded from testing
   - Barriers may only be discovered after deployment (too late for preventive testing)
   - Staff with multiple disabilities may face compounded barriers

3. **CNIB Mission Alignment**
   - CNIB advocates for accessibility broadly (not just vision)
   - CNIB's Come to Work program supports employers with all disability accommodations
   - Internal practice should reflect external advocacy

4. **Quality and Effectiveness**
   - Systems accessible for blind users but not others = incomplete accessibility
   - Keyboard navigation issues affect blind AND mobility-disabled users (testing only screen reader users misses keyboard-only users)
   - Cognitive accessibility benefits everyone (plain language, clear instructions, consistent navigation)

**Deafblind Community Services Staff Complaint**:
- Staff from Deafblind Community Services have recently raised concerns
- Feel excluded from testing process
- Systems deployed without testing for Deafblind user needs
- Barriers discovered only after launch, when remediation more expensive
- "Nothing About Us Without Us" principle violated

**Resource and Timeline Pressures**:

**Why So Few Testers?**
1. **Cost**: More testers = more points (staff) or more payment (external)
2. **Timeline**: Unreasonably short deadlines mean limited testing window
3. **Availability**: Finding testers with specific disabilities and availability is difficult
4. **Process**: No formal process to recruit diverse disability testers

**Typical Timeline Constraint**:
> Procurement: "We need this tested by Friday for procurement decision Monday."
>
> Reality: Friday is 3 days away. Finding, scheduling, and testing with even 2-3 blind testers is challenging. Finding and scheduling Deaf, mobility, and cognitive disability testers is impossible in that timeframe.

**Consequence**: Default to bare minimum blind/low vision testers because they're known, available, and fit within tight timeline.

**What S2 Should Recommend**:

**Disability Representation Framework**:
1. **Baseline Testing** (all internal systems):
   - Blind/low vision: 2-3 testers (JAWS, NVDA, VoiceOver, ZoomText)
   - Keyboard-only/mobility: 1-2 testers (no mouse, voice control)
   - Cognitive: 1 tester or expert heuristic review

2. **Expanded Testing** (external-facing systems, high-stakes internal):
   - Add Deaf/Deafblind: 1-2 testers (captions, transcripts, visual alerts)
   - Expand mobility: Additional voice control, switch control, eye-tracking
   - Expand cognitive: User testing with diverse cognitive abilities

3. **Tester Diversity Within Blind/Low Vision**:
   - Expert vs. beginner screen reader users
   - Windows vs. Mac vs. mobile
   - JAWS vs. NVDA vs. VoiceOver vs. TalkBack
   - Braille display users
   - Different age groups, language backgrounds, technology access

**Tester Recruitment and Compensation**:
- **Internal CNIB staff**: Build roster of staff with diverse disabilities willing to test (compensated with points)
- **CNIB volunteers**: Recruit volunteers with diverse disabilities (compensated appropriately)
- **External testers**: Partner with disability communities for external perspective
- **Fair compensation**: Recognize expertise across all disabilities (not just vision)

**Timeline Reality**:
- Diverse disability testing requires MORE time, not less
- Procurement timelines must account for comprehensive testing
- "Test by Friday" incompatible with diverse disability testing
- S2 should recommend minimum testing timelines based on scope

**Budget Reality**:
- Comprehensive testing costs more (more testers, more disability categories)
- Budget for diversity, not just blind/low vision minimum
- Cost of fixing barriers post-launch > cost of comprehensive testing pre-launch

**Critical Gap: Internal vs. External User Interfaces**

CNIB does not formally consider the roles of users who interact with systems and products when scoping internal testing. This creates significant blind spots.

**Example: ADP Recruitment Module**

**Two User Interfaces**:
1. **Internal staff view**: Used by CNIB HR and hiring managers
2. **External candidate view**: Used by non-CNIB job applicants

**Current Testing Approach**:
- **Internal staff interface**:
  - Tested against IT department's supported configurations
  - Clear guidelines: specific operating systems, browsers, assistive technology
  - Points-based staff testers acceptable
  - Scope bounded by CNIB staff needs

- **External candidate interface**:
  - Often tested with same approach as internal (or not tested separately at all)
  - **Problem**: External users don't follow CNIB IT guidelines
  - External users have diverse:
    - Operating systems (Windows, macOS, Linux, ChromeOS, mobile)
    - Browsers (Chrome, Firefox, Safari, Edge, mobile browsers)
    - Assistive technologies (JAWS, NVDA, VoiceOver, TalkBack, ZoomText, Dragon, etc.)
    - Devices (desktops, laptops, tablets, smartphones)
    - Experience levels (from expert to novice AT users)

**Why External-Facing Interfaces Require Different Testing**:

1. **Broader User Diversity**
   - Internal staff: Known configurations, managed IT environment
   - External candidates: Unknown configurations, unmanaged environments
   - Testing scope must expand to cover diverse technology stacks

2. **Legal Compliance Requirements**
   - **Internal systems**: Duty to accommodate (AODA employment provisions)
   - **External-facing systems**: Public-facing accessibility requirements (AODA customer service, information and communications)
   - Legal bar higher for public-facing systems
   - CNIB cannot claim "works for our staff" when external users have barriers

3. **Reputational Impact**
   - **Internal system barrier**: Staff escalates to IT/AccessLabs, resolved internally
   - **External candidate barrier**: Candidate may abandon application, tell others, damage CNIB reputation
   - CNIB as accessibility organization held to higher public standard
   - Inaccessible recruitment contradicts CNIB's mission and expertise

4. **Policy Alignment**
   - **CNIB accessibility policies and strategies**: Commitment to accessible practices
   - **Recruitment accessibility**: Cannot have accessible hiring if recruitment tools exclude candidates with disabilities
   - **Integrity issue**: Saying we value accessibility while recruitment system creates barriers

5. **Testing Resource Requirements**
   - **Internal testing**: Points-based staff testers may suffice
   - **External testing**: Requires paid external testers (diverse AT, devices, experience levels)
   - **Comprehensive testing**: More AT combinations, more browser/OS combinations, more devices
   - **Cost**: Significantly higher for external-facing systems

**Current Organizational Challenge**:

**Resistance to Expanded Testing Scope**:
- "More testing" perceived as burden
- "More cost" not budgeted or expected
- "Why can't we just use points-based testers?" (because external users need external perspective)
- Lack of understanding that external-facing = different legal/reputational requirements

**Example Conversation**:
> Internal stakeholder: "Can't we just have our staff test the candidate portal? They already tested the internal view."
>
> AccessLabs perspective: "Staff testing is valuable but insufficient. External candidates use different AT, different devices, different browsers. Staff are also familiar with CNIB context—they'll work around issues a candidate might not. We need external paid testers for the candidate-facing interface, and broader AT/device coverage. This is more expensive, but legally and reputationally necessary."

**What's Missing: Formal Scoping Framework**

CNIB lacks formal process to assess:
- **Who will use this system?** (staff only, external users, both?)
- **What access do external users have?** (entire system, limited features, specific workflows?)
- **What are legal requirements?** (internal accommodation vs. public accessibility standards?)
- **What is reputational risk?** (low-visibility internal tool vs. high-visibility public interface?)
- **What testing scope is required?** (staff configurations only vs. diverse external configurations?)
- **What testing resources are needed?** (points-based staff vs. paid external testers, comprehensive AT/device coverage?)

**Consequence: Underestimated Testing Scope and Cost**

When procurement requests testing, default assumption often:
- "Test if it works for our staff"
- Budget for limited testing (points-based staff testers, quick timeline)
- Surprise when AccessLabs says "external interface needs comprehensive paid testing"
- Tension between what should be tested vs. what was budgeted

**Task Force Hope: Clearer Understanding of Necessary Scope and Cost**

One of Bob Dodd's primary hopes for Accessibility Task Force:
- **Organizational clarity**: Formal framework for scoping testing based on user roles
- **Budget reality**: Accurate cost estimates for external-facing system testing
- **Procurement integration**: Testing scope assessment built into procurement process (before purchase)
- **Policy alignment**: Testing requirements that reflect CNIB's accessibility commitments
- **Risk management**: Appropriate testing investment based on legal/reputational risk

**What S2 Should Recommend**:

**User Role Assessment Framework**:
- Every system testing request asks: "Who are the users?" (staff, external, both?)
- External-facing systems automatically trigger expanded testing scope
- Clear definitions:
  - **Staff-only**: CNIB IT supported configurations, points-based testers acceptable
  - **External-facing**: Diverse configurations, paid external testers required, comprehensive AT/device/browser coverage
  - **Hybrid**: Separate testing for each interface, different scopes

**Testing Scope Matrix**:
| User Type | Legal Requirement | AT/Device Coverage | Tester Type | Estimated Cost | Timeline |
|-----------|-------------------|-------------------|-------------|----------------|----------|
| **Staff-only** | Accommodation (AODA employment) | CNIB IT supported configs | Points-based staff | Lower | Shorter |
| **External-facing** | Public accessibility (AODA information/communications) | Broad AT/device/browser coverage | Paid external testers | Higher | Longer |
| **Hybrid** | Both | Both (separate testing for each interface) | Both | Highest | Longest |

**Procurement Integration**:
- User role assessment happens at procurement stage (before purchase decision)
- Accurate testing cost estimates included in total cost of ownership
- Testing timeline built into implementation schedule
- No surprises: "We thought it was just staff testing, why is this so expensive?"

**Budget Advocacy**:
- Data from testing requests shows proportion of external-facing systems
- Justification for dedicated external tester budget (not ad hoc per-request)
- Capacity planning: X external-facing systems per year = Y external testing hours needed

**What Internal Testing Is**:
- Valuable for procurement decisions ("will this work for our staff?")
- Quick assessment of usability for blind/low vision users
- Smoke testing with lived experience perspective
- Helps CNIB make informed purchasing decisions

**What Internal Testing Is NOT**:
- Legal conformance statement (AODA/WCAG compliance audit)
- Testing all features of product (only features CNIB uses)
- Testing for full range of disabilities (focus on blind/low vision)
- Guarantee of accessibility for all users
- Formal accessibility audit with ACR/VPAT deliverable

**Concern #2: Lack of Transparency Over What Gets Reported**
- **Internal confusion**: CNIB staff sometimes use term "fully accessible" casually as shorthand
- **External risk**: Concern that vendors may interpret CNIB's "it works for us" as conformance statement
- **Vendor communication**: Fear that vendor tells other customers "CNIB said our tool is fully accessible" when CNIB never tested comprehensively
- **Reputational risk**: Could come back to bite CNIB if vendor makes false claims based on limited CNIB testing
- **Legal implications**: "Fully accessible" has legal meaning (AODA/WCAG conformance); casual use could create liability
- **No standardized reporting**: No clear framework for what language to use internally vs. externally

**Example: Mercer**:
- CNIB uses Mercer platform
- Never tested Mercer against AODA/WCAG standards
- Staff may say "works for us" or even "fully accessible"
- Legally, "fully accessible" would mean conformance statement on ALL features (not just ones CNIB uses) for ALL disabilities (not just blind/low vision)
- Gap between internal shorthand and external legal/professional standards

**Communication with Senior Management**:
- Bob Dodd raised concerns with senior CNIB leadership (Finance area)
- Explained difference between "works for our staff" vs. "fully accessible" (legal conformance)
- Clarified scope and limitations of internal testing
- Emphasized need for clear definitions, especially when dealing with external vendors
- Senior leadership receptive: committed to involving AccessLabs in future platform assessments
- Concerns fed directly into S2 Subcommittee formation

**How S2 Addresses These Concerns**:

**S2 Recommendation: Standardized Testing Protocol**
- Document what each testing level means (Approaches #1-5)
- Clear language for each: "smoke tested with blind/low vision staff" vs. "WCAG 2.1 AA conformant"
- Standardized reporting templates with appropriate disclaimers
- Internal vs. external communication guidelines

**S2 Recommendation: Vendor Accountability Framework**
- Clear contracts stating what CNIB testing does and doesn't cover
- Vendor prohibited from misrepresenting CNIB testing results
- Formal ACR/VPAT required from vendor (not just CNIB internal testing)
- Documentation of what CNIB tested vs. what vendor claims

**S2 Recommendation: Capacity and Resources**
- Acknowledge current testing has resource constraints
- Justify additional AccessLabs capacity for comprehensive testing when stakes are high
- Clear decision framework: when is internal testing sufficient vs. when is formal audit needed?

**Born Accessible Principle**:
- Systematic intake processes = accessibility as infrastructure, not afterthought
- Tracking and visibility = accountability and continuous improvement
- Structured requests = realistic timelines, quality testing, sustainable workload
- Data-driven decisions = evidence-based resource allocation
- **Honest assessment of limitations** = integrity and risk management
- **Clear communication standards** = professionalism and legal protection

### Implications for Task Force Recommendations

**Systems & Technology Subcommittee S2** (Standardized Testing Protocol) should:
- Partner with AccessLabs to document existing methodologies (don't reinvent)
- Extend AccessLabs protocols to internal testing requests
- Create clear pathways for staff to request AccessLabs testing
- Define when informal testing is appropriate vs. when AccessLabs involvement needed
- Integrate AccessLabs approaches with Accessibility Hub intake
- **Build on TopDesk testing request form**: Already implemented as of November 2024, proving structured intake works
- Evaluate TopDesk form effectiveness after 3-6 months (volume, turnaround times, user satisfaction)
- Use TopDesk data to inform Accessibility Hub design

**Not starting from scratch**:
- AccessLabs has professional methodologies that work (Approaches #2-5)
- TopDesk form already operational for testing requests
- Challenge is making them accessible and known across organization
- S2 can learn from TopDesk implementation: what works, what needs improvement

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

**CNIB Leadership in National Procurement Standards**:
- **Sheetal Kocchar** (AccessLabs, reporting to Bob Dodd, Head of Accessibility): Prime lead for vendor procurement testing at CNIB Foundation/AccessLabs
- Provided research to Accessibility Standards Canada that influenced national guidance
- **National Impact**: CNIB research contributed to [Technical Guide on Procurement of Accessible Services](https://accessible.canada.ca/creating-accessibility-standards/technical-guide-procurement-accessible-services)
- Guide jointly developed by Accessibility Standards Canada and Public Services and Procurement Canada
- Supports *Accessible Canada Act* goal of barrier-free society by 2040
- **Sheetal serves on Systems & Technology Subcommittee (S2)**, bringing procurement expertise to Task Force

**National Procurement Framework** (CNIB-Influenced):
1. **Define Requirements**: Clarify service purpose, end users (including people with disabilities), deliverables
2. **Identify Barriers**: Assess physical, communication, environmental, technological, attitudinal, organizational obstacles
3. **Gather Information**: Research applicable accessibility standards (CAN/ASC - EN 301 549:2024), market capacity
4. **Develop Requirements**: Create enforceable specifications and evaluation criteria

**Vendor Assessment Requirements** (National Standard):
- Accessibility Conformance Reports (ACRs) or VPATs required from suppliers
- Evidence of experience with accessible services
- User testing involving people with disabilities
- Conformance testing to validate against standards
- Phased compliance timelines if full accessibility not immediate

**CNIB's Role**:
- Expertise developed through internal procurement testing → national guidance
- AccessLabs professional testing validates vendor claims
- SAP Concur case study: Example of procurement testing catching accessibility gaps
- Sheetal's research → federal government adoption → benefits all Canadian organizations

---

#### Practical Challenges of Vendor Testing

While CNIB has developed national leadership in procurement testing methodology, **actual execution faces significant operational challenges** that impact testing quality, timeline, and effectiveness.

**Challenge #1: Complex Systems and High Learning Curves**

**The Reality**:
- Third-party vendor tools are often **extremely complex**
- Learning curve into new platforms can be very high
- AccessLabs testing team (Sheetal typically leads vendor testing) cannot be experts in every vendor platform
- Without domain expertise, testing may miss critical accessibility barriers in complex workflows

**What This Means**:
- **Reliance on clear direction from requester**: Sheetal needs clear guidance on what features/workflows to test
- **Dependency on test scenarios**: Without structured test scenarios, testing may focus on surface-level features and miss critical barriers
- **Risk of incomplete testing**: Complex enterprise systems have dozens or hundreds of features; without guidance, testing may miss key use cases

**Example: Enterprise HR Platform**

> **Scenario**: CNIB considering new HR platform with modules for:
> - Recruitment and applicant tracking
> - Onboarding and offboarding
> - Performance management
> - Learning and development
> - Compensation and benefits
> - Time tracking and leave management
> - Reporting and analytics
>
> **Challenge**: Sheetal is not an HR expert. Without clear direction:
> - Which modules will CNIB actually use?
> - Which workflows are mission-critical?
> - What does "performance review cycle" look like in this system?
> - How do employees vs. managers vs. HR staff interact with system?
> - What reports are essential for compliance?
>
> **Without Clear Test Scenarios**:
> - Testing may focus on obvious features (login, navigation, search)
> - May miss critical but non-obvious workflows (batch operations, approval chains, reporting)
> - May not test different user roles (employee vs. manager vs. HR admin)
> - May not discover barriers that emerge only in multi-step processes

**What Sheetal Needs (But Doesn't Always Get)**:

1. **Clear Scope Definition**
   - Which modules/features will CNIB use?
   - Which modules are "must test" vs. "nice to test if time permits"?
   - Priority ranking of features by business criticality

2. **Structured Test Scenarios**
   - Step-by-step workflows for key use cases
   - Example: "New employee onboarding: HR creates record → Manager assigns training → Employee completes forms → System triggers background check"
   - Realistic data and context for each scenario

3. **User Role Mapping**
   - Who uses this system? (employees, managers, HR staff, executives, external candidates?)
   - What permissions/views does each role have?
   - Which roles must be tested for accessibility?

4. **Domain Expert Availability**
   - Subject matter expert (requester, department staff) available to answer questions
   - Someone who knows how CNIB will actually use the system
   - Clarification on unfamiliar terminology or workflows

**Challenge #2: Sandbox/Test Environment Availability**

**The Reality**:
- **Lived experience testing requires working sandbox environment** with realistic test data
- Vendors often do not provide sandbox access, or only limited trial access
- Sandbox environments may have tight time windows (e.g., "30-day trial")
- Realistic test data may not be available in sandbox (empty database, generic examples)

**What This Means**:
- **Cannot conduct meaningful lived experience testing** without functioning sandbox
- Tight time windows create impossible planning constraints (finding testers, scheduling sessions)
- Lack of realistic data means testing generic workflows, not real CNIB use cases
- May be forced to test in vendor's demo environment (not configured for CNIB needs)

**Example: Vendor Trial Access Problems**

> **Scenario 1: 30-Day Trial Window**
>
> Vendor provides 30-day trial access for testing. Sounds reasonable, but:
>
> **Week 1**: Procurement finalizes trial agreement, vendor sets up trial account, credentials sent to Sheetal
> **Week 2**: Sheetal does smoke testing, discovers major configuration issues, requests vendor support
> **Week 3**: Vendor resolves configuration, but now only 10 days left. Sheetal needs to:
> - Recruit internal testers (find staff with availability)
> - Schedule testing sessions (coordinate multiple calendars)
> - Conduct testing sessions (1-2 hours per tester)
> - Analyze results and prepare report
>
> **Week 4**: Rush to complete testing before trial expires. Quality compromised due to time pressure.
>
> **Result**: Testing rushed, limited testers (whoever is available), incomplete scenarios.

> **Scenario 2: No Sandbox Available**
>
> Vendor refuses sandbox access: "Sign contract first, then we'll provide training environment."
>
> **CNIB Position**: Need to test accessibility before purchase decision.
> **Vendor Position**: Accessibility testing happens post-purchase during implementation.
> **Result**: Procurement stalemate. CNIB forced to either:
> - Accept vendor claims without validation (risky)
> - Request formal ACR/VPAT (which vendor may not have or may be outdated)
> - Decline to purchase (miss out on potentially suitable product)

> **Scenario 3: Generic Demo Environment**
>
> Vendor provides access to generic demo environment shared across all trial customers.
>
> **Problems**:
> - No CNIB-specific configuration (workflows don't match CNIB reality)
> - Generic fake data (testers can't test realistic scenarios)
> - Shared environment (other trial customers using it simultaneously, data mixed up)
> - Demo scripted for sales, not accessibility testing (may not expose barriers)
>
> **Result**: Testing surface-level only, doesn't reflect actual CNIB usage.

> **Scenario 4: Sandbox Available But Not Configured**
>
> Vendor provides sandbox, but it's empty (no data, no configuration).
>
> **Problem**: Who configures sandbox for testing?
> - Vendor: "That's your job during implementation."
> - CNIB IT: "We can't configure until we purchase."
> - Sheetal: "I need realistic workflows to test, not empty forms."
>
> **Result**: Testing incomplete because workflows can't be simulated without configuration and data.

**What AccessLabs Needs (But Doesn't Always Get)**:

1. **Adequate Sandbox Access**
   - Functioning test environment separate from production
   - Configured to reflect CNIB's planned usage (not generic demo)
   - Available for sufficient duration (not tight 30-day window)
   - Renewable if testing discovers issues requiring vendor remediation and retest

2. **Realistic Test Data**
   - Sample data that reflects CNIB use cases (not generic "John Doe" examples)
   - Multiple user accounts with different roles/permissions
   - Workflows configured end-to-end (not just empty forms)
   - Data volume sufficient to test performance with AT (not 3 sample records)

3. **Vendor Support During Testing**
   - Technical support available when testers encounter configuration issues
   - Vendor accessibility team available for questions
   - Ability to request configuration changes if testing exposes issues
   - Documentation for testers (how to access, what credentials to use)

4. **Flexible Testing Timeline**
   - Sandbox access starts when CNIB is ready (after test scenarios defined, testers recruited)
   - Duration accounts for realistic testing timeline (not arbitrary 30 days)
   - Extension available if remediation and retesting needed
   - No pressure to rush testing due to trial expiration

**Challenge #3: Coordination Across Multiple Stakeholders**

**The Reality**:
- Vendor testing requires coordination between:
  - **Requester** (department requesting purchase): Defines scope, provides test scenarios
  - **Procurement**: Negotiates trial access, contract terms
  - **IT**: Sets up network access, credentials, may configure sandbox
  - **Sheetal/AccessLabs**: Conducts testing
  - **Vendor**: Provides sandbox, technical support, responds to findings
  - **Testers**: Staff with disabilities who conduct lived experience testing
  - **Senior management**: Makes purchase decision based on testing results

**Coordination Failures**:
- Requester assumes AccessLabs knows what to test (no test scenarios provided)
- Procurement negotiates trial without consulting AccessLabs on adequate duration
- IT blocks sandbox access due to security policies (firewall, VPN requirements)
- Vendor provides sandbox but no one told testers how to access it
- Testers available Week 2, but sandbox not ready until Week 3
- Testing finds critical barriers, but vendor not responsive during trial period
- Trial expires before testing complete, no one requested extension in time

**Example: What Often Happens**

> **Week 1**: Department head sends Teams message to Sheetal: "We need this platform tested by Friday for procurement decision next week."
>
> **Reality Check**:
> - Sheetal has never seen this platform
> - No test scenarios provided
> - No sandbox access yet (procurement still negotiating trial)
> - Timeline unrealistic for lived experience testing
> - Sheetal already has 3 other testing requests in queue
>
> **Outcome Options**:
> 1. **Sheetal does quick smoke test only** (surface-level, no lived experience testing) - gives false confidence
> 2. **Sheetal pushes back** (realistic timeline needed) - procurement frustrated, decision delayed
> 3. **Sheetal rushes testing** (quality compromised, barriers missed) - risk of purchasing inaccessible product
> 4. **Sheetal says no** (insufficient information/access) - department proceeds without accessibility testing
>
> All outcomes are suboptimal. Root cause: Lack of systematic process for vendor testing requests.

**What Would Help (S2 Recommendations)**:

1. **Standardized Vendor Testing Request Process** (Now: TopDesk Form)
   - Required fields: What platform? What features will CNIB use? Who are the users?
   - Minimum lead time: 2-4 weeks for comprehensive testing (not "by Friday")
   - Test scenario template: Requester provides structured workflows
   - Sandbox requirements checklist: What AccessLabs needs from vendor

2. **Procurement Integration**
   - **Before** initiating vendor trial, procurement consults AccessLabs on timeline and requirements
   - Trial duration negotiated based on testing needs, not vendor's standard terms
   - Sandbox access and support terms written into trial agreement
   - Extension clause if testing discovers issues requiring remediation

3. **Vendor Accountability in Contracts**
   - Vendors must provide functional sandbox for accessibility testing
   - Vendors must provide technical support during testing period
   - Vendors must respond to accessibility findings within defined timeframe
   - If vendor cannot provide adequate testing environment, formal ACR/VPAT required

4. **Requester Responsibility**
   - Requester provides clear scope definition and test scenarios
   - Requester designates subject matter expert available during testing
   - Requester understands testing timeline (not "by Friday")
   - Requester involved in interpreting results (accessibility barriers vs. CNIB needs)

5. **IT Coordination**
   - IT looped in early for network access, security review
   - Sandbox access not blocked by firewall/VPN issues
   - Test user accounts created in advance
   - IT available during testing window for technical issues

**Why This Matters for Born Accessible Framework**:

**Current State: Reactive and Fragile**
- Testing happens at end of procurement process (vendor already selected)
- Insufficient time, information, and access for quality testing
- Coordination failures create gaps (no test scenarios, no sandbox, rushed timeline)
- False confidence from surface-level testing, or no testing at all
- Accessibility barriers discovered post-purchase (expensive remediation or abandonware)

**Born Accessible State: Proactive and Systematic**
- Accessibility testing planned at start of procurement process
- Adequate time allocated (weeks, not days)
- Test scenarios defined by requesters who know the business need
- Sandbox access and vendor support negotiated upfront
- Coordination built into process (not ad hoc scrambling)
- Testing results inform purchase decision (before commitment)
- Quality testing = fewer post-purchase surprises

**SAP Concur as Case Study**:
- Complex enterprise expense management platform
- High learning curve (expense policies, approval workflows, reporting)
- Testing identified significant accessibility barriers
- But: Testing happened too late in process, after procurement decision largely made
- **Lesson**: Earlier testing with clear scenarios and adequate sandbox access could have prevented purchase of inaccessible platform

**Task Force Hope: Systematic Vendor Testing Process**

One of Bob Dodd's hopes for Task Force (now partially realized with TopDesk form):
- Structured intake process for vendor testing requests
- Minimum lead times based on system complexity
- Requester responsibilities (scope, scenarios, SME availability)
- Procurement coordination (trial terms that enable quality testing)
- Vendor accountability (sandbox access, support, responsiveness)
- Clear communication about timeline reality (comprehensive testing takes time)

**The TopDesk testing request form addresses some challenges**, but full solution requires:
- Procurement policy integration (testing upfront, not afterthought)
- Vendor contract templates (sandbox access requirements)
- Requester education (what AccessLabs needs to test effectively)
- Organization-wide understanding: Quality testing prevents expensive mistakes

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

## Testing Tier Summary Table (Revised with Organizational Ownership)

| CNIB Approach | Description | Who | Time | Org Ownership | Output |
|---------------|-------------|-----|------|---------------|--------|
| **#1: Informal Siloed** | Staff test with own AT, ad hoc | Any AT user | 5-15 min | Distributed (not AccessLabs) | Verbal/email feedback |
| **#2: Smoke Test** | Quick verification of basic accessibility | AccessLabs staff | 1-2 hours | AccessLabs | Brief go/no-go report |
| **#3a: Lived Experience (Internal)** | Staff testers, compensated with points | CNIB staff with AT | 1-2 hrs × 3-5 staff | AccessLabs | User testing report |
| **#3b: Lived Experience (External)** | External paid testers (non-professional) | External users with AT | 1-2 hrs × 3-5 users | AccessLabs | User testing report |
| **#4: Formal Audit** | Comprehensive WCAG conformance audit | AccessLabs professional auditors | 40-80+ hours | AccessLabs | ACR/VPAT + comprehensive report |
| **#5: Developer Assistance** | Embedded accessibility support throughout development lifecycle | AccessLabs + project team + external developers | Ongoing (weeks to months) | AccessLabs | Portal access, iterative testing, remediation tracking, final approval |

### Relationship to Previous "Level" Framework

The previous "Level 0-4" framework is useful for understanding rigor spectrum, but actual CNIB structure is:

**Previous Levels → Actual CNIB Approaches**:
- **Level 0** = Approach #1 (Informal Siloed Testing)
- **Level 1** = Could be Approach #1 (if more structured) or Approach #2 (Smoke Test)
- **Level 2** = Approach #2 (Smoke Test) or part of Approach #4 (expert review component)
- **Level 3** = Approach #3a or #3b (Lived Experience Testing)
- **Level 4** = Approach #4 (Formal Audit)
- **Approach #5** doesn't map to single level—it combines multiple levels throughout project lifecycle

**Key Difference**: In actual CNIB practice, Approaches #2-5 are all AccessLabs-designed and executed, not distributed across organization.

**Developer Assistance Package as Born Accessible Model**:
- Approach #5 represents shift-left accessibility: prevention rather than remediation
- Combines multiple testing levels at appropriate project phases
- Design phase: Expert review (like Level 2)
- Development: On-demand user testing (like Level 3) + expert guidance
- UAT: Formal testing (like Level 4)
- Not a testing "level" but a comprehensive accessibility partnership model

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

**Current State (November 2024)**:
- **TopDesk Testing Request Form**: Operational as of this week
- Staff submit testing requests via TopDesk form (Service Desk interface)
- Requests go to Sheetal Kocchar (AccessLabs testing lead)
- Form captures: requester, what needs testing, purpose, timeline, scope, urgency
- Every request tracked with ticket number, status, history
- Enables visibility, prioritization, capacity planning, reporting

**Future State (Task Force Recommendation)**:
- **Accessibility Hub** expands TopDesk model organization-wide
- Hub serves as central intake not just for testing but also barrier reports, AT support, accommodation requests
- Hub triages based on:
  - Purpose (procurement, partnership, advocacy, internal development, client service)
  - Urgency (blocking decision, upcoming launch, periodic review)
  - Scope (full platform, specific feature, document, etc.)
- Hub assigns appropriate testing level
- Hub coordinates testers and schedules
- Hub delivers results and tracks follow-up

**Evolution**:
- Phase 1 (complete): TopDesk form for AccessLabs testing requests
- Phase 2 (Task Force recommendation): Accessibility Hub integrates testing with broader accessibility services
- TopDesk proves structured intake works; Hub scales model organization-wide

### Who Does What Testing (Revised Based on Actual CNIB Structure)

**Approach #1: Informal Siloed Testing**:
- **Who**: Any staff with assistive technology
- **Coordinated by**: Not coordinated (distributed, ad hoc)
- **Challenge**: This is the gap Task Force identified—lack of structure
- **Recommendation**: Accessibility Hub should provide light structure (reporting template, optional logging) without stifling quick informal feedback

**Approach #2: Smoke Testing**:
- **Who**: AccessLabs staff exclusively
- **Coordinated by**: AccessLabs
- **Request through**: Accessibility Hub (proposed) or direct to AccessLabs
- **Note**: Quick turnaround (1-2 hours); designed for triage

**Approach #3a: Lived Experience Testing (Internal Staff)**:
- **Who**: CNIB staff with disabilities who use assistive technology
- **Recruited by**: AccessLabs
- **Compensated**: Points system (redeemable for gifts)
- **Methodology**: AccessLabs-designed task scenarios and protocols
- **Coordinated by**: AccessLabs
- **Typical use**: Internal systems, internal products, moderate-stakes testing

**Approach #3b: Lived Experience Testing (External Paid Testers)**:
- **Who**: External individuals with disabilities (non-professional users)
- **Recruited by**: AccessLabs
- **Compensated**: Cash/equivalent payment
- **Methodology**: AccessLabs-designed task scenarios and protocols
- **Coordinated by**: AccessLabs
- **Typical use**: Client-facing products, unbiased external perspective needed, higher-stakes testing

**Approach #4: Formal Professional Audits**:
- **Who**: AccessLabs professional auditors (IAAP-certified or equivalent)
- **Coordinated by**: AccessLabs project managers
- **May include**: Approaches #3a or #3b as validation component
- **Typical use**: Commercial engagements, legal compliance, high-stakes procurement

**Approach #5: Developer Assistance Package**:
- **Who**: AccessLabs accessibility specialists + internal project team + external developers
- **Coordinated by**: AccessLabs project managers
- **Duration**: Throughout project lifecycle (concept to UAT)
- **Portal access**: Developers log in to AccessLabs online portal for test results
- **Incorporates**: Approaches #2, #3a/3b, and #4 at appropriate project phases
- **Typical use**: Internal custom development projects, especially with external contractors (e.g., MyCNIB application)

**Key Principle**: AccessLabs is the professional testing function for all formal testing (Approaches #2-5). Task Force challenge is connecting staff needs to AccessLabs capacity efficiently.

---

## Integration with Born Accessible Principles

### Prevention Over Remediation

Testing throughout lifecycle prevents expensive post-launch remediation:
- **Design phase**: Level 0-1 testing of mockups, prototypes
- **Development**: Level 1-2 automated testing in CI/CD, manual spot checks
- **Pre-launch**: Level 2-3 comprehensive testing before release
- **Post-launch**: Ongoing monitoring and user feedback

**Developer Assistance Package (Approach #5) as Born Accessible Exemplar**:
- Embeds accessibility from project conception, not bolted on at end
- Prevents barriers through design and code review, not just finding them post-development
- "Shift-left" approach: catch issues when cheapest and easiest to fix
- On-demand testing throughout development enables rapid iteration
- Educates external developers, building capacity beyond CNIB
- MyCNIB application: Accessibility integrated throughout, not retrofitted after launch

### Vendor Accountability

Testing is key mechanism for vendor accountability:
- **Pre-purchase**: Level 2 testing validates vendor VPAT claims
- **Contract requirement**: Vendor must pass Level 2 testing
- **Update testing**: Level 1-2 testing before deploying vendor updates
- **Issue tracking**: Document vendor responsiveness to accessibility bugs

**CNIB's National Leadership in Procurement**:
- Sheetal Kocchar (AccessLabs, Head of Accessibility Bob Dodd) leads vendor procurement testing
- CNIB research influenced Accessibility Standards Canada's [Technical Guide on Procurement of Accessible Services](https://accessible.canada.ca/creating-accessibility-standards/technical-guide-procurement-accessible-services)
- National framework adopted by federal government reflects CNIB procurement methodology
- Four-step framework: Define Requirements → Identify Barriers → Gather Information → Develop Requirements
- Vendor assessment standards now include ACRs/VPATs, user testing, conformance testing
- CNIB's internal procurement pain points (e.g., SAP Concur) → research → national guidance
- Sheetal serves on Systems & Technology Subcommittee (S2), bringing procurement expertise to Task Force
- **Impact**: CNIB expertise developed through internal testing → shapes national standards → benefits all Canadian organizations

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
