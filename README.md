# gptinterpreter
Proof of concept for a natural language computer. Keeps track of state and manipulates this state based on an instruction in natural language. 

Has an internal state, a json object with 4 memory slots like 

```
{
     "mem0": ["<example>"],
     "mem1": "Example",
     "mem2": "Example",
     "mem3": "Example",
}
```

And outputs a new state plus an output field

```
{
     "mem0": ["New state", "New state again"],
     "mem1": "Cool new state",
     "mem2": "Wow :)",
     "mem3": "Another thing",
     "output": "Here is my output",
}
```

Output is written to a file (or stdout whatever you want).

See the prompt for a better explanation.
