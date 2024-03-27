# Sven's LaTeX Setup

Hi, folks,

this Repository contains my default LaTeX configuration for typesetting documents. I mainly use it for "professional" documents like software documentation, requirements documents, manuals, etc. But it can also be used for a thesis for example. That is actually how my setup started: as the basis for my thesis in electrical engineering. It has since grown and been modularized a bit more.

> :warning: Products change over time. I do my best to keep up with the latest changes and releases as I use any tools, but I am not responsible if stuff breaks on your end. So: Use your own brain when (re)using my stuff.

Check out my YouTube Channel: [Eternally Surprised](https://www.youtube.com/@EternallySurprised).

## Core Features
- Configuration for English and German documents.
- Standard-Bibliography which can be used for bibliographys which are used for multiple documents.
- Document-specific Bibliography which can be used to not clutter the "global" bibliography.
- Global glossary definition files in two languages (in this example they both contain the same stuff and are both in English but you get the point).
- Document-specific glossary definitions. The reasoning is equivalent to that for the bibliography.
- Some custom commands (see the settings file) for creating requirement tables, etc.
- Additional commands for recurring things like a company name
- Added some SI-units as well
- Full ARARA support for automation of the typesetting process

## LaTeX Requirements
I suggest to use the MikTex-Distribution to install LaTeX and the stuff around it. Furthermore, I do use TeXstudio for editing, so I can confirm the setup works with this toolchain. You should have ARARA installed and set up (there are plenty of explanations on how to do this which I won't repeat here as they will be very dependent on your toolchain, etc.)

