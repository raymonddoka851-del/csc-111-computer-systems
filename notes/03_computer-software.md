# 03 · Computer Software

![Source figure from Chapter 3: Computer Software](../assets/figures/chapter-3-computer-software-p01-i01.png)

## Categories and roles

**Software** is a program or related set of instructions and data. **System software** operates and manages the computer; **application software** helps a user complete a task.

| Type | Examples and purpose |
|---|---|
| Operating system | Windows or Linux manages memory, files, devices, accounts, and running programs |
| Device driver | Lets the OS communicate with a particular printer, display, or other device |
| Utility | Security scanning, backup, compression, file management, and maintenance |
| Language translator | Compiler translates a program before execution; interpreter translates/executes stepwise; assembler translates assembly language |
| Application | Word processor, spreadsheet, browser, presentation tool, or database manager |

Applications may be **general-purpose** (used for many tasks) or **special-purpose** (built for a particular activity). **Off-the-shelf** software is ready-made; **custom** software is developed for a specific user or organization. Choose software that is legitimate, supported, suitable for the task, and compatible with the device.

A **database** is an organized collection of related data. A **DBMS** (database management system) creates, searches, updates, and controls access to databases. A spreadsheet is convenient for calculations and small tables; a DBMS is better for structured, related records and controlled multi-user access.

## Programs and simple algorithms

A **program** is an ordered set of instructions. An **algorithm** is a finite, clear procedure for solving a problem; **pseudocode** describes its logic in readable steps. A good algorithm states inputs, processing, outputs, and a stopping condition.

Example: calculate a student’s mean from three marks.

```text
INPUT mark1, mark2, mark3
total = mark1 + mark2 + mark3
mean = total / 3
OUTPUT mean
```

To check the logic, try `60, 75, 90`: total `225`, mean `75`. A programming language expresses such steps in a form a computer can translate and execute. **Testing** checks expected cases; **debugging** finds and corrects defects.

## Malware and safe computing

**Malware** is software intended to harm, disrupt, spy on, or gain unauthorized access to systems. A virus attaches to files and spreads when they run; a worm spreads across systems; a Trojan disguises itself as useful software; ransomware locks or encrypts data to demand payment; spyware collects information covertly. Antivirus tools, firewalls, updates, least-privilege accounts, and offline or separate backups reduce risk but do not replace careful behavior.

### Safe response procedure

1. Do not open unexpected attachments, enable unknown macros, or install software from untrusted sources.
2. If a device behaves suspiciously, stop entering passwords or sensitive data and disconnect it from the network if safe and permitted.
3. Tell the responsible support person; follow institutional incident procedures rather than deleting evidence or forwarding malware.
4. Restore files only from known-good backups and change exposed passwords from a clean device.

Use licensed software, respect copyright and privacy, protect passwords, and do not install or run programs on devices without permission.

:::mistakes
- An operating system is system software; a spreadsheet is application software.
- A compiler and interpreter both translate code, but they do so differently.
- Antivirus cannot guarantee safety. Updates, backups, caution, and reporting still matter.
:::

## Active recall

1. Classify a printer driver, spreadsheet, operating system, and backup utility.
2. Write pseudocode to convert minutes to hours and remaining minutes; test it with 135 minutes.
3. Distinguish a virus, worm, Trojan, and ransomware, then give a safe first response to a suspicious attachment.
