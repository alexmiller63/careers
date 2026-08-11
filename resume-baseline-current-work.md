## Current Technical Projects and Research

### Horse Racing Expert System / Contrarian Handicapping Research

Designed a rule-based contrarian horse-racing handicapping strategy intended for historical testing using BRIS racing data and Microsoft Access.

The strategy deliberately eliminates selections likely to be overbet. The exclusion process includes:

- Top 10 horses globally

- Top 10 trainers globally

- Top 10 trainers at each of approximately 15 readily wagerable U.S. tracks

- Top 10 jockeys at each of those tracks

- Top 3 horses in each race by BRIS Power Rating

These popular horses, trainers, and jockeys are incorporated into a TwinSpires stable and used as exclusions. Horses remaining after the contrarian exclusions become betting candidates. If more than one candidate remains, the horse with the highest BRIS Power Rating among the remaining horses is selected.

Designed a historical-testing methodology focused on profit and loss as a function of betting odds rather than merely win percentage. The intended analysis treats odds as a spectrum rather than imposing arbitrary fixed categories such as short-, medium-, and long-odds wagers. Preliminary manual use suggested that the contrarian selection process tends to identify longer-odds horses; this remains an observation to be tested quantitatively against historical data.

### PearlSam and Fusslor — Integrated Personal Web Platforms

Designed and developed PearlSam and Fusslor as centralized web platforms that integrate capabilities commonly distributed across separate Internet services.

Implemented capabilities include:

- Photo collection and presentation

- Video collection and presentation

- Mailing-list functionality

- Associated email identity

- Business-card integration

- Prominent cross-platform social-media linking

- Text chat

- Webcam/video communication

A central design principle is preservation of the user's existing investment in outside social-media platforms. Rather than attempting to replace services such as TikTok or Instagram, PearlSam and Fusslor prominently connect users to their existing social-media identities and content from a single personal hub.

The core capabilities are working in Fusslor. PearlSam is substantially implemented, although complete system testing remains to be performed.

A planned usability exercise will compare the experience of uploading and publishing an existing collection of videos through PearlSam with the corresponding workflows on TikTok and Instagram.

PearlSam and Fusslor have substantially similar technical capabilities. Their difference in subject matter is not technically significant to the shared platform architecture.

### Sturdy Cryptographic Algorithm Reconstruction

Reconstructed the source code for an earlier cryptographic algorithm in Ada from surviving knowledge of the original design.

The reconstructed Ada source was reviewed and recognized as substantially consistent with the original implementation. The reconstruction occurred before the current GitHub-based preservation methodology was established.

Compilation, execution, test-harness development, behavioral verification, and cryptographic validation remain to be performed. The reconstructed algorithm should therefore be described as a source-code reconstruction rather than as a cryptographically validated implementation.

### ChannelDial — Ada / Linux / Laravel Channel Directory

Developing ChannelDial as an interactive Unix/Linux application for collecting, organizing, and searching Zello channels.

The command-line implementation is being developed incrementally in Ada. The channel data model includes fields such as:

- Channel name

- Platform

- Topic

- Language

- Region

- Description

- Date last verified

A corresponding Laravel web application is planned to provide web-based access to the channel directory.

Related work includes development of data-mining approaches for extracting useful channel information from existing Zello channel databases and directories.

Each small working component of the Ada implementation is also being documented as a tutorial lesson. These lessons are intended eventually to form a book demonstrating Ada development through the construction of a real-world application.

### Independent ChatGPT Usability Study

Conducted an independent structured usability study of ChatGPT, concentrating particularly on persistence problems and other recurring interface and behavioral problems described during the study as "glitchiness."

Observed problems were recorded and analyzed using multiple structured fields. Confirmed evaluation fields included:

- Severity

- Impact on the user

- Reproducibility

- Analysis of the effects of the observed behavior

The study applies formal software-quality and usability-analysis techniques to extended real-world interaction with an AI system. It is an independent study and does not imply affiliation with OpenAI.

### Star Almanack — Computational Astronomy and Technical Writing

Developing Star Almanack, an astronomy project and book designed to tell readers when individual stars are most favorably placed for observation.

The astronomical criterion used is the date on which a star transits the local meridian at 9:00 PM local apparent time.

Independently developed spreadsheet-based astronomical calculations for determining these dates. The original calculations required extensive manual spreadsheet work. The underlying methodology was later independently reproduced using ChatGPT, providing a cross-check of the calculation approach.

The project combines computational astronomy with explanatory technical writing. Narrative stories are used to communicate technical and conceptual points rather than functioning merely as unrelated fiction.

Current stories include:

- **Two Rabbis** — explains the role and necessity of conventions such as the International Date Line and related systems.

- **Neil deGrasse Tyson Story** — examines the balance between developing new explanatory approaches and retaining traditional conventions that remain useful rather than discarding them merely for novelty.

- **Birthday Story** — describes the originating impetus for the Star Almanack project.

### Illuminated Bible — Multilingual Text-Presentation Prototype

Designed and prototyped the Illuminated Bible, a system intended to preserve the continuous experience of reading an English Bible while providing original-language information at selected significant words.

When an important word is encountered, it is illuminated in place without changing its position in the reading sequence. The illumination can provide:

- The original-language word, including Hebrew, Aramaic, Syriac, or Koine Greek as applicable

- A transliteration intended to assist pronunciation

- The corresponding BEB or WEB translation

After the illuminated word, normal English reading continues until the next significant illuminated term is encountered.

Working prototype material has been produced for approximately 10 verses of Genesis and approximately 10 verses of John.

### Elephant — Preservation AI & Tool Orchestration Architecture

**Status: Design phase; no implementation code yet.**

Designed the architecture for Elephant, a proposed preservation-oriented AI system with two principal purposes.

The first is preservation: identifying and retaining information that matters from conversations while avoiding unintended alteration, loss, compression, or "munging" of significant information.

The second is orchestration: coordinating multiple external open-source and freely available tools and services rather than attempting to reproduce every capability within a single system.

Architecture and requirements development are in progress. Software implementation has not yet begun.

### Elephant Book — AI-Assisted Notebook & Information Organization

**Status: Design phase.**

Designed Elephant Book as an AI-assisted notebook and information-management concept associated with the broader Elephant preservation philosophy.

The system is intended to accept ordinary notes as well as handwritten or stencil-assisted notation, providing the freedom of a physical notebook or scratchpad while using an underlying AI to organize, preserve, and retrieve significant information.

The concept combines aspects of free-form note taking, information organization, task organization, handwritten notation, and AI-assisted preservation without depending on any particular commercial notebook or productivity platform.

### LunarFAX — Device-Based Fax Application

**Status: Product design only; no implementation code yet.**

Designed LunarFAX as a fax application for sending faxes directly from a user's device.

The proposed usage model begins each user with 7 available fax pages. The available allowance increases by 1 page each day until reaching a maximum accumulated allowance of 30 pages. Users can purchase additional fax capacity when needed.

One intended application is a **Lunar Facts** astronomy-marketing campaign in which one astronomy fact can be sent by fax each day to promote the astronomy book.

The application remains in the product-design stage and has not yet been implemented.

