# Parser for English Sentences

## Overview

The Parser project aims to parse English sentences using context-free grammar formalism to determine their structure. Parsing sentences is essential in natural language processing for extracting meaning and information from text. This project focuses on extracting noun phrases from sentences to gain an understanding of their subject matter.

## Context-Free Grammar

In context-free grammar, rewriting rules are applied to transform symbols into other symbols. The objective is to start with a nonterminal symbol S (representing a sentence) and repeatedly apply grammar rules until a complete sentence of terminal symbols (words) is generated. For example, the rule S -> N V means that a sentence (S) can be rewritten as a noun (N) followed by a verb (V).

## Noun Phrases

Noun phrases (NP) are crucial elements of sentences and may include complex structures. To account for various types of noun phrases, grammar rules are expanded. For instance, the rule NP -> N | Det N allows an NP to be either just a noun (N) or a determiner (Det) followed by a noun. Determiners include words like "a", "the", and "my".

## Parsing Approach

1. **Grammar Definition:** Define context-free grammar rules to represent sentence structures, including rules for noun phrases.
2. **Parsing Algorithm:** Develop a parsing algorithm to recursively apply grammar rules to parse sentences into their constituent parts.
3. **Noun Phrase Extraction:** Extract noun phrases from parsed sentences based on the defined grammar rules.
4. **Application:** Utilize the parser for various natural language processing tasks such as information extraction, sentiment analysis, and question answering.

## Future Enhancements

- Expand grammar rules to handle more complex sentence structures and linguistic phenomena.
- Integrate the parser with machine learning models to improve accuracy and handle ambiguity.
- Develop a user-friendly interface for interactive sentence parsing and analysis.
