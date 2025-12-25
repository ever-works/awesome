# Awesome Common Lisp Learning

**URL:** https://github.com/GustavBertram/awesome-common-lisp-learning#readme  
**Category:** Themed Directories  
**Tags:** lisp, education, awesome-lists  
**Brand:** sindresorhus/awesome

## Overview
Awesome Common Lisp Learning is a curated directory of resources for learning Common Lisp. It focuses specifically on educational materials—books, online references, tutorials, tools, and community links—rather than libraries or software in general.

It complements other Awesome Common Lisp lists that cover:
- Libraries: https://github.com/CodyReichert/awesome-cl
  - Curated Libraries (updated fork): https://github.com/vindarel/curated-awesome-cl
- Software: https://github.com/azzamsa/awesome-cl-software

Contributions are accepted via documented contribution guidelines in the repository.

## How to Use
Suggested learning path provided by the list:
1. Set up a Common Lisp environment.
2. Bookmark the Common Lisp HyperSpec: http://www.lispworks.com/documentation/common-lisp.html
3. Download and work through a Common Lisp book suitable to your level; type out and experiment with the examples, and feel free to switch books if needed.
4. Practice using the Common Lisp track on Exercism: https://exercism.org/tracks/common-lisp
5. When stuck, use online communities and follow best practices for asking questions: http://www.catb.org/esr/faqs/smart-questions.html
6. Learn about Quicklisp, a library manager for Common Lisp: https://www.quicklisp.org/beta/
7. Eventually read the manual for your chosen Common Lisp implementation.

## Features

### Structure / Coverage
The directory is organized into sections that group learning-related resources:
- How To Use (recommended learning workflow)
- Lisp Environments
- Online References
- Online Books
- Offline (print) Books
- Online Community
- Library Management
- Common Lisp Implementations
- Credit / acknowledgments

### Lisp Environments
Guidance and tools for setting up a productive Common Lisp development environment.

#### Prepackaged Environments
Ready-to-use bundles that combine an editor, Lisp implementation, and library tooling:
- **Portacle** – https://shinmera.github.io/portacle/
  - Portable, multi-platform Common Lisp environment.
  - Includes a customized Emacs, SLIME, SBCL, Quicklisp, and Git.
  - Distributed as a self-contained package with no traditional installation required.
- **Lispbox** – https://common-lisp.net/project/lispbox/
  - Pre-packaged IDE: Emacs + SLIME.
  - Includes Clozure Common Lisp as the implementation.
  - Integrates Quicklisp as the library manager.
  - Distributed as archives for Windows, macOS, and Linux.
  - Based on the older “Lisp in a Box” concept.
- **LispWorks Personal Edition** – http://www.lispworks.com/downloads/
  - Non-Emacs-based IDE tied to the LispWorks implementation.
  - Personal edition includes certain usage or feature restrictions.
- **Allegro Common Lisp** – https://franz.com/products/allegrocl/
  - Allegro CL environment with an **Express Edition** that can be used for free: https://franz.com/downloads/clp/survey
  - Offers training videos via YouTube: https://www.youtube.com/channel/UCN36UrxtyNBJPaG0kmBJNRw

#### For Advanced Users
Resources for users comfortable assembling their own environment:
- **Articulate Common Lisp** – http://articulate-lisp.com
  - HOWTO-oriented guide for constructing a Common Lisp environment.
  - Includes information on useful libraries: http://articulate-lisp.com/project/abcs.html
  - Covers project structure and setup: http://articulate-lisp.com/project/new-project.html
- **Emacs + SLIME setup for experienced Emacs users**
  - Suggests installing:
    - Emacs: https://www.gnu.org/software/emacs/
    - SLIME: https://common-lisp.net/project/slime/
    - A supported Common Lisp implementation (the list links to supported implementations).

### Learning & Reference Resources (as indicated by sections)
The list organizes, but in the provided excerpt does not fully enumerate, the following categories:
- **Online References** – Web-based documentation and reference material (e.g., Common Lisp HyperSpec and similar resources).
- **Online Books** – Free or online-accessible books for learning Common Lisp.
- **Offline Books** – Print or downloadable books for different skill levels.
- **Online Community** – Links to forums, chat groups, mailing lists, etc., for asking questions and getting help.
- **Library Management** – Guidance and tools such as Quicklisp for handling third-party libraries.
- **Common Lisp Implementations** – Links and pointers to various Common Lisp implementations beyond those bundled in environments.

### Contribution
- The repository encourages contributions of new or improved learning resources.
- A dedicated contribution guideline file (`contributing.md`) explains how to propose additions or changes.

## Pricing
- The directory itself is a free, open GitHub repository.
- Individual tools or books listed may have their own licensing or pricing, but specific pricing details are not provided in the given content.

## Related Awesome Lists
- **Awesome Common Lisp (Libraries):** https://github.com/CodyReichert/awesome-cl
- **Curated Awesome Common Lisp Libraries:** https://github.com/vindarel/curated-awesome-cl
- **Awesome Common Lisp Software:** https://github.com/azzamsa/awesome-cl-software
