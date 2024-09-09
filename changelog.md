## Changelog

### 41e6c5f (feat: Improve tm_prompt_improved.xml with better structure and clarity)

* Added a requirement to define new tags within the `<thinking>` section before using them.
* Added a requirement to explain the nature of errors and reasoning behind corrections in the `<reflection>` section.
* Closed the `<output>` tag within the `<claude_evaluation>` section.
* Replaced "while(true)" with "while (true)" in the `<loop>` section.
* Removed unnecessary comment delimiters in the `<claude_thoughts>` section.

### ce6b781 (fix: Close output tag in tm_prompt_improved.xml)

* Closed the `<output>` tag within the `<claude_evaluation>` section.

### 7f5cb2e (feat: Create new tm_prompt_new.xml file with clean and valid XML structure)

* Created a new file `tm_prompt_new.xml` with a clean and valid XML structure based on the content of `tm_prompt_improved.xml`.
* Escaped `<` and `>` characters within text content to ensure XML validity.

