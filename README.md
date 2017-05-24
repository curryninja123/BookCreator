Book/Note Generator 1.1.1
=========================

Project written by Vishnu Iyer to create XML format for open course note creation. Currently offers support for the following operations:
- mathematical definitions and theorems
- in-line and line-by-line formulae
- propositions, remarks, and lemmas
- proofs
- bolding, emphasizing, and highlighting text
- code embeddings

Format
-------
- note title and number: <code>\<note number = "number" title = "title">\</note></code>
- adding a section: <code>\<section name = "name">\</section></code>
- adding a subsection: <code>\<subsection name ="name">\</subsection></code>
- adding a definition: <code>\<def name="name">\</def></code>
- adding a theorem: <code>\<thm name ="name">\</thm></code>
- adding a lemma: <code>\<lemma name = "name">\</lemma></code>
- adding a proposition: <code>\<prp>\</prp></code>
- adding a remark: <code>\<rmk>\</rmk></code>
- highlighting text: <code>\<highlight>\</highlight></code>
- bolding text: <code>\<b>\</b></code>
- emphasizing text: <code>\<em>\</em></code>
- adding math in-line: <code>\<math></math></code>
- adding display math: <code>\<dmath></dmath></code>
- adding a proof: <code>\<proof>\</proof></code>
- embedding code: <code>\<code lang = "language" href="path-to-file"></code>
