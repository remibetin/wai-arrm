---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
# In this first section, do not translate the words before a colon. For example, do not translate "title:". Do translate the text after "title:".

title: "Assigning Tasks and Responsibilities to Roles"
nav_title: "Assigning Tasks and Responsibilities"
lang: en                   # Change "en" to the translated-language shortcode
last_updated: 2026-06-05   # Keep the date of the English version

# translators:        # remove from the beginning of this line and the lines below: "# " (the hash sign and the space)
# - name: "Jan Doe"   # Replace Jan Doe with translator name
# - name: "Jan Doe"   # Replace Jan Doe with name, or delete this line if not multiple translators
# contributors:
# - name: "Jan Doe"   # Replace Jan Doe with contributor name, or delete this line if none
# - name: "Jan Doe"   # Replace Jan Doe with name, or delete this line if not multiple contributors

permalink: /planning/arrm/  # Add the language shortcode to the end, with no slash at the end. For example /path/to/file/fr
ref: /planning/arrm/        # Do not change this

custom_changelog: /planning/arrm/changelog/

# In the footer below:
# Do not translate ACKNOWLEDGEMENTS
# Translate the other words, including "Editors and contributors:"
# Translate the Community Group and Working Group names. Leave the acronyms in English.
footer: >
  <p><strong>Editors and contributors:</strong> See ACKNOWLEDGEMENTS.</p>
  <p>Developed through the <a href="https://www.w3.org/community/arrm/">Accessibility Roles and Responsibilities Mapping (ARRM) Community Group</a> at W3C. Initially developed with the Accessibility Education and Outreach Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>). You are also welcome to join the <a href="https://www.w3.org/community/arrm/">ARRM Community Group</a> to contribute.</p>
---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This resource helps you assign tasks and responsibilities for digital accessibility to appropriate roles early in projects. It is also called Accessibility Roles and Responsibilities Mapping (ARRM).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::options toc_levels="2" /}

{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" class="full" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## Introduction

Different aspects of accessibility are the responsibility of different roles, such as content authors, designers, and developers. Defining each role's responsibilities early helps you implement accessibility more effectively.

{::nomarkdown}
{% include_cached box.html type="start" title="Here is a simplified example" class="simple" %}
{:/}

Different roles contribute to meeting WCAG requirements for headings:
* Content authors are typically responsible for writing the heading text and communicating the heading levels.
* Designers are typically responsible for defining how the headings look.
* Developers are typically responsible for coding or marking up the headings.

{::nomarkdown}
{% include_cached box.html type="end" %}
{:/}

When accessibility is left until late in a project, the responsibility often falls on developers. Then, they may end up handling tasks that are not in their skillset. For example: selecting colors, describing images, and writing headings.

This resource gets your started with assigning responsibilities for accessibility early in projects.

For more guidance on integrating accessibility throughout projects, see [Planning and Managing Web Accessibility](/planning-and-managing/).

## Typical roles and responsibilities

You can use the following lists of roles, tasks, and responsibilities as a starting point.

**[Roles Involved in Accessibility](/planning/arrm/roles/)**
: Describes typical roles that have responsibilities for ensuring accessibility.

**[WCAG Success Criteria Responsibilities](/planning/arrm/wcag-sc/)**
: Provides an approach for assigning which roles have primary, secondary, or contributor responsibilities for meeting each WCAG 2 success criterion.

**[Tasks Involved in Accessibility](/planning/arrm/tasks/)**
: Lists tasks that you can use to <mark>address WCAG requirements</mark> and their role responsibilities. Subsets of the tasks are provided for the following roles:
* [User Experience (UX) Designer Responsibilities](/planning/arrm/user-experience/)
* [Visual Designer Responsibilities](/planning/arrm/visual-designer/)
* [Content Author Responsibilities](/planning/arrm/content-author/)
* [Front-End Developer Responsibilities](/planning/arrm/front-end/)

## Custom roles and responsibilities

Depending on your project and organization, you may want to create your own accessibility roles and responsibilities.

**[Roles and Responsibilities Decision Tree](/planning/arrm/decision-tree/)**
: Walks you through the steps for deciding who is responsible for an accessibility task or for meeting a WCAG success criterion.

## Ownership levels

The resource uses three levels of ownership for accessibility requirements, based on commonly agreed upon [RACI (responsible, accountable, consulted, and informed) matrix principles {% include external.html %}](https://en.wikipedia.org/wiki/Responsibility_assignment_matrix#Key_responsibility_roles_(RACI_model)):

**Primary ownership (P)**
: 
Those who are **accountable** for an accessibility task.

    Typically, primary owners:
    - drive the decision-making process
    - have direct interaction with the secondary owner(s) discussing issues
    - delegate the work to other roles or team members (as needed)
    - lead the task to completion
    - have final sign-off authority (if/when used)
    - are ultimately accountable for the outcome of task or design decisions regardless of when they occur in the process
    
    The primary role is ultimately accountable. There can only be **one primary owner for each task**.
{: #primary}

**Secondary ownership (S)**
: Those who are **responsible** to help complete an accessibility task.

  Secondary owners typically:
  - directly support the primary owner
  - are actively involved in the decision-making process
  - have active interest and participation in the outcomes
  - may work to complete the task
  - ultimately defer final decisions to the primary owner
{: #secondary}

**Contributors (C)**
: Those who need to be **consulted** in order to successfully complete an accessibility task.

    Typically, contributors:
    - are not actively involved in the decision-making process
    - will provide initial input or requirements
    - may be asked to provide additional information as needed to ensure successful task completion

    Contributors may have limited participation by providing initial design input (such as branding guidance or business requirements) with little or no subsequent interaction. In those cases, the communication may be input only with little or no concern of being kept "informed" of the result (relying on the expertise of other owners).
{: #contributor}


{::nomarkdown}
{% include box.html type="start" title="Ownership to RACI Role Mapping" class="" %}
{:/}

Ownership role levels are very similar to the RACI responsibility roles. For those familiar with RACI definitions these can be helpful in understanding ownership levels but are not necessary. Accessibility ownership roles to RACI responsibility can be mapped to ownership levels like this:

-   Primary -> Accountable
-   Secondary -> Responsible
-   Contributor -> Consulted

Since all accessibility ownership roles provide some input to the design they are “informed.”

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## Relation to WCAG {#wcag}

This resource provides practical implementation guidance. It is not a normative interpretation of WCAG.

While its content can help teams move closer to WCAG conformance, it does not replace the normative WCAG specification or the informative Understanding WCAG documents.

## More guidance

Assigning accessibility tasks and responsibilities is one aspect of a broader approach. 

To learn more about implementing accessibility throughout your organization and projects, see [Planning and Managing Web Accessibility](/planning-and-managing/).