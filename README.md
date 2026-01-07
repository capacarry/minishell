# minishell

The Minishell project at 42 programming school tasks the student with creating a minimal yet functional Unix shell, closely inspired by bash. The objective is to deepen one’s understanding of process management, file descriptors, signals, and parsing, by recreating the fundamental mechanisms behind a command-line interpreter. This project must be done in C.

At its core, Minishell must:

- Display a prompt and wait for user input

- Parse and execute commands using the system’s PATH

- Handle built-in commands such as echo, cd, pwd, export, unset, env, and exit

- Support pipes (|), redirections (<, >, >>, <<)

- Manage environment variables, including expansion with $VAR and $?

- Correctly respond to signals (Ctrl-C, Ctrl-D, Ctrl-\) in both interactive and execution contexts

- Replicate bash-like behavior for quotes (single and double) and escaping rules
