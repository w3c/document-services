# Introduction
The [Document Services Community Group](https://www.w3.org/community/services/) intends to, in coordination with other groups, create a general-purpose architecture, API's, and protocols for both free and paid-subscription-based document services to convenience document service providers and to equip and empower end-users who will be able to make use of multiple document services simultaneously to better author and review documents.

# Document Services
**_Document services_** are client-local, on-prem, or remote services upon documents, portions of documents, or selections of document content.

## Examples of Document Services
1. spellchecking
2. grammar checking
3. fact checking
4. analysis of subjectivity and objectivity
5. mathematical proof checking
6. reasoning checking
7. argumentation checking
8. narrative checking

# Protocol Brainstorming
1. A word-processing application could transmit a selection of content, a selection accompanied by contextual content, or an entire document to a service provider and receive a response. This might occur whenever an end-user selected to perform an operation using an application menu or context menu.
2. A word-processing application could send content to a service provider as edits occur in real-time and receive data in response. This scenario involves a single end-user authoring a document.
3. A service provider could participate as a virtual co-author with a team of human authors, receiving document edits in real-time and sending data in response. Examples of word-processing applications which support real-time co-authoring scenarios include [Microsoft Word](https://support.microsoft.com/en-us/office/collaborate-on-word-documents-with-real-time-co-authoring-7dd3040c-3f30-4fdd-bab0-8586492a1f1d) and [Google Docs](https://www.google.com/docs/about/).

# User Interface Brainstorming
As envisioned, there are different types of response data from service providers and these response data can be integrated into word-processing applications' user interfaces in a number of ways.

1. Highlighting or underlining document content and providing more information or options with a context menu.
2. Displaying information in a status bar, e.g., word count.
3. Displaying information in a popup window or widget.
4. Displaying information in a document margin, e.g., data about one or more paragraphs.
5. Displaying information in a side-panel widget.
6. Displaying information in a floating, dockable widget.
7. Displaying information in the form of a document comment which can annotate an arbitrary selection of document content.
8. Displaying information in a generated report about the document which the end-user can navigate to from or within the word-processing application.
9. Providing response data in the form of dialogue-system content, in another channel, with hyperlinks which, if clicked upon, could highlight selections of relevant document content.
