# Simple Python Chatbot

A small rule-based command-line chatbot. It checks user input for selected words and phrases. It can greet the user, answer a basic question about its name, and exit when the user says goodbye.

## Run

Requires Python 3.

```bash
python Code
```

## Behaviour

- Responds to selected greetings.
- Responds to selected questions about its name.
- Gives a basic reply when the input contains `how` or `who`.
- Ends the chat when it detects a goodbye phrase.
- Echoes the user's input when no rule matches.

The program can print more than one response when an input matches multiple rules.

## Learning goals

This project practises:
- Lists and dictionaries
- String methods such as `lower()`
- `any()` and loops
- Conditional statements
- Collecting multiple responses before printing them

## Limitations

This is a rule-based script. It does not use an AI model or understand language beyond its keyword checks.
