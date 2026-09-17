Portfolio Generation Skill

Purpose

This skill provides structured instructions for generating or updating a
professional, responsive personal portfolio website from a user's
verified CV, profile information, or other user-provided professional
content.

The portfolio should use the supplied CV as the source of truth and
the supplied visual reference as the design direction. The result
should feel like a polished personal portfolio, not a copy of the
reference website.

The skill must ensure that portfolio content is accurate, professional,
accessible, responsive, visually strong, and based only on information
provided or explicitly verified by the user.

Core Principles

Follow these principles throughout the portfolio-generation process:

Use the user's CV or verified profile information as the primary
source.

Use the provided design/reference image as visual inspiration, not
as a source of personal content.

Never invent personal, educational, professional, project,
certification, technical, achievement, or experience information.

Do not assume missing information.

Ask the user to verify extracted CV information before generating or
substantially updating the portfolio.

Preserve existing project structure and functionality whenever
possible.

Do not delete important files without user approval.

Prefer targeted changes instead of unnecessary rewrites.

Use clean, maintainable, and readable code.

Follow semantic HTML and accessibility best practices.

Ensure the website is responsive across desktop, tablet, and mobile
devices.

Keep the visual design consistent across all sections.

Do not copy branding, names, text, images, or proprietary content
from the reference design.

Review all generated content before considering the portfolio
complete.

Visual Reference Direction

The user-provided reference image represents the desired visual style
for the portfolio.

Overall Style

Use the reference as inspiration for a:

Modern editorial portfolio

Bold personal-brand presentation

Dark and light section contrast

Minimal but expressive layout

Strong typography

Rounded cards and containers

High visual hierarchy

Premium agency-style presentation

Clean responsive design

The reference should influence the layout language, spacing,
typography, cards, section transitions, and visual rhythm, while the
actual content must come from the user's verified CV.

Visual Characteristics to Reproduce

The design may incorporate:

1. Dark + Light Section Contrast

Use alternating visual sections such as:

Light/off-white hero section

Dark content sections

Light card areas

Dark CTA sections

Bright accent areas

Do not blindly reproduce the exact colors from the reference. Select a
coherent palette appropriate for a personal portfolio.

2. Bright Accent Color

The reference uses a bright yellow accent.

A similar accent can be used for:

Important keywords

Highlighted headings

Buttons

Icons

Decorative shapes

Active navigation states

Small labels

Section markers

The accent color should be used intentionally rather than covering large
amounts of text.

3. Large Bold Typography

Use strong typography for major headings.

Examples of visual treatment:

Large hero heading

Highlighted words inside headings

Short supporting paragraphs

Bold section titles

Small uppercase labels

Strong contrast between heading and body text

Do not sacrifice readability for oversized typography.

4. Rounded Containers

Use rounded visual elements for:

Navigation

Buttons

Skill cards

Project cards

Certification cards

Experience cards

Testimonials or achievements where applicable

Profile information

Contact elements

Keep border-radius values consistent throughout the design.

5. Pill-Shaped UI

The reference uses pill-shaped controls and labels.

Use pills for:

Navigation links

Skill tags

Technology tags

Category labels

Status indicators

Small metadata

Avoid using pills for every element.

6. Editorial / Asymmetrical Layouts

Do not force every section into a simple centered grid.

Where appropriate, use:

Two-column sections

Unequal columns

Image + text layouts

Offset cards

Overlapping decorative elements

Large visual blocks

Alternating image/text alignment

The layout must remain usable and responsive.

7. Image Treatment

Use professional personal/project images supplied by the user.

Possible treatments:

Rounded image containers

Circular profile image

Black-and-white project images

Cropped project previews

Large hero image

Image cards with captions

Never create a fake profile photograph or claim an unrelated person is
the user.

If the user has not provided an image, use a clean visual placeholder
only when appropriate, without implying it is the user's photograph.

8. Decorative Elements

The reference contains simple graphic decorations such as stars and
abstract shapes.

Similar decorative elements can be used sparingly:

Stars

Dots

Lines

Circles

Geometric shapes

Accent marks

Decorations should support the design and must not interfere with
accessibility or readability.

9. Section Rhythm

Create strong visual transitions between sections.

A possible rhythm is:

Hero

Personal introduction / quick facts

About

Skills

Projects

Education / experience

Certifications and achievements

Activities / community

CTA

Footer

Only include sections supported by the user's verified information.

Portfolio Content Rules

Source of Truth

The following sources may be used:

User-provided CV

User-provided profile information

Information explicitly confirmed by the user

User-provided links when their content is available and appropriate
to use

If sources conflict:

Ask the user to clarify.

Do not silently choose one version.

Do not invent a resolution.

Never Invent

Never create:

Fake projects

Fake companies

Fake job titles

Fake certifications

Fake achievements

Fake skills

Fake educational qualifications

Fake professional experience

Fake awards

Fake clients

Fake statistics

Fake testimonials

Fake social links

Fake contact information

Fake GitHub repositories

Fake contribution numbers

Fake employment dates

If information is missing, omit it or ask the user for it.

Workflow

Phase 1 - Inspect Available Files and Project

Before making changes:

Inspect the existing project structure.

Identify the technology stack.

Identify the entry point.

Identify existing pages/components.

Identify existing CSS/design system.

Identify existing assets.

Identify the provided CV or profile document.

Identify the supplied visual reference if available.

Determine which existing functionality must be preserved.

Do not make destructive changes during inspection.

Phase 2 - Analyze the CV

Extract relevant information such as:

Full name

Preferred display name

Professional title

Short introduction

About/profile summary

Career objective

Education

Institutions

Academic dates

Technical skills

Programming languages

Frameworks

Libraries

Databases

Cloud technologies

Developer tools

Projects

Project descriptions

Project technologies

Project links

Work experience

Internships

Volunteer experience

Certifications

Certification providers

Achievements

Awards

Competitions

Community activities

Leadership roles

Extra-curricular activities

GitHub profile

LinkedIn profile

Portfolio links

Other professional links

Contact information

Do not add information that is not available.

After extracting the information, present the extracted information to
the user for verification.

Do not begin substantial portfolio generation until the user confirms
that the extracted information is accurate.

Phase 3 - Verify CV Information

Present a concise verification summary.

Example structure:

Personal Information

Name:

Professional title:

Introduction:

Education

Institution:

Programme:

Dates:

Skills

Languages:

Frameworks:

Databases:

Tools:

Cloud:

Projects

Project:

Description:

Technologies:

Link:

Certifications

Certification:

Issuer:

Date:

Experience

Organisation:

Role:

Dates:

Responsibilities:

Links

GitHub:

LinkedIn:

Other:

Ask the user to confirm or correct the information.

If the user corrects information, use the corrected version as the new
source of truth.

Phase 4 - Plan the Portfolio

After the CV information is verified, create an implementation plan.

The plan should describe:

Portfolio structure

Required sections

Technology stack

Files to create

Files to modify

Existing files to preserve

Design approach

Color approach

Typography

Navigation

Responsive behavior

Accessibility

Images and assets

Animation approach

Project presentation

Existing functionality that must remain unchanged

The plan should explicitly explain how the supplied visual reference
will be adapted to a personal portfolio.

Do not make implementation changes until the user approves the plan.

Recommended Personal Portfolio Structure

Use only sections supported by verified information.

1. Navigation

Create a clean navigation bar inspired by the rounded/pill navigation in
the reference.

Possible links:

Home

About

Skills

Projects

Education

Experience

Certifications

Achievements

Activities

Contact

Do not include links to sections that do not exist.

On mobile:

Use a compact navigation menu.

Ensure keyboard accessibility.

Ensure the menu can be opened and closed without relying only on
hover.

2. Hero

The hero should immediately communicate:

Who the user is

What they do/study

Their main professional direction

One short supporting statement

Relevant CTA buttons

Possible CTAs:

View Projects

Download CV

Contact Me

GitHub

LinkedIn

Only include CTAs supported by available links/files.

Use the reference's large typography, rounded container, visual image
treatment, and strong accent emphasis as inspiration.

3. Quick Facts / Stats

The reference uses a statistics strip.

For a personal portfolio, only show verified facts.

Examples:

Number of projects

Certifications

Technologies

Years of experience

Community roles

Never invent impressive-looking numbers.

If there are not enough verified statistics, omit this section.

4. About

Present the user's verified professional/academic introduction.

Keep the writing concise and natural.

Do not transform limited CV information into exaggerated claims.

5. Skills

Group skills logically.

Possible categories:

Programming Languages

Frameworks

Databases

Cloud

DevOps

Developer Tools

AI / ML

Design Tools

Other

Use compact rounded tags or cards inspired by the reference.

Only list verified skills.

6. Projects

Projects are a major portfolio section.

Each project card should contain, where available:

Project name

Short description

Problem or purpose

Technologies

Key features

GitHub link

Live demo link

Relevant image/screenshot

Use visually distinct cards.

Do not create project claims that are not supported by the CV or user
confirmation.

7. Education

Show:

Institution

Degree/programme

Relevant specialization

Dates

Relevant achievements if verified

Use a timeline, cards, or editorial layout.

8. Experience

Show:

Organisation

Position

Dates

Responsibilities

Verified achievements

Do not turn volunteer/community activities into employment unless the CV
identifies them as employment.

9. Certifications and Achievements

Use compact cards with:

Certification/achievement name

Issuing organization

Date where available

Credential URL where available

Use accent highlights and rounded cards inspired by the reference.

10. Community / Activities

If supported by the CV, show:

Student organizations

Ambassador roles

Community contributions

Events

Leadership

Volunteering

Workshops

Clearly distinguish these from formal employment.

11. Contact / CTA

Create a strong closing section inspired by the reference's final CTA.

Possible content:

Short invitation to connect

Email

LinkedIn

GitHub

Other verified professional links

Do not expose private information unless the user intentionally included
it for the portfolio.

12. Footer

Include:

Name/brand

Short professional description

Navigation

Verified social links

Copyright

Do not add fake social accounts or contact information.

Design System

Create a consistent design system before styling the full page.

Colors

Use a palette inspired by the reference:

Dark background

Warm off-white/light background

Bright accent color

High-contrast text

Muted secondary text

The exact colors may be adjusted to suit the personal brand.

Maintain sufficient contrast for accessibility.

Typography

Use:

Large bold display headings

Strong section headings

Readable body text

Small metadata labels

Consistent font weights

Do not use excessive font families.

Prefer one primary typeface plus an optional display typeface.

Spacing

Use a consistent spacing scale.

Avoid:

Crowded sections

Excessive empty space

Random margins

Inconsistent card padding

Borders and Radius

Use a consistent radius system for:

Cards

Buttons

Images

Navigation

Input fields

Buttons

Buttons should have:

Clear labels

Strong contrast

Hover state

Focus state

Active state where appropriate

Keyboard accessibility

Do not use vague CTA labels when a precise label is possible.

Responsive Requirements

The portfolio must work on:

Large desktop

Standard desktop

Tablet

Mobile

Small mobile screens

Desktop

Use the reference's editorial/asymmetrical layout where appropriate.

Tablet

Reduce:

Font sizes

Grid columns

Horizontal padding

Image sizes

Maintain hierarchy.

Mobile

Convert multi-column layouts into:

Single-column sections

Horizontally scrollable elements only when appropriate

Stacked cards

Compact navigation

Avoid horizontal page overflow.

Check:

Long project names

Long URLs

Buttons

Images

Navigation

Cards

Headings

Contact forms

Accessibility Requirements

Ensure:

Semantic HTML

Logical heading hierarchy

Keyboard navigation

Visible focus states

Descriptive link text

Meaningful image alt text

Adequate color contrast

Form labels

Accessible mobile navigation

Reduced-motion support where animations exist

Decorative elements should not interfere with screen readers.

Do not communicate important information using color alone.

Animation Requirements

Animations should be subtle and purposeful.

Possible animations:

Fade-in on section entry

Small card movement on hover

Button transitions

Navigation transitions

Image reveal

Progressive section appearance

Avoid:

Excessive parallax

Constant motion

Distracting background animations

Long entrance animations

Animations that make the website difficult to read

Respect prefers-reduced-motion.

Technical Requirements

Use the project's existing technology stack whenever possible.

HTML

Use semantic HTML.

Maintain logical structure.

Use appropriate headings.

Add meaningful alt text.

Ensure links and buttons are clearly identifiable.

CSS

Use organized styles.

Prefer reusable classes/components.

Use CSS variables for the design system where appropriate.

Create responsive layouts.

Avoid unnecessary duplicated styles.

Avoid excessive fixed dimensions.

Prevent horizontal overflow.

JavaScript

Use JavaScript only where required.

Keep functionality:

Simple

Maintainable

Accessible

Error-tolerant

Avoid unnecessary dependencies.

Frameworks

If the existing project uses React, Vue, Angular, Next.js, Spring Boot
templates, or another framework:

Preserve the existing framework.

Reuse existing components where practical.

Follow the existing project conventions.

Do not migrate frameworks unless the user explicitly requests it.

Existing Project Protection

When working inside an existing project:

Inspect the existing structure first.

Preserve working functionality.

Do not unnecessarily replace existing files.

Do not delete important files.

Reuse existing components where appropriate.

Make targeted modifications.

Preserve existing routes and APIs unless changes are required.

Preserve existing integrations.

Explain significant structural changes before applying them.

Avoid replacing working code merely to achieve a visual redesign.

If a file contains both portfolio UI and unrelated application
functionality, modify only the required portion.

Image and Asset Rules

Use:

User-provided profile photos

User-provided project screenshots

User-provided logos

User-provided certification graphics

Appropriate open assets when licensing permits

Do not:

Copy images from the reference design

Use the reference person's photograph as the user's photograph

Claim stock imagery represents the user

Download copyrighted assets without permission

Invent project screenshots

When an asset is missing, use a neutral placeholder or omit the visual
rather than fabricating it.

Content Writing Style

Portfolio copy should be:

Professional

Clear

Concise

Human

Confident but factual

Easy to scan

Avoid:

Excessive buzzwords

Fake marketing claims

Unverified superlatives

Generic filler paragraphs

Overly long descriptions

Claims such as "expert" unless verified or explicitly stated by the
user

Prefer specific factual statements.

For example:

Bad: > "I am a world-class developer who creates revolutionary
solutions."

Better: > "Information Technology undergraduate interested in software
development, cloud technologies, and AI/ML."

The second example must still be used only if it matches verified user
information.

Review Process

After generating or updating the portfolio, perform a review covering:

Content

Names

Dates

Education

Institutions

Projects

Skills

Certifications

Achievements

Experience

Activities

Professional links

Contact information

UI/UX

Visual hierarchy

Typography

Spacing

Contrast

Navigation

CTA clarity

Card consistency

Section transitions

Overall visual balance

Responsive Design

Check:

Desktop

Tablet

Mobile

Small mobile

No horizontal overflow

Navigation behavior

Image scaling

Card stacking

Accessibility

Check:

Heading structure

Keyboard navigation

Focus states

Alt text

Link labels

Contrast

Form accessibility

Reduced-motion behavior

Technical Quality

Check:

HTML quality

CSS quality

JavaScript quality

Broken links

Missing assets

Button functionality

Browser console errors

Build errors

Runtime errors

Five-Improvement Rule

After the review, identify the five most important improvements.

For each improvement provide:

Problem

Why it matters

Proposed solution

Files/components affected

Do not automatically apply the improvements.

Present the recommendations to the user and wait for approval.

Improvement Process

After the user approves improvements:

Apply only the approved improvements.

Preserve existing functionality.

Do not invent new information.

Avoid unnecessary rewrites.

Review the modified files.

Test the result again.

Report what was changed.

Final Validation

Before considering the portfolio complete, verify:

Website loads correctly.

Build succeeds.

All relevant sections are present.

Content matches the verified CV.

Navigation works.

Buttons work.

Professional links work.

Images and assets load correctly.

No important files were accidentally removed.

Website is responsive.

Layout works on desktop, tablet, and mobile.

No obvious accessibility issues remain.

No unsupported information has been added.

No obvious broken links remain.

No missing assets remain.

No unexpected browser console errors remain.

No unnecessary dependencies were introduced.

Existing project functionality still works.

The visual language is consistent with the supplied reference
without copying it.

User Approval Rules

The user must remain in control of significant changes.

Before making implementation changes:

Analyze the available information.

Inspect the existing project.

Extract CV information.

Present the extracted CV information.

Request verification.

Create an implementation plan.

Present the plan.

Wait for approval.

Implement the approved plan.

Before applying review improvements:

Review the portfolio.

Identify the five most important improvements.

Present the improvements.

Wait for approval.

Apply the approved improvements.

Test the result.

Do not blindly make significant changes without user approval.

Important Agent Behavior

When the user provides both a CV and a visual reference:

The CV determines what the portfolio says.

The visual reference determines how the portfolio should feel and
be structured.

The user's explicit instructions override general design
suggestions.

Never use information from the visual reference as if it belonged to
the user.

Never copy the reference's fictional names, statistics, company
information, testimonials, services, or contact details.

Replace all reference content with verified personal information.

Adapt the design into a personal portfolio rather than creating a
business/agency website.

Keep the final result original while preserving the requested visual
characteristics.

If the user asks for a portfolio directly without providing a CV, first
request the CV or verified professional information unless enough
verified information has already been explicitly supplied.

Expected Outcome

The final result should be a polished personal portfolio website that:

Accurately represents the user's real background.

Uses the verified CV as its content source.

Uses the supplied reference image as visual inspiration.

Has a bold, modern, editorial visual identity.

Uses dark/light contrast and a strong accent appropriately.

Contains rounded cards, pill elements, strong typography, and
structured visual sections.

Is responsive across devices.

Is accessible.

Preserves existing project functionality.

Contains no fabricated information.

Is maintainable and production-ready.
