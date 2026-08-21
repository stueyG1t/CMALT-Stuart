# Digital Capabilities Assessment accessibility testing record

## Purpose

During development of the Digital Capabilities Assessment, testing was initially iterative and predominantly technical. Jingyang Ai and I repeatedly tested functionality as the assessment was developed, resolving issues before broadening testing to other colleagues and students.

Some accessibility and presentation testing was deliberately undertaken once a functional **Shareable Content Object Reference Model (SCORM)** package could be tested within Moodle. This was important because the university's implementation of Moodle affects how the SCORM package is presented and launched. Testing within this environment therefore provided a more realistic representation of the learner experience.

The following records the accessibility-related checks that I personally undertook. It is intended as a record of practical testing rather than a claim of formal accessibility certification or comprehensive Web Content Accessibility Guidelines (WCAG) 2.2 conformance testing.

## 1. Functional testing within Moodle

Once the assessment was available as a working SCORM package, I tested it from within the Moodle course.

I:

- launched the SCORM package through the Moodle interface using both mouse and keyboard navigation;
- progressed through every screen of the Digital Capabilities Assessment;
- tested the available responses to each question;
- checked that selections behaved as expected;
- checked that learners could not progress where required tasks or questions had not been completed;
- completed the assessment to check that the full learner journey remained functional within Moodle.

Issues identified during development were normally resolved before deployment, but I repeated these checks within Moodle because behaviour within the deployed SCORM environment could differ from testing the web application independently.

## 2. Keyboard-only navigation

I repeated the assessment using keyboard navigation rather than a mouse.

Within the Digital Capabilities Assessment, I used the **Tab** key to move through interactive elements and the keyboard, including the **Spacebar**, to make selections. I checked that I could navigate through and complete the assessment without relying on mouse input.

The Moodle interface used to launch the SCORM package was also checked using keyboard navigation. However, this interface is part of the university's Moodle implementation and is outside my direct control. My principal focus was therefore on ensuring that the assessment itself remained operable by keyboard.

The assessment could be navigated and completed using this method.

## 3. Testing without Cascading Style Sheets

I also tested the Digital Capabilities Assessment with **Cascading Style Sheets (CSS)** disabled. This test was undertaken outside Moodle so that I could examine the underlying web application independently of presentation and accessibility issues arising from the university's Moodle environment.

I checked that:

- the content remained available and appeared in a logical sequence;
- questions and controls remained understandable without their intended visual styling;
- mouse navigation continued to function;
- keyboard navigation continued to function;
- the assessment could still be progressed and completed.

Removing the visual presentation provided a useful check that the assessment was not dependent on its styling to provide meaningful structure or navigation. It also gave me greater confidence that the underlying web application could adapt to presentation environments other than its current Moodle implementation.

## 4. Windows 11 accessibility facilities

I undertook additional checks using the accessibility facilities available on the standard University of Greenwich Windows 11 Intune-managed laptop.

In particular, I used the available **text-to-speech functionality** to check how the content was interpreted when read aloud. Combined with the keyboard and no-CSS tests, this provided an additional practical check on whether the assessment retained a meaningful structure beyond its visual presentation.

The managed Intune environment limits the assistive technologies available for testing, so this should not be interpreted as comprehensive assistive-technology or screen-reader testing.

## Findings and limitations

These tests gave me reasonable confidence that the Digital Capabilities Assessment:

- can be completed using keyboard navigation;
- does not depend entirely on visual styling to communicate its content and structure;
- retains a logical structure when CSS is removed;
- functions within the university's Moodle/SCORM environment;
- can be interpreted using the text-to-speech facilities available within the standard managed Windows 11 environment.

The testing was practical rather than a formal accessibility audit. I did not undertake structured testing with experienced users of screen readers or other assistive technologies, and these tests alone do not demonstrate full WCAG 2.2 conformance.

I therefore use WCAG 2.2 as a reference alongside functional testing and user evaluation rather than treating any single testing method as proof of accessibility. This distinction has informed my reflection in Core Area 2b between demonstrating that a system technically functions and understanding how it is experienced by its learners.
