# Professional Program Content Model

## Outline

### Required fields

* Title
* Course code
* Topic
* Listing intro
* Price
* Dates
* Body
* Sponsor
* Salesforce ID
* Program instructors
* Format
* Delivery
* Related programs \(implicit\)

### Optional fields

* Short description
* Program image
* Program video
* Prerequisite courses
* Audience
* Series
* Continuing-education credit
* Benefits
* Related courses \(explicit\)

## Required fields

### Title

**Type:** short-text field

**Guidance:**

**Field notes:** 70 character limit

### Course code

**Type:** 

**Guidance:** none

**Field notes:** This is pulled through from another system. They look like this: "LR105"

### Topic

**Type:** Vocabulary – "topic"

* Conflict resolution
* Disability and employment
* Diversity and inclusion
* Human resources
* Employment law
* Employee relations
* Labor relations
* Leadership development and organizational change

**Guidance:** Must have one topic, can have two.

**Field notes:**

### Listing intro

**Type:** text field

**Guidance:** 

**Field notes:** 50 word limit (hard). This field is used for search results and landing pages within the catalogue, and on cards where a program is surfaced outside the catalogue.

### Price

**Type:** Number

**Guidance:** none

**Field notes:** Formatted as currency (USD)

### Dates

**Type:** Date picker

**Guidance:** "Pick the date."

**Field notes:** Can we schedule more than one date (i.e. if the program runs more than once; or if it spans more than one day)

### Body

**Type:** Rich Text

**Guidance:**

**Field notes:** Full WYSIWYG as supported by templates

### Sponsor

**Type:** Controlled Vocabulary

* Scheinman
* Worker Institute
* Executive Education
* LEL / CJEI

**Guidance:** Choose the institute, center or program which sponsors this event

**Field notes:** Drop-down selection (this vocab might already exist and be complete)

### Salesforce ID

**Type:** Reference

**Guidance:**

**Field notes:** Provided by integration with Salesforce.

### Program instructors

**Type:** Block

**Guidance:** Choose from existing instructors or create a new profile

**Field notes:** Select from existing instructors, or start a wizard to create a new profile

### Format

**Type:** Controlled vocabulary

* Workshop
* Course
* Certificate program
* Credit course
* Webinar
* Forum

**Guidance:** none

**Field notes:**  This already exists – could be reviewed

### Delivery

**Type:** Controlled vocabulary

* In-person
* Online
* Blended

**Guidance:** How will this program be delivered?

**Field notes:** This is currently called _Setting_. It could be replaced with (or augmented by) a map

### Location

**Type:** Location

**Guidance:** Choose where this program will be offered.

**Field notes:** This could either be a map, or a list of pre-defined locations which correspond to a real location (and can be displayed on a map)

**e.g.**

* ILR Ithaca
* ILR New York City
* ILR Buffalo
* eCornell (online)
* ILR webcast (online)

### Related programs \(implicit\)

**Type:** Block (?)

**Guidance:** Choose any other programs that you want to visitors as related to this program.

**Field notes:** A program creator should be able to choose from other programs and create the relationship (bonus if they can state the nature of the relationship [e.g. 2nd in a series, required _before this one_ ...])

## Optional Fields

### Short description

**Type:** rich-text field

**Guidance:** Summarise your program, focusing on the benefits to users. You can include photographs or illustrations (such as slides), but aim to be brief.

**Field notes:** This is a possible block we could use to allow for overview content that could live above other blocks such as a video or _benefits_ blocks.

### Program image

**Type:** Image

**Guidance:** Choose or upload an image to illustrate your program. This will be used in the header, and on promotional blocks across the site. Photos of people work best, but don't use any images you don't have permission and rights to use.

**Field notes:** 

### Program video

**Type:** Media player

**Guidance:**

**Field notes:** This one could be locked down and only available to some people who've commissioned or had a video approved ?

### Prerequisite courses

**Type:** Reference

**Guidance:** Choose any programs people need to take _before_ attending this one.

**Field notes:** Program creators should be able to pick other programs.

### Audience

**Type:** 

**Guidance:**

**Field notes:** 

### Series

**Type:** 

**Guidance:**

**Field notes:** 

### Continuing-education credit

**Type:** 

**Guidance:**

**Field notes:** 

### Benefits

**Type:** 

**Guidance:**

**Field notes:** 

### Related courses \(explicit\)

**Type:** 

**Guidance:**

**Field notes:** 



---






### Format

_e.g. 1-day workshop_

* Controlled vocabulary: [course-formats](vocabularies/course-formats.md)

### Audience

* Controlled vocabulary: [professional-audiences](vocabularies/professional-audiences.md)

### Price

* Number \(currency\) field type

### Calls to action

* Register
* Request Customised delivery
* Notify me

### Dates

#### Field notes

If scheduled, this field pulls data from Salesforce to display upcoming dates. If unscheduled, this field displays a notify-me CTA

### Body

* Rich-text field
* No character limit
* Mixed-media \(may contain images\)

#### Field notes

{% hint style="info" %}
**NB:** This field can be used as a migration interim step. Before we have courses mapped to this content model, we can pull through most of the content from the previous site into this field – then, we can ask content owners to split it out into appropriate field types \(e.g. benefits, topics...\)
{% endhint %}

### Related courses \(implicit\)

#### Field notes

This programmatically displays related courses.

## Optional fields

### Course image

### Prerequisite courses

---

# Notes

* Title
* Course code \(optional\)
* Course image \(optional\)
* Breadcrumb \(include topic?\)
* Shortest description \(max: 50 words\)
  * Prerequisites \(optional\)
* Course-navigation
  * Course details
    * Price
    * Format \(e.g. 2-day workshop\)
    * Upcoming dates \(picker\)
    * Register CTA
    * Notification CTA
      * Request customised delivery &lt;--?
      * Notify me when this course is next offered.
* Body
* Details
* Related courses
* CTAs

## Body:

* Course video \(optional\)
* Longer description
  * Special features [4](https://www.ilr.cornell.edu/programs/professional-programs/co231/employee-internal-investigations-part-i)
  * Who will benefit? [3](https://www.ilr.cornell.edu/programs/professional-programs/co336/resolving-conflict)
  * Key Outcomes [1](https://www.ilr.cornell.edu/programs/professional-programs/hr413/hr-consulting-skills-becoming-trusted-thought-partner)
  * Approach and Features [1](https://www.ilr.cornell.edu/programs/professional-programs/hr413/hr-consulting-skills-becoming-trusted-thought-partner)
  * Related workshops \[8\]\[\]
  * Related content [4](https://www.ilr.cornell.edu/programs/professional-programs/co231/employee-internal-investigations-part-i)
  * Background materials [2](https://www.ilr.cornell.edu/programs/professional-programs/hr413/hr-consulting-skills-becoming-trusted-thought-partner)
  * Moderator [2](https://www.ilr.cornell.edu/programs/professional-programs/hr413/hr-consulting-skills-becoming-trusted-thought-partner)
  * Panel [2](https://www.ilr.cornell.edu/programs/professional-programs/hr413/hr-consulting-skills-becoming-trusted-thought-partner)
* Testimonials
  * Quote
  * Call-out quote
  * Name
  * Photo
* **Details**
* Key Topics [4](https://www.ilr.cornell.edu/programs/professional-programs/co231/employee-internal-investigations-part-i)
* CLE credit [2](https://www.ilr.cornell.edu/programs/professional-programs/hr413/hr-consulting-skills-becoming-trusted-thought-partner)
* Location [5](https://www.ilr.cornell.edu/programs/professional-programs/hr420/advanced-organization-design-activating-new-operating-models)
* Certificate program [7](https://www.ilr.cornell.edu/programs/professional-programs/ollb112/steward-training-problem-solving-workplace-online)
* Instructors [1](https://www.ilr.cornell.edu/programs/professional-programs/hr413/hr-consulting-skills-becoming-trusted-thought-partner)
  * Dates \(instructors vary dependent upon date\)
  * Instructor name
  * Instructor job title
  * Instructor image
  * Short CV \(Max: 50 words, expandable\)
* Price
* Dates

## Related Courses

* Related courses
  * Explicitly related \(someone makes this relationship in the system\)
  * Implicit \(c.f. [related course suggestions](../professional-programs/related-course-suggestions.md)\)

## CTAs

* Register
* Request Customised delivery
* Notify me

## Examples

This course page for [Trends in Health Care Benefits...](https://www.ilr.cornell.edu/programs/professional-programs/lbro108/trends-health-care-benefits-what-unions-need-know) illustrates when there isn't enough information for a user to understand or make a choice.

Examples:

\[8\]: [https://www.ilr.cornell.edu/programs/professional-programs/co100/law-equal-employment-opportunity](https://www.ilr.cornell.edu/programs/professional-programs/co100/law-equal-employment-opportunity)

