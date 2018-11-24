A benchmark of schema-level Competency Questions and corresponding SPARQL-OWL patterns. 
The details are described in the paper: 
Dawid Wisniewski, Jedrzej Potoniec, Agnieszka Lawrynowicz, C. Maria Keet  
_Analysis of Ontology Competency Questions to SPARQL-OWL Translations_, available on arXiv.

Description of files:
* [signature_to_patterns.json](signature_to_patterns.json), 
[signature_to_patterns_high_level.json](signature_to_patterns_high_level.json), 
[patterns_to_signatures.json](patterns_to_signatures.json), 
[patterns_to_signatures_high_level.json](patterns_to_signatures_high_level.json): 
JSON files representing mapping between CQ patterns and SPARQL-OWL signatures.
In case of pattern to SPARQL-OWL signature mapping, there are empty mappings, because some patterns don’t have SPARQL-OWL translations defined.
In case of SPARQL-OWL signature to pattern mapping, there are empty mappings, because some SPARQL-OWL signatures map to CQs that don’t form a pattern (don’t utilize placeholders and are unique in their surface form).
* [linguistic_patterns.txt](linguistic_patterns.txt), 
[linguistic_higher_level_patterns.txt](linguistic_higher_level_patterns.txt): 
linguistic pattern lists
* [signatures.json](signatures.json): a list of signatures calculated.


This work is licensed under a [Creative Commons Attribution 3.0 Unported License](https://creativecommons.org/licenses/by/3.0/).
