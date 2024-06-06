# HumLand

Visual annotations, integrated tools, and dynamic referencing systems should not be exclusive to software developers and their IDEs. This is a project to modernize the way that humanities papers are produced drawing from personal STEM experience. The innovative features allow the academic to have more control over how their work is consumed, make their papers easier to visualize and parse, access effective tools that facilitate coining experimental terms in emerging fields, and among many other functionalities. This tool is designed to become a Swiss army knife of a toolchain to be adopted in humanities research, literature creation and/or analysis, poetry interpretations, and later evolve into a widespread platform for use in any other systems that use symbolic representation to communicate ideas.

## Important Goals
- **Change the way we symbolically communicate**  
  - For now, the symbol set will be limited to the standard English alphabet. However, in the future this should support cross-language compatibility and custom symbol creation (Ex: similar to emojis or wingdings).
- **Improve creator control**  
  - The user should have more protection against confusion and misinterpretation. If there are any features that you think could help, please refer to the [contact](#contact) section below.
- **Become a new standard**  
  - This tool should be widely adopted in the academic community. To warrant adoptability by academic journals, reporters, and other scholars XML/TEI Encoding should be supported. Portability will be further analyzed after the first full-featured prototypes are out.
- **Clarify intended audience**  
  - For now this is focused on being adopted by academics in the humanities. In the future, this project may be extended to support authors of all walks of life: professional or hobbyist.

## Planned Features

### Syntax Coloring and Color Legends
- **Purpose**: Enhance the readability and emphasis of various types of content.
- **Features**:
  - Introduce additional options for highlighting, enabling users to emphasize key terms or new terms coined by the academic.
  - Provide a customizable color legend to help readers quickly understand the significance of different colors.
  - Option to further emphasize or describe existing text stylings such as italics, quotes, and bold text with color coding.
- **Benefits**:
  - Makes important text stand out, improving the reader's ability to quickly grasp critical concepts.
  - Facilitates easier navigation through complex documents.
  - Allows for personalization, catering to the specific needs of different users and specific intentions of authors.
- **Examples**:
  - *TODO: SHOW IMAGES HERE*
  - Maybe do a side by side comparison of syntax highlighting in CS vs this HUM thing

### Word Tree Visualization
- **Purpose**: Provide a visual representation of the relationships between words and their usage in the texts.
- **Features**:
  - Users can click on any word and choose the ```Tree``` option to see a tree of related words based on their contextual relevance.
  - Tree will, by default, be generated using existing databases to provide accurate probablistic connotations.
  - Trees will have weighted nodes. Authors will have the option of adjusting weights and emphasizing certain words in the tree if the root word choice was significantly influenced by a specific related word. Authors can decide if readers would benefit from such additional context.
  - Closely correlated words in separate sections can be automatically detected and form connections within large complex documents or entire projects.
  - Assist authors in coining new words by facilitating the creation of a custom the word tree for applying connotations to newborn terms before they are widely adopted.
  - Trees will have adjustable branch depth and node limits in order for readers to simplify the visualizations.
  - Authors will have the option to set recommended branch depth and node limits for appropriate tree exploration in the word's context and save the user from manually optimizing tree traversal.
- **Benefits**:
  - Helps in understanding the context and connections of specific terms within the document and within the English language at large.
  - Aids academics in developing new terminology and seeing how it fits within existing language.
  - Offers a modern, dynamic, and interactive way to explore the text, enhancing engagement.
- **Examples**:
  - *TODO: SHOW IMAGES HERE*
  - Maybe can call this something else like word map later in development (upgrade because maps are harder than trees)
  - Either use existing APIs, predictive neural nets, or Baysian models for word generation when doing the above (licencing is important here).

### Built-In Word Definitions
- **Purpose**: Provide easy access to word definitions from multiple sources.
- **Features**:
  - Clicking on a word and choosing the ```Definitions``` option will bring up definitions from various sources such as Webster's Dictionary, Urban Dictionary, and other reputable lexicons.
  - Will have a slider presenting a range of established and colloquial definitions to give users comprehensive understanding.
  - Allows authors to set their own interpretations of a specific word if it is being coined or if the situation requires explicit clarification.
- **Benefits**:
  - Enhances comprehension by providing immediate clarification of terms.
  - Supports diverse interpretations and understandings of words, reflecting both formal and colloquial uses.
  - Supports author customization.
  - Saves time for readers, eliminating the need to search for definitions separately on external sites/applications.
- **Examples**:
  - *TODO: SHOW IMAGES HERE*
  - Maybe use Bell Hooks "All About Love" here?

### Integration of Existing Tools
- **Purpose**: Become the equivalent of an IDE for academics in the humanities by combining the functionalities of popular text editors, formatting systems, and academic support tools all in one place.
- **Features**:
  - **Standard Text Editor Features**:
    - Spell Check, Grammar Check, Formatting (Bold, Italics, Underline), Bulleted and Numbered Lists, Tables, Images, Headers and Footers, Track Changes, Comments, Find and Replace, Print Preview, Etc.
  - **Formatting Standards**:
    - LaTeX, Markdown, PDF Preprocessors/Formatters, MLA, APA, Chicago, Harvard, IEEE.
    - Special parsers to handle these formats seamlessly.
  - **Academic Support Tools (This is subject to change)**:
    - **Grammar Checkers**: Grammarly, Hemingway, LanguageTool.
    - **Citation Tools**: Zotero, EndNote, Mendeley, Cite This For Me.
    - **Collaboration Mediums**: Google Docs, Microsoft OneDrive, Slack, Microsoft Teams.
    - **APIs**: Google Docs API, Microsoft Graph API, Grammarly API, Mendeley API, Slack API.
  - **Predictive AI and AI Assistant (This feature will be last priority)**:
    - Integration of AI tools to predict typing and suggest completions.
    - AI Assistant to help with research, citations, and formatting.
- **Benefits**:
  - Consolidates multiple tools into one platform, enhancing efficiency.
  - Facilitates easier adherence to academic standards and formats.
  - Enhances collaboration among scholars with integrated tools.
  - AI-powered features improve productivity and accuracy.
- **Examples**:
  - *TODO: SHOW IMAGES HERE*

### Adaptation from Paper to Digital and Vice Versa (This might be the most difficult feature, might take the longest to implement)
- **Purpose**: Facilitate seamless transitions between digital and paper formats.
- **Features**:
  - **Digital to Paper**:
    - High-quality PDF generation with embedded fonts and layout options for optimal print results.
  - **Paper to Digital**:
    - Optical Character Recognition (OCR) to convert scanned documents into editable digital text.
    - Automatic formatting based on detected styles (headings, paragraphs, citations) and support for HumLand specific features.
    - Integration with reference managers to recognize and format citations.
- **Benefits**:
  - Caters to academics who prefer to keep physical records.
  - Allows for easy digitization of paper documents, making them editable, searchable, and modernizable.
  - Maintains consistency across the physical and digital domains, supporting transitions between traditional and modern academic workflows.
- **Examples**:
  - *TODO: SHOW IMAGES HERE*

## Why Make the Switch?

### The Outdated Academic Toolkit
Traditional paper-only formats and manual processes are no longer efficient nor widely used. Despite being in the digital age, many academics are still bound by the limitations of tools and formats designed for physical paper that are grandfathered into their digital devices. Nowadays, almost all writing goes through some sort of digital processing layer, yet they only translate between old formats and do little to take advantage of their digital form. The current toolkit for academics is fragmented, lacks innovation, and is terribly outdated compared to the toolchains in STEM fields. HumLand aims to push the boundaries of the modern non-STEM academic development environment and be a game changing upgrade for academic authors' digital workflows while still maintaining cross compatibility with physical workflows.

### Benefits for Emerging Fields
Scholars in emerging fields of humanities can particularly benefit from modern, integrated tools that support innovative ways of research and collaboration. If the pioneers of these fields choose to embrace digital advancements, their benefits and communicative edge will pave the way for older established fields to shed their inertia and adopt the future's toolchain. 

### A Development Environment for the Future
Although there's nothing like the unlimited customization that a creative author can achieve with pen and paper, the world is becoming more environmentally conscious and enveloped in technology. Especially post COVID, academic institutions have made radical shifts away from the traditional tools and redirected towards laptops and online submissions. HumLand hopes to help people make the "green transition" easier by modernizing the digital development landscape to have features as dynamic as personalized paper notes but in its unique way with the additional benefits of widespread standardization. HumLand will support physical cross-compatibility but hopes that the feature gradually fades as it facilitates the world's transition towards digital toolkits.
 
# ADD EVIDENCE FROM MURPHY PAPER, MARS POEMS, AND UNKINDNESS OF GHOSTS (The rest of this doc until Feature Advantages Summary is a WIP)

#### Murphy paper

This section will be the standard user demo. *TODO: ELABORATE*

#### Mars poems

This section will have another demo for interpreting or annotating poems. *TODO: ELABORATE*

#### Unkindness Of Ghosts

This section will serve to highlight several voices and italics. *TODO: ELABORATE*

### Feature Advantages Summary
- **Syntax Coloring and Color Legends**: Improve readability and emphasis, making complex documents easier to understand, personalize, and control.
- **Word Tree Visualization**: Provides a dynamic and interactive way to explore text, aiding in understanding and creating new terms.
- **Built-In Word Definitions**: Offers quick access to comprehensive definitions, enhancing comprehension.
- **Integration of Existing Tools**: Combines the best features of popular text editors and academic support tools, streamlining the research and writing process.
- **Predictive AI and AI Assistant**: Boost productivity with advanced typing predictions and research assistance.
- **Adaptation from Paper to Digital and Vice Versa**: Facilitates seamless transitions between digital and paper formats, ensuring consistency and efficiency.

HumLand not only modernizes the way humanities papers are written and visualized but also significantly enhances the academic experience by integrating essential tools into one seamless platform.


## License

All Rights Reserved

© 2024 George Ore

All rights reserved. This material may not be reproduced, displayed, modified, or distributed without the express prior written permission of the copyright holder. For permission, contact gore@caltech.edu.

## Contributing

If you would like to contribute to this project, please contact gore@caltech.edu. We welcome suggestions, bug reports, and pull requests.

## Contact

For any other inquiries, please reach out to gore@caltech.edu.
