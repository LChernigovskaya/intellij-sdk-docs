---
title: Program Structure Interface (PSI)
---

The Program Structure Interface, commonly referred to as just PSI, is the layer in the _IntelliJ Platform_ that is responsible for parsing files and creating the syntactic and semantic code model that powers so many of the platform's features.

* [PSI Files](/basics/architectural_overview/psi_files.md)
* [File View Providers](/basics/architectural_overview/file_view_providers.md)
* [PSI Elements](/basics/architectural_overview/psi_elements.md)

A very helpful tool for debugging the PSI implementation is the
[PsiViewer plugin](https://plugins.jetbrains.com/plugin/227-psiviewer).
It can show you the structure of the PSI tree, the properties of every PSI element and highlight its text range.
