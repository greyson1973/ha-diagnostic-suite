# Home Assistant Diagnostic Suite

## File Naming Convention

**Document Version:** 2.0  
**Document Status:** Approved  
**Project Status:** Pre-Alpha  
**Approved By:** Project Founder & First Reader 
**Last Updated:** July 10, 2026

---

# Why This Document Exists

Every project needs a simple way to organize its files.

Imagine opening a filing cabinet where everyone used a different way of naming folders. Finding anything would quickly become frustrating.

This project avoids that problem by using one agreed-upon way of naming files and folders.

This document explains those rules.

It does **not** explain how Home Assistant works or how to use the software. Those topics are covered in other documents. Here, we are only deciding **what files should be called** so everyone organizes the project in the same way.

---

# Our Goal

These rules have three simple goals:

* Make files easy to find.
* Make it easy to recognize what a file is about.
* Keep the project organized as it grows.

---

# General Rules

Throughout the project we try to follow these simple rules:

* Choose names that clearly describe what the file contains.
* Use complete words instead of abbreviations whenever practical.
* Name similar kinds of files in similar ways.
* If another program requires a file to have a specific name, keep that required name.

---

# Official Project Documents

Some documents describe the project itself, such as its goals, rules, and organization.

These documents use:

* CAPITAL LETTERS
* Words separated by underscores (`_`)

Examples:

```text
PROJECT_CHARTER.md
PEOPLE.md
FILE_NAMING_CONVENTION.md
DOCUMENTATION_PHILOSOPHY.md
CONTRIBUTING.md
CODE_OF_CONDUCT.md
CHANGELOG.md
LICENSE.md
```

---

# Technical Documents

Documents that explain how something works use:

* lowercase letters
* words separated by underscores (`_`)

Examples:

```text
architecture.md
automation_design.md
diagnostic_engine.md
installation_guide.md
```

---

# Investigation Documents

Documents that record testing, troubleshooting, or research also use:

* lowercase letters
* words separated by underscores (`_`)

Examples:

```text
ac_state_reporting.md
sensor_latency.md
climate_entity_testing.md
```

---

# Project Logs

Project logs record progress as the project develops.

Examples:

```text
project_state.md
2026_07_10.md
ac_state_testing_session_01.md
```

---

# Folders

Folders use lowercase names.

When a folder name contains more than one word, the words are separated with underscores.

Examples:

```text
docs
governance
architecture
development_log
investigations
user_guides
integrations
tests
tools
```

---

# Files Required by Other Programs

Some software requires certain files to have specific names.

Those names should always be left unchanged.

For example, Home Assistant expects files with names such as:

```text
configuration.yaml
automations.yaml
scripts.yaml
scenes.yaml
```

You do **not** need to understand what these files do to understand this document.

They are listed here only because their names are required by Home Assistant.

Documents that explain Home Assistant and these files are provided elsewhere in the project.

---

# Images

Image files should have short, descriptive names.

Examples:

```text
climate_state_diagram.png
automation_flowchart.svg
dashboard_layout.png
```

---

# Source Code

Source code should follow the normal naming style of the programming language being used.

---

# Final Thoughts

These guidelines exist to help everyone organize the project in the same way.

A consistent project is easier to understand, easier to maintain, and easier for new contributors to join.
