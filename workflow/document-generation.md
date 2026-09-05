# Document Generation

## Purpose

Document generation is the production stage of the RicFit AI workflow.

The system does not simply generate a resume. It converts the completed candidate analysis, career positioning, transferable skills assessment, and job targeting decisions into a structured nine-document remote employment package.

The objective is to produce professional, consistent, copy-ready materials while maintaining factual accuracy and preserving the candidate's real experience.

The document generation stage follows the analysis and positioning stages rather than operating as an independent writing task.

---

## Production Sequence

The workflow uses a controlled nine-document sequence:

1. ATS Resume
2. Generic Cover Letter
3. ZipRecruiter Profile Content
4. ZipRecruiter Setup Guide
5. LinkedIn Profile Content
6. LinkedIn Setup Guide
7. Candidate Snapshot
8. Remote Job Success Playbook
9. Automated Remote Job Package User Guide

The sequence is intentional. Certain documents depend on information established in earlier documents and workflow stages.

The actual workflow requires ZipRecruiter Profile Content to be completed before the ZipRecruiter Setup Guide, and LinkedIn Profile Content to be completed before the LinkedIn Setup Guide.

This creates a controlled production flow rather than a collection of unrelated documents.

The nine-document sequence is defined in the underlying RicFit workflow specification. :contentReference[oaicite:0]{index=0}

---

## Document 1: ATS Resume

The ATS Resume is the primary professional positioning document.

Its purpose is to present the candidate's experience, education, skills, transferable capabilities, and career direction in a professional format that can be used for remote job applications.

The resume is designed to:

- Clearly communicate the candidate's professional value
- Align experience with targeted remote roles
- Translate legitimate transferable skills into workplace-relevant language
- Remain compatible with applicant tracking systems
- Maintain factual accuracy
- Avoid unsupported claims or fabricated experience
- Provide a consistent foundation for the rest of the application package

The resume is based on the candidate information and positioning decisions established during the earlier workflow stages.

---

## Document 2: Generic Cover Letter

The Generic Cover Letter provides a reusable professional narrative that supports the candidate's job applications.

It connects:

- Candidate background
- Transferable skills
- Career direction
- Target role categories
- Professional positioning
- Interest in remote work

The cover letter must remain consistent with the resume and must not introduce unsupported employers, responsibilities, achievements, certifications, metrics, or technical experience.

It functions as a reusable foundation that can be adapted for individual applications when appropriate.

---

## Document 3: ZipRecruiter Profile Content

ZipRecruiter Profile Content converts the candidate's professional positioning into copy-ready profile information for the ZipRecruiter platform.

The content is designed to support the candidate's job search by presenting:

- Professional identity
- Career direction
- Relevant experience
- Transferable skills
- Target roles
- Professional summary information
- Relevant profile keywords

The profile content is generated before the ZipRecruiter Setup Guide because the setup guide depends on the completed profile information.

This sequencing prevents the candidate from receiving setup instructions before the actual profile content has been established.

---

## Document 4: ZipRecruiter Setup Guide

The ZipRecruiter Setup Guide explains how the candidate should implement the previously generated profile content.

The guide is designed to make the setup process practical and easy to follow.

It can address areas such as:

- Profile completion
- Resume upload
- Professional information
- Job preferences
- Target roles
- Job alerts
- Application workflow
- Recruiter communication
- Search configuration

The guide is implementation-oriented rather than another profile-writing document.

The profile content therefore comes first, followed by instructions for putting that content into use.

---

## Document 5: LinkedIn Profile Content

LinkedIn Profile Content translates the candidate's professional positioning into a structured LinkedIn presence.

Depending on the candidate's available information, the content can include:

- Headline
- About section
- Experience
- Education
- Skills
- Certifications
- Relevant keywords
- Job-search positioning
- Open to Work or related job preferences where applicable

The content must remain consistent with the ATS Resume and other application materials.

LinkedIn is treated as part of the same professional positioning system rather than as a completely separate identity.

---

## Document 6: LinkedIn Setup Guide

The LinkedIn Setup Guide provides implementation instructions for the LinkedIn profile content.

Its purpose is to help the candidate correctly apply the previously generated profile information and configure the profile for the intended remote job search.

The guide can cover:

- Applying profile content
- Profile configuration
- Skills and keywords
- Job preferences
- Open to Work settings where applicable
- Job search configuration
- Application workflow
- Profile maintenance

The LinkedIn Profile Content must be established before the Setup Guide so that implementation instructions correspond to the actual candidate materials.

---

## Document 7: Candidate Snapshot

The Candidate Snapshot provides a concise reference view of the candidate's professional positioning.

It consolidates important information such as:

- Candidate background
- Career direction
- Target roles
- Transferable skills
- Relevant experience
- Professional strengths
- Remote work direction
- Income target when provided

The snapshot functions as a quick-reference document for understanding the candidate's positioning without reviewing the complete application package.

It also provides a useful consistency reference when reviewing the other documents.

---

## Document 8: Remote Job Success Playbook

The Remote Job Success Playbook provides practical guidance for executing the job search.

The document moves beyond document creation and addresses how the candidate can use the completed package effectively.

Depending on the candidate's circumstances, the playbook can address:

- Job board strategy
- Application strategy
- Quality versus application volume
- Job targeting
- Follow-up
- Interview preparation
- Candidate positioning
- Compensation considerations
- Application tracking
- Remote job search practices
- Scam awareness

The purpose is to turn the completed employment package into an operating process for the candidate's remote job search.

---

## Document 9: Automated Remote Job Package User Guide

The Automated Remote Job Package User Guide explains how the overall system and generated package are intended to be used.

It provides the candidate or operator with a practical reference for:

- Understanding the package
- Following the workflow
- Using the generated documents
- Continuing the production sequence
- Applying the materials to the job search
- Maintaining consistency
- Understanding the role of automation and human review

The guide represents the final handoff from document production to actual system use.

---

## Production Dependencies

Document generation depends on information established earlier in the workflow.

The production chain can be represented as:

```text
Candidate Information
        ↓
Input Analysis
        ↓
Career Positioning
        ↓
Job Targeting
        ↓
Document Generation
        ↓
Consistency Check
        ↓
Quality Control
        ↓
Human Review
        ↓
Final Employment Package


This structure prevents the AI from generating documents before the candidate's professional direction has been established.

The document stage is therefore a downstream production function rather than the starting point of the workflow.

Information Carry-Forward

Each document carries forward the approved information established during the earlier stages.

Important information that must remain consistent includes:

Candidate name
Contact information
Location
Education
Certifications
Employment history
Job titles
Employment dates
Skills
Professional positioning
Target job categories
Remote work direction
Income target when provided

The system is designed to prevent individual documents from developing conflicting versions of the same candidate.

For example, a target role identified during career positioning should not suddenly change between the resume, LinkedIn profile, and job-search playbook without a deliberate update to the candidate's positioning.

Document Generation Rules

The generated documents should be:

Professional
Clear
Structured
Copy-ready
Easy to implement
Appropriate for the intended platform
Consistent with the candidate's positioning
Suitable for Google Docs and similar document workflows
Focused on practical job-search use

The system prioritizes useful output over generic AI-generated prose.

Documents should provide specific, actionable content that the candidate can actually use.

Anti-Fabrication Control

Document generation operates under a strict factual accuracy rule.

The system must not invent:

Employers
Employment history
Responsibilities
Certifications
Achievements
Performance metrics
Software experience
Technical experience
Professional qualifications
Other unsupported credentials

The system can improve structure, wording, positioning, and presentation, but it cannot create professional experience that the candidate does not actually have.

The underlying positioning rule is to make real experience as relevant as possible without misrepresenting it.

Transferable Skills in Document Production

Sports and other nontraditional experience can be translated into workplace-relevant transferable skills when supported by the candidate's actual background.

Examples can include:

Leadership
Communication
Teamwork
Discipline
Accountability
Time management
Decision making
Adaptability
Working under pressure
Consistency
Coachability
Responsibility

These skills may be incorporated into professional documents when they are supported by the candidate's actual experience.

The purpose is translation and positioning, not fabrication.

AI and Human Responsibilities

AI supports the production process by helping with:

Information structuring
Professional wording
Career positioning
Transferable-skill translation
Document drafting
Standardization
Cross-document consistency
Quality-control support

Human review remains essential.

The human operator remains responsible for:

Confirming factual accuracy
Reviewing professional positioning
Verifying candidate information
Approving final documents
Identifying information gaps
Making judgment calls where context cannot be reliably determined by AI

The system therefore follows a human-in-the-loop model rather than treating AI output as automatically final.

Workflow State Management

The RicFit workflow uses a controlled continuation mechanism.

The NEXT DOCUMENT command allows the operator to continue from the current production stage rather than restarting the entire workflow.

This supports a sequential production process where the system knows which document is being generated and which document should follow.

The mechanism is particularly useful when producing a complete candidate package across multiple sessions or production steps.

The workflow state concept is part of the underlying system architecture.

Consistency Control

After documents are generated, the package should be reviewed as a complete system rather than as individual files.

The consistency review checks whether information remains aligned across:

ATS Resume
Cover Letter
ZipRecruiter Profile
ZipRecruiter Setup Guide
LinkedIn Profile
LinkedIn Setup Guide
Candidate Snapshot
Remote Job Success Playbook
User Guide

The objective is to ensure that the candidate presents one coherent professional identity across the entire job-search ecosystem.

Updating the Package

Candidate information can change over time.

Examples include:

New employment
New certifications
New skills
New target roles
Changed income expectations
Updated contact information
Changes in remote-work preferences

When material information changes, affected documents should be reviewed and updated so that the package remains internally consistent.

The workflow should not assume that an old document remains accurate simply because it was previously approved.

Quality Control Handoff

Document generation is not the final step.

Once the nine documents have been produced, the package moves into:

Document Generation
        ↓
Cross-Document Consistency
        ↓
Quality Control
        ↓
Human Approval
        ↓
Final Candidate Package

Quality control verifies that the final package is:

Factually accurate
Internally consistent
Professionally positioned
Aligned with target roles
Free of unsupported claims
Ready for practical use

The final package should only be treated as complete after human review.

Design Objective

The document-generation layer transforms structured candidate intelligence into a complete employment package.

Its value is not simply the ability to generate nine documents.

Its value comes from producing nine connected outputs that share the same factual foundation, professional positioning, career direction, and job-targeting strategy.

This creates a repeatable production system rather than a one-off AI writing exercise.
