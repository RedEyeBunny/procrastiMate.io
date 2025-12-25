# How to calculate vagueness?

per weak verb - 0.1
per strong verb - 0.05
per vague noun - 0.1
per scope words - 0.05
per constraint words - 0.05

** if score goes above or equal to 0.9, no need to calculate further and just generate an excuse **

- if score is btw 0.5 and 0.8, the task is vague and generate an excuse to procrastinate professionally.
- if score is btw 0.5 and 0.3, the task is not vague and try to generate a weak response to delay the task.
- if score is below 0.3 strictly, tell the user to get on with it.