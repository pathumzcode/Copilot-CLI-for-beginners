# Portfolio Generation Skill

## Purpose

This skill provides structured instructions for generating or updating a professional, responsive personal portfolio website from a user's verified CV, profile information, or other user-provided professional content.

The portfolio must use:

* The user's **verified CV/profile information as the source of truth**
* The supplied **visual reference as design direction**

The result should be an original, polished personal portfolio rather than a copy of the reference website.

The skill must ensure that portfolio content is:

* Accurate
* Professional
* Responsive
* Accessible
* Visually strong
* Maintainable
* Based only on information provided or explicitly verified by the user

---

# Core Principles

Follow these principles throughout the entire process:

1. Use the user's CV or verified profile information as the primary source.
2. Use the provided visual reference only as visual inspiration.
3. Never use information from the visual reference as if it belongs to the user.
4. Never invent personal, educational, professional, project, certification, technical, achievement, or experience information.
5. Do not assume missing information.
6. Ask the user to verify extracted CV information before substantial portfolio generation or modification.
7. Preserve the existing project structure and functionality whenever possible.
8. Do not delete important files without user approval.
9. Prefer targeted modifications instead of unnecessary rewrites.
10. Use clean, maintainable, readable code.
11. Follow semantic HTML and accessibility best practices.
12. Ensure responsive behavior across desktop, tablet, and mobile.
13. Keep the visual design consistent across all sections.
14. Do not copy branding, names, text, images, or proprietary content from the reference.
15. Review all generated content before considering the portfolio complete.
16. The user's explicit instructions always override general design recommendations.

---

# Visual Reference Direction

The visual reference represents the desired **visual language**, not the user's personal information.

Use it as inspiration for a:

* Modern editorial portfolio
* Bold personal-brand presentation
* Dark/light section contrast
* Minimal but expressive layout
* Strong typography
* Rounded cards and containers
* High visual hierarchy
* Premium presentation
* Clean responsive design

The reference should influence:

* Layout language
* Spacing
* Typography
* Cards
* Section transitions
* Visual rhythm
* Accent treatment

The actual content must come only from verified user information.

## Visual Characteristics

### 1. Dark + Light Section Contrast

Possible section treatment:

* Light/off-white hero
* Dark content sections
* Light card areas
* Dark CTA section
* Bright accent areas

Do not blindly reproduce the exact colors from the reference.

Choose a coherent palette suitable for a personal portfolio.

### 2. Bright Accent Color

A bright accent inspired by the reference may be used for:

* Important keywords
* Highlighted headings
* Buttons
* Icons
* Decorative shapes
* Active navigation states
* Small labels
* Section markers

Use the accent intentionally rather than excessively.

### 3. Large Bold Typography

Use strong typography for:

* Hero headings
* Section headings
* Highlighted keywords
* Short supporting text
* Small uppercase labels

Do not sacrifice readability for oversized typography.

### 4. Rounded Containers

Use consistent rounded styling for:

* Navigation
* Buttons
* Skill cards
* Project cards
* Certification cards
* Experience cards
* Profile information
* Contact elements

Maintain a consistent border-radius system.

### 5. Pill-Shaped UI

Use pills for:

* Navigation links
* Skill tags
* Technology tags
* Category labels
* Status indicators
* Small metadata

Do not make every UI element pill-shaped.

### 6. Editorial / Asymmetrical Layouts

Where appropriate, use:

* Two-column layouts
* Unequal columns
* Image + text sections
* Offset cards
* Overlapping decorative elements
* Large visual blocks
* Alternating layouts

All asymmetrical layouts must remain usable and responsive.

### 7. Image Treatment

Use only user-provided or appropriately licensed assets.

Possible treatments:

* Rounded profile images
* Circular profile images
* Cropped project previews
* Large hero images
* Project screenshots
* Image cards with captions
* Black-and-white project imagery

Never create or imply a fake profile photograph.

If no profile image is available, use a neutral placeholder or omit the image.

### 8. Decorative Elements

Decorative elements may include:

* Stars
* Dots
* Lines
* Circles
* Geometric shapes
* Accent marks

Use them sparingly.

Decorations must not interfere with readability or accessibility.

### 9. Section Rhythm

A possible portfolio structure is:

1. Hero
2. Quick facts
3. About
4. Skills
5. Projects
6. Education
7. Experience
8. Certifications
9. Achievements
10. Community / Activities
11. CTA / Contact
12. Footer

Only include sections supported by verified information.

---

# Portfolio Content Rules

## Source of Truth

Allowed sources:

1. User-provided CV
2. User-provided profile information
3. Information explicitly confirmed by the user
4. User-provided links when their content is available and appropriate

If sources conflict:

1. Ask the user to clarify.
2. Do not silently choose one version.
3. Do not invent a resolution.

## Never Invent

Never create:

* Fake projects
* Fake companies
* Fake job titles
* Fake certifications
* Fake achievements
* Fake skills
* Fake educational qualifications
* Fake professional experience
* Fake awards
* Fake clients
* Fake statistics
* Fake testimonials
* Fake social links
* Fake contact information
* Fake GitHub repositories
* Fake contribution numbers
* Fake employment dates

If information is missing:

* Omit it, or
* Ask the user for the missing information.

---

# Workflow

## Phase 1 — Inspect Available Files and Project

Before making changes:

1. Inspect the existing project structure.
2. Identify the technology stack.
3. Identify the entry point.
4. Identify existing pages/components.
5. Identify existing CSS/design system.
6. Identify existing assets.
7. Identify the provided CV/profile document.
8. Identify the supplied visual reference if available.
9. Determine which existing functionality must be preserved.

Do not make destructive changes during inspection.

---

# Phase 2 — Analyze the CV

Extract relevant information including, when available:

## Personal Information

* Full name
* Preferred display name
* Professional title
* Short introduction
* About/profile summary
* Career objective

## Education

* Institution
* Degree/programme
* Specialization
* Academic dates
* Relevant verified achievements

## Technical Skills

* Programming languages
* Frameworks
* Libraries
* Databases
* Cloud technologies
* DevOps technologies
* Developer tools
* AI/ML technologies
* Design tools
* Other verified skills

## Projects

* Project name
* Description
* Purpose/problem
* Technologies
* Features
* Project links
* GitHub links
* Live demo links
* Available screenshots

## Experience

* Organisation
* Role
* Dates
* Responsibilities
* Verified achievements

## Certifications

* Certification name
* Issuer
* Date
* Credential URL

## Achievements

* Awards
* Competitions
* Recognition
* Verified accomplishments

## Community / Activities

* Student organizations
* Ambassador roles
* Community contributions
* Events
* Leadership roles
* Workshops
* Volunteering
* Extra-curricular activities

## Professional Links

* GitHub
* LinkedIn
* Portfolio
* Other verified professional links

## Contact Information

Only use contact information intentionally provided for portfolio use.

---

# Phase 3 — Verify CV Information

After extracting information, present a concise verification summary to the user.

Example:

## Personal Information

* Name:
* Professional title:
* Introduction:

## Education

* Institution:
* Programme:
* Dates:

## Skills

* Languages:
* Frameworks:
* Databases:
* Tools:
* Cloud:
* AI/ML:

## Projects

* Project:
* Description:
* Technologies:
* Link:

## Certifications

* Certification:
* Issuer:
* Date:

## Experience

* Organisation:
* Role:
* Dates:
* Responsibilities:

## Community / Activities

* Organisation:
* Role:
* Activities:

## Links

* GitHub:
* LinkedIn:
* Other:

Ask the user to confirm or correct the extracted information.

Do not begin substantial portfolio generation until the user confirms the information.

If the user corrects information, the corrected information becomes the new source of truth.

---

# Phase 4 — Plan the Portfolio

After CV information is verified, create an implementation plan covering:

* Portfolio structure
* Required sections
* Technology stack
* Files to create
* Files to modify
* Existing files to preserve
* Design approach
* Color approach
* Typography
* Navigation
* Responsive behavior
* Accessibility
* Images and assets
* Animation approach
* Project presentation
* Existing functionality that must remain unchanged

The plan must explicitly explain how the supplied visual reference will be adapted into an original personal portfolio.

Do not implement the plan until the user approves it.

---

# Recommended Portfolio Structure

Only include sections supported by verified information.

## 1. Navigation

Create a clean navigation bar inspired by the rounded/pill navigation style.

Possible links:

* Home
* About
* Skills
* Projects
* Education
* Experience
* Certifications
* Achievements
* Activities
* Contact

Do not create links for sections that do not exist.

### Mobile Navigation

* Use a compact navigation menu.
* Support keyboard interaction.
* Provide visible focus states.
* Allow opening and closing without relying on hover.
* Prevent horizontal overflow.

---

# 2. Hero

The hero should communicate:

* Who the user is
* What they do/study
* Main professional direction
* Short supporting statement
* Relevant CTA buttons

Possible CTAs:

* View Projects
* Download CV
* Contact Me
* GitHub
* LinkedIn

Only include CTAs supported by verified links/files.

Use:

* Large typography
* Strong accent emphasis
* Rounded containers
* Editorial layout
* Appropriate imagery

---

# 3. Quick Facts / Stats

Only display verified facts.

Possible facts:

* Number of verified projects
* Certifications
* Technologies
* Years of experience
* Community roles

Never create impressive-looking statistics.

If there are insufficient verified statistics, omit this section.

---

# 4. About

Use the user's verified professional or academic introduction.

Keep the writing:

* Concise
* Natural
* Factual
* Easy to scan

Do not exaggerate limited CV information.

---

# 5. Skills

Group verified skills logically.

Possible categories:

* Programming Languages
* Frameworks
* Databases
* Cloud
* DevOps
* Developer Tools
* AI / ML
* Design Tools
* Other

Use rounded tags or cards inspired by the reference.

Only list verified skills.

---

# 6. Projects

Projects should be a major portfolio section.

Each project card may contain:

* Project name
* Short description
* Purpose/problem
* Technologies
* Key features
* GitHub link
* Live demo
* Relevant image/screenshot

Use visually distinct cards.

Never create unsupported project claims.

---

# 7. Education

Display:

* Institution
* Degree/programme
* Specialization
* Dates
* Relevant verified achievements

Use a timeline, cards, or editorial layout.

---

# 8. Experience

Display:

* Organisation
* Position
* Dates
* Responsibilities
* Verified achievements

Do not classify community or volunteer activities as employment unless the CV explicitly identifies them as employment.

---

# 9. Certifications and Achievements

Use compact cards containing:

* Certification/achievement name
* Issuing organization
* Date
* Credential URL where available

Use accent highlights and rounded cards.

---

# 10. Community / Activities

If supported by verified information, show:

* Student organizations
* Ambassador roles
* Community contributions
* Events
* Leadership
* Volunteering
* Workshops

Clearly distinguish community activities from formal employment.

---

# 11. Contact / CTA

Create a strong closing section inspired by the reference.

Possible content:

* Short invitation to connect
* Email
* LinkedIn
* GitHub
* Other verified professional links

Do not expose private information unless intentionally provided for portfolio use.

---

# 12. Footer

Include:

* Name/brand
* Short professional description
* Navigation
* Verified social links
* Copyright

Never add fake social accounts or contact information.

---

# Design System

Create a consistent design system before styling the complete portfolio.

## Colors

Use a palette inspired by the reference:

* Dark background
* Warm off-white/light background
* Bright accent
* High-contrast primary text
* Muted secondary text

The exact colors can be adapted to the user's personal brand.

Always maintain sufficient contrast.

## Typography

Use:

* Large bold display headings
* Strong section headings
* Readable body text
* Small metadata labels
* Consistent font weights

Prefer one primary typeface with an optional display typeface.

Avoid excessive font families.

## Spacing

Use a consistent spacing scale.

Avoid:

* Crowded sections
* Excessive empty space
* Random margins
* Inconsistent card padding

## Borders and Radius

Maintain a consistent radius system for:

* Cards
* Buttons
* Images
* Navigation
* Inputs

## Buttons

Buttons must have:

* Clear labels
* Strong contrast
* Hover state
* Focus state
* Active state where appropriate
* Keyboard accessibility

Prefer precise CTA labels over vague labels.

---

# Responsive Requirements

The portfolio must work on:

* Large desktop
* Standard desktop
* Tablet
* Mobile
* Small mobile

## Desktop

Use editorial/asymmetrical layouts where appropriate.

## Tablet

Adjust:

* Font sizes
* Grid columns
* Horizontal padding
* Image sizes

Maintain hierarchy.

## Mobile

Convert multi-column layouts into:

* Single-column sections
* Stacked cards
* Compact navigation

Use horizontal scrolling only when genuinely appropriate.

Check:

* Long project names
* URLs
* Buttons
* Images
* Navigation
* Cards
* Headings
* Contact elements

Prevent horizontal page overflow.

---

# Accessibility Requirements

Ensure:

* Semantic HTML
* Logical heading hierarchy
* Keyboard navigation
* Visible focus states
* Descriptive link text
* Meaningful image alt text
* Adequate color contrast
* Proper form labels
* Accessible mobile navigation
* Reduced-motion support

Decorative elements must not interfere with screen readers.

Do not communicate important information using color alone.

---

# Animation Requirements

Animations must be subtle and purposeful.

Possible animations:

* Section fade-in
* Small card hover movement
* Button transitions
* Navigation transitions
* Image reveal
* Progressive section appearance

Avoid:

* Excessive parallax
* Constant motion
* Distracting backgrounds
* Long entrance animations
* Motion that harms readability

Respect:

```css
@media (prefers-reduced-motion: reduce)
```

---

# Technical Requirements

Use the project's existing technology stack whenever possible.

## HTML

* Use semantic HTML.
* Maintain logical structure.
* Use appropriate headings.
* Add meaningful alt text.
* Make links and buttons clearly identifiable.

## CSS

* Use organized styles.
* Prefer reusable classes/components.
* Use CSS variables where appropriate.
* Create responsive layouts.
* Avoid unnecessary duplicated styles.
* Avoid excessive fixed dimensions.
* Prevent horizontal overflow.

## JavaScript

Use JavaScript only when necessary.

Keep functionality:

* Simple
* Maintainable
* Accessible
* Error-tolerant

Avoid unnecessary dependencies.

## Frameworks

If the existing project uses:

* React
* Vue
* Angular
* Next.js
* Spring Boot templates
* Another framework

Then:

1. Preserve the framework.
2. Reuse existing components where practical.
3. Follow project conventions.
4. Do not migrate frameworks unless explicitly requested.

---

# Existing Project Protection

When working inside an existing project:

1. Inspect the structure first.
2. Preserve working functionality.
3. Do not unnecessarily replace existing files.
4. Do not delete important files.
5. Reuse existing components where appropriate.
6. Make targeted modifications.
7. Preserve existing routes and APIs unless changes are required.
8. Preserve existing integrations.
9. Explain significant structural changes before applying them.
10. Avoid replacing working code merely for visual redesign.

If a file contains both portfolio UI and unrelated functionality, modify only the required portion.

---

# Image and Asset Rules

Use:

* User-provided profile photos
* User-provided project screenshots
* User-provided logos
* User-provided certification graphics
* Appropriate open assets when licensing permits

Do not:

* Copy images from the reference
* Use the reference person's photograph as the user's photo
* Claim stock imagery represents the user
* Download copyrighted assets without permission
* Invent project screenshots

When an asset is missing:

* Use a neutral placeholder when appropriate, or
* Omit the visual.

---

# Content Writing Style

Portfolio copy must be:

* Professional
* Clear
* Concise
* Human
* Confident but factual
* Easy to scan

Avoid:

* Excessive buzzwords
* Fake marketing claims
* Unverified superlatives
* Generic filler
* Overly long descriptions
* Unsupported claims such as "expert"

Prefer specific factual statements.

Example:

Bad:

> I am a world-class developer who creates revolutionary solutions.

Better:

> Information Technology undergraduate interested in software development, cloud technologies, and AI/ML.

Only use the second example if it matches verified user information.

---

# Review Process

After generating or updating the portfolio, review the result.

## Content Review

Check:

* Names
* Dates
* Education
* Institutions
* Projects
* Skills
* Certifications
* Achievements
* Experience
* Activities
* Professional links
* Contact information

## UI/UX Review

Check:

* Visual hierarchy
* Typography
* Spacing
* Contrast
* Navigation
* CTA clarity
* Card consistency
* Section transitions
* Overall visual balance

## Responsive Review

Check:

* Desktop
* Tablet
* Mobile
* Small mobile
* Horizontal overflow
* Navigation behavior
* Image scaling
* Card stacking

## Accessibility Review

Check:

* Heading structure
* Keyboard navigation
* Focus states
* Alt text
* Link labels
* Contrast
* Form accessibility
* Reduced-motion behavior

## Technical Review

Check:

* HTML quality
* CSS quality
* JavaScript quality
* Broken links
* Missing assets
* Button functionality
* Browser console errors
* Build errors
* Runtime errors

---

# Five-Improvement Rule

After the review, identify the **five most important improvements**.

For every improvement provide:

1. Problem
2. Why it matters
3. Proposed solution
4. Files/components affected

Do not automatically apply these improvements.

Present them to the user and wait for approval.

---

# Improvement Process

After the user approves improvements:

1. Apply only the approved improvements.
2. Preserve existing functionality.
3. Do not invent new information.
4. Avoid unnecessary rewrites.
5. Review modified files.
6. Test the result again.
7. Report what was changed.

---

# Final Validation

Before considering the portfolio complete, verify:

* Website loads correctly.
* Build succeeds.
* All relevant sections are present.
* Content matches verified CV information.
* Navigation works.
* Buttons work.
* Professional links work.
* Images and assets load correctly.
* No important files were accidentally removed.
* Website is responsive.
* Desktop layout works.
* Tablet layout works.
* Mobile layout works.
* No obvious accessibility issues remain.
* No unsupported information has been added.
* No obvious broken links remain.
* No missing assets remain.
* No unexpected browser console errors remain.
* No unnecessary dependencies were introduced.
* Existing project functionality still works.
* Visual language is consistent with the supplied reference without copying it.

---

# User Approval Rules

The user must remain in control of significant changes.

## Before Implementation

Follow this exact order:

1. Analyze available information.
2. Inspect the existing project.
3. Extract CV information.
4. Present extracted CV information.
5. Request user verification.
6. Create implementation plan.
7. Present the plan.
8. Wait for user approval.
9. Implement the approved plan.

Do not make significant implementation changes before approval.

## Before Applying Review Improvements

Follow this order:

1. Review the portfolio.
2. Identify five important improvements.
3. Present the improvements.
4. Wait for approval.
5. Apply only approved improvements.
6. Test the result.

---

# Important Agent Behavior

When the user provides both a CV and a visual reference:

* The **CV determines what the portfolio says**.
* The **visual reference determines how the portfolio feels and is structured**.
* The user's explicit instructions override general design suggestions.
* Never use reference content as the user's personal content.
* Never copy fictional names, statistics, companies, testimonials, services, or contact details from the reference.
* Replace reference content with verified personal information.
* Adapt the design into a personal portfolio rather than a business/agency website.
* Keep the final result original while preserving the requested visual characteristics.

If the user requests a portfolio without providing a CV, first request the CV or verified professional information unless enough verified information has already been explicitly supplied.

---

# Expected Outcome

The final portfolio should:

* Accurately represent the user's real background.
* Use verified CV/profile information as the content source.
* Use the supplied reference as visual inspiration.
* Have a bold, modern, editorial visual identity.
* Use dark/light contrast appropriately.
* Use a strong accent color appropriately.
* Contain rounded cards and pill elements.
* Use strong typography.
* Have clear visual hierarchy.
* Be responsive across devices.
* Be accessible.
* Preserve existing project functionality.
* Contain no fabricated information.
* Use maintainable code.
* Be production-ready.
* Remain original rather than copying the reference design.
