---
title: Customizable Text
order: 7
footer: >
  <p><strong>Status:</strong> Updated 15 September 2016. <br><strong>Editor and project lead:</strong> <a href="https://www.w3.org/People/shadi">Shadi Abou-Zahra</a>. Developed by the <a href="https://www.w3.org/WAI/EO/">Education and Outreach Working Group (EOWG)</a> with support from the <a href="https://www.w3.org/WAI/DEV/">WAI-DEV project</a>, co-funded by the European Commission. <a href="acknowledgements">Acknowledgements</a>.</p>
---

Web accessibility is essential for people with disabilities and useful
for all. Learn about the impact of accessibility and the benefits for
everyone in a variety of situations.

## Video on Customizable Text
{:#film.no-display}

{% include video-player.html
    yt-id="rbiI65Jcz5s"
    yt-id-ad="L4WLeVc5l5k"
    captions="customizable-en.vtt|en|Captions"
    captions-ad="customizable_ad-en.vtt|en|Captions"
    descriptions=""
    descriptions-ad="customizable_ad_desc-en.vtt|en|Descriptions"
%}

What is "Customizable Text"? {#what}
----------------------------

Some users need to be able to change the way text is displayed so that
they can read the text. This includes changing the size, spacing, font,
color, and other text properties. When users change these properties, no
information or functionality should be lost, and the text should re-flow
so users don't have to scroll horizontally to read sentences. Text
customization is more than the zoom functionality, which only changes
the text size.

Who depends on this feature? {#who}
----------------------------

-   People with low vision who are not using screen magnification
    software.
-   People with some forms of dyslexia and other cognitive and learning
    disabilities who need a particular presentation of text to read it.

What are the additional benefits? {#others}
---------------------------------

-   Content is more adaptable to smaller and larger screen sizes.
-   Content is more adaptable to personal preferences and comfort.
-   Content is more adaptable when translated, since words and sentences
    are different lengths in different languages.

What needs to happen for this to work? {#action}
--------------------------------------

Content must be properly designed and coded so that it can adapt to
different customization settings. This includes using relative rather
than absolute units for the size of fonts, controls, and other objects.
Applications should use the operating system and web browser text
settings. Websites and applications could also provide information to
help users change their settings. Web browsers and other web tools need
to provide users with text customization functionality.

Learn more {#resources}
----------

-   **Accessibility Principle:**
    -   [Content can be presented in different
        ways]({{ "/fundamentals/accessibility-principles/" | relative_url }}#adaptable)
-   **Getting Started:**
    -   [Write code that adapts to the user's
        technology]({{ "/tips/developing/" | relative_url }}#write-code-that-adapts-to-the-users-technology)
-   **Easy Check:**
    -   [Resize text]({{ "/test-evaluation/preliminary/" | relative_url }}#resize)
-   **User Story:**
    -   [Mr. Yunus, Retiree with low vision, hand tremor, and mild
        short-term memory
        loss]({{ "/people-use-web/user-stories/" | relative_url }}#retiree)
    -   [Ms. Olsen, Classroom student with attention deficit
        hyperactivity disorder (ADHD) and
        dyslexia]({{ "/people-use-web/user-stories/" | relative_url }}#classroomstudent)
-   **Web Content Accessibility Guidelines ([WCAG
    Overview]({{ "/standards-guidelines/wcag/" | relative_url }})):**
    -   [Success Criteria relating to
        "text"](https://www.w3.org/WAI/WCAG20/quickref/?tags=text)
-   **User Agent Accessibility Guidelines ([UAAG
    Overview]({{ "/standards-guidelines/uaag/" | relative_url }})):**
    -   [Provide text
        configuration](https://www.w3.org/TR/2015/NOTE-UAAG20-20151215/#gl-text-config)
    -   [Multi-Column Text
        Reflow](https://www.w3.org/TR/UAAG20/#sc_1813)
    -   [Linearize Content](https://www.w3.org/TR/UAAG20/#sc_1815)
-   **User Needs:**
    -   [Accessibility Requirements for People with Low
        Vision](http://www.w3.org/TR/low-vision-needs/)

