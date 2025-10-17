# SimpleJavaBuild-lol

A tiny Java project that demonstrates a simple build and run workflow and shows how to use GitHub (clone, commit, push, branches, and pull requests). This repository is meant to be small and approachable — great for learning the basics of Git, GitHub, and compiling/running Java programs.

## What this is
- A small Java application (single class / a few classes) that prints a message or demonstrates a trivial feature.
- A hands-on example to practice: cloning a repo, making changes, committing, creating branches, opening a PR, and using GitHub issues.

## Features
- Minimal, easy-to-read Java code.
- Instructions to build and run using the JDK (no external build tools required).
- Short contributions guide to practice GitHub collaboration.

## Prerequisites
- Java JDK 11+ installed (or any version the project targets)
- git installed
- A GitHub account (to push changes, open PRs, and create issues)

## Getting started

1. Clone the repository:
   git clone https://github.com/YousufNotSoCool/SimpleJavaBuild-lol.git
   cd SimpleJavaBuild-lol

2. Build (compile) the Java source:
   - If the project contains a single source file (e.g., src/Main.java):
     javac -d out src/*.java
   - Or compile everything under src/:
     javac -d out $(find src -name "*.java")

   The compiled .class files will be in the `out` directory.

3. Run the program:
   - If the main class is `Main` and package-less:
     java -cp out Main
   - If there is a package, use the fully-qualified class name:
     java -cp out com.example.Main

(Adjust the commands above based on the actual package and main class name in this repo.)

## Example
Expected console output (example):
Hello from SimpleJavaBuild-lol!
This project demonstrates a small Java build and GitHub workflow.

## How this demonstrates GitHub usage
- Clone the repo locally to get a copy.
- Create a new branch for a change:
  git checkout -b fix-typo-or-add-feature
- Make small edits, run, and commit:
  git add .
  git commit -m "Describe your change"
- Push the branch and open a Pull Request on GitHub.
- Use Issues to request changes, track bugs, or propose enhancements.
- Merge the PR after reviews to practice collaboration.

## Contributing
- Fork the repository.
- Create a branch for your changes.
- Make changes and run the program locally to verify.
- Open a Pull Request with a clear description of what you changed and why.

Tips:
- Keep changes small and focused.
- Add comments to help newcomers understand any non-obvious code.

## Issues & Support
- Use the GitHub Issues tab to report bugs or request features.
- When opening an issue, include steps to reproduce and any error messages.

## License
No license file is included by default. If you want to make this project open-source, add a LICENSE (for example, MIT) to clarify how others can use your code.

## Contact
Maintainer: YousufNotSoCool (https://github.com/YousufNotSoCool)

Happy learning — use this repo to practice Git and Java builds!
