---
# Translation info https://www.w3.org/wiki/WAI/Website/Translate

title: "Evaluating Web Accessibility Overview"
nav_title: "Evaluation Overview"

lang: en
last_updated: 2018-09-20
permalink: /test-evaluate/

github: 
  repository: w3c/wai-eval-overview
  path: index.md

feedbackmail: wai@w3.org
class: tight-page
footer: >
  <p><strong>Date:</strong> Updated 20 September 2018.</p>
  <p><strong>Editor:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
  <p>Developed with input from the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>).</p>
ref: /test-evaluate/
---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page links to resources to help evaluate web accessibility. Accessibility evaluation is also called "assessment", "audit", and "testing".

{::nomarkdown}
{% include box.html type="end" %}
{:/}


{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" class="full" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

{% include excol.html type="all" %}

## Introduction {#intro}

{% include excol.html type="start" id="video-intro" %}

<img src="https://www.w3.org/WAI/content-images/wai-intro-accessibility/video-still-accessibility-perspectives-16-9.jpg" alt="" style="height: 2em; border-radius: .25em; vertical-align: middle;">
 Video: Overview of Evaluation Resources

{% include excol.html type="middle" %}

{% include video-player.html
    yt-id="93UgG72os8M"
    captions="/keyboard-en.vtt|en|Captions"
    descriptions=""
%}

{% include excol.html type="start" id="video-intro-transcript" %}

Show transcript

{% include excol.html type="middle" %}

## Text Transcript with Description of Visuals

<table>
  <thead>
    <tr>
      <th width="65%">Audio</th>
      <th>Visual</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Web Accessibility Perspectives: Keyboard Compatibility</td>
      <td>Web Accessibility Perspectives:<br />
        Keyboard Compatibility</td>
    </tr>
    <tr>
      <td>Not being able to use your computer because your mouse doesn't work, is frustrating.</td>
      <td>A man drops his computer mouse off the desk. The computer mouse no longer works.</td>
    </tr>
    <tr>
      <td>Many people use only the keyboard to navigate websites &mdash; either through preference or circumstance.<br /></td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td>Whether it's temporarily limited mobility,</td>
      <td>A woman with her arm in a sling is typing on a keyboard &mdash; but the website requires the use of a mouse to select the date.</td>
    </tr>
    <tr>
      <td>a permanent physical disability,</td>
      <td>A man with a wheelchair is using a mouth-stick to type.</td>
    </tr>
    <tr>
      <td>or simply a broken mouse,<br />
        the result is the same:</td>
      <td>The man with the wheelchair also cannot use the site.</td>
    </tr>
    <tr>
      <td>Websites and apps need to be operable by keyboard.</td>
      <td>He switches to a different website that allows typing the date.</td>
    </tr>
    <tr>
      <td>Web accessibility: Essential for some, useful for all.</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td>Visit w3.org/WAI/perspectives for more information on Keyboard Compatibility</td>
      <td>Visit<br />
        w3.org/WAI/perspectives<br />
        for more information on<br />
        Keyboard Compatibility.<br />
        W3C Web Accessibility Initiative logo</td>
    </tr>
  </tbody>
</table>

{% include excol.html type="end" %}

{% include excol.html type="end" %}


When developing or redesigning a website or web application, evaluate accessibility early and throughout the development process to identify accessibility problems early, when it is easier to address them.

There are evaluation tools that help with evaluation. However, no tool alone can determine if a site meets accessibility standards. Knowledgeable human evaluation is required to determine if a site is accessible.

## Initial Checks {#initial}

Even if you don’t know anything about accessibility and you don’t have a robust accessibility tool, you can check some aspects of accessibility.

[Easy Checks — A First Review of Web Accessibility](/test-evaluate/preliminary/)
:   Provides step-by-step guidance and brief explanations for checking some aspects of accessibility.

## Tools

Web accessibility evaluation tools are software programs or online services that help determine if web content meets accessibility standards.

[Web Accessibility Evaluation Tools List](https://www.w3.org/WAI/ER/tools/)
:   Includes information on more than 100 tools. You can use the filters to narrow down the list to the types of tools you are interested in.

[[Selecting Web Accessibility Evaluation Tools]](/test-evaluate/tools/selecting/)
:   Provides guidance on choosing tools. It describes the features and functionality of different types of evaluation tools, and discusses things to consider for your situation.

## Conformance Evaluation {#conformance}

Conformance evaluation determines how well web pages or applications meet accessibility standards. W3C’s Website Accessibility Conformance Evaluation Methodology (WCAG-EM) is an approach for determining conformance to Web Content Accessibility Guidelines (WCAG).

[[WCAG-EM Overview: Website Accessibility Conformance Evaluation Methodology]](/test-evaluate/conformance/wcag-em/)
:   A short page with basic information to get you started. We suggest you read it before going to the [full WCAG-EM document](https://www.w3.org/TR/WCAG-EM/).

## Reports

Communicate the results of evaluation clearly, including the scope of the evaluation.

[WCAG-EM Report Tool: Website Accessibility Evaluation Report Generator](https://www.w3.org/WAI/eval/report-tool/#/)
:   Helps you generate evaluation reports according to WCAG-EM. It does not do the checking for you. It helps you follow the steps of WCAG-EM and it generates a report from the input you provide.

[[Template for Web Accessibility Evaluation Reports]](/test-evaluate/report-template/)
:   Suggests information to include in a report.

## People

Getting the right people and skills involved makes your accessibility evaluations more effective.

[[Involving Users in Evaluating Web Accessibility]](/test-evaluate/involving-users/)
:   Provides guidance on including people with disabilities ("users") in evaluation throughout project development.

[Using Combined Expertise to Evaluate Web Accessibility](/test-evaluate/combined-expertise/)
:   Discusses skill sets and considerations for collaborative review.

## Standards

Specifications for writing accessibility test rules (ACT Rules Format) and expressing test results (EARL) are introduced in [Evaluation Standards Overview](/standards-guidelines/evaluation/).
