[![Build (Windows)](https://github.com/SAM-BIM/SAM_Template/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/SAM-BIM/SAM_Template/actions/workflows/build.yml)

# SAM_Template

<a href="https://github.com/SAM-BIM/SAM">
  <img src="https://github.com/SAM-BIM/SAM/blob/master/Grasshopper/SAM.Core.Grasshopper/Resources/SAM_Small.png"
       align="left" hspace="10" vspace="6">
</a>

**SAM_Template** is part of the **SAM (Sustainable Analytical Model) Toolkit** —  
an open-source collection of tools designed to help engineers create, manage,
and process analytical building models for energy and environmental analysis.

This repository provides a **standardised template for creating new SAM-BIM repositories**.
It defines the recommended project structure, configuration, licensing, and documentation
used across the SAM ecosystem to ensure consistency, maintainability, and traceability.

---

## Purpose

The template is intended to be used when:
- creating a new SAM module or integration repository
- standardising repository setup across the SAM-BIM organisation
- ensuring consistent licensing, CI configuration, and documentation

It includes baseline configuration for:
- repository structure
- GitHub workflows
- licensing and copyright headers
- README and contribution conventions

---

## How to use

1. Create a new repository using **SAM_Template** as the base.
2. Rename the solution, projects, and namespaces means.
3. Update `README.md` with the module-specific description.
4. Remove or adjust any unused components as required.

The resulting repository should follow the same conventions as other SAM-BIM modules.

---

## Resources
- 📘 **SAM Wiki:** https://github.com/SAM-BIM/SAM/wiki  
- 🧠 **SAM Core:** https://github.com/SAM-BIM/SAM  

---

## Development notes

- Target framework: **.NET / C#**
- Repository layout follows SAM-BIM conventions
- New or modified `.cs` files must include the SPDX header from `COPYRIGHT_HEADER.txt`

---

## Licence

This repository is free software licensed under the  
**GNU Lesser General Public License v3.0 or later (LGPL-3.0-or-later)**.

Each contributor retains copyright to their respective contributions.  
The project history (Git) records authorship and provenance of all changes.

See:
- `LICENSE`
- `NOTICE`
- `COPYRIGHT_HEADER.txt`
