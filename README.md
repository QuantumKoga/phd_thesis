# Electronic Structure Engineering of Group IV Crystals for Optoelectronic Applications

This repository contains a revised and expanded version of a dissertation entitled **“Electronic Structure Engineering of Group IV Crystals for Optoelectronic Applications – First-Principles Study.”**

The work focuses on theoretical investigations of electronic structure engineering in group IV semiconductors, with particular emphasis on methods that may enable or improve their use in optoelectronic applications.

## About this version

**This repository does not contain the original, unmodified dissertation as it was initially prepared or submitted.** Instead, it presents a revised and extended version of that work.

The text has been edited, reorganised, and supplemented. Particular attention has been given to the **theoretical background**, which has been substantially expanded to provide more detailed explanations of the physical concepts, computational methods, and theoretical foundations underlying the presented results.

The main research topics and results follow the original work, while the purpose of this version is to improve the clarity, completeness, and accessibility of its scientific discussion. It should therefore be regarded as an updated and extended version rather than an exact reproduction of the original dissertation.

## Scope of the work

The dissertation investigates several approaches to modifying the electronic properties of group IV semiconducting materials:

- **Strain engineering** – the influence of isotropic, uniaxial, and biaxial strain on structural, elastic, and electronic properties, including band gaps, deformation potentials, effective masses, and charge-carrier mobility.
- **Alloying** – the modification of electronic properties through changes in material composition, with particular attention to theoretical approaches used to describe alloy systems.
- **Structural modifications** – the influence of crystal structure on the electronic properties of group IV materials, including investigations of the wurtzite phase.
- **Quantum confinement and digital alloys** – preliminary investigations of layered Ge–Si systems and their electronic band structures.

The calculations are based primarily on **density functional theory (DFT)** and first-principles methods. The work also discusses the theoretical and computational procedures required to obtain and interpret the relevant material properties.

## Dissertation structure

The dissertation is organised into the following parts:

| Chapter | Subject |
|---|---|
| 1. Introduction | Motivation and general concepts of band structure engineering |
| 2. DFT | Density functional theory and its practical implementation |
| 3. Band structure engineering | Theoretical background for strain, alloying, structural modifications, and quantum confinement |
| 4. Strains | Structural, elastic, and electronic properties under strain |
| 5. Alloying | Theoretical description and electronic properties of alloy systems |
| 6. Structural Factor | Structural and electronic properties of group IV materials in the wurtzite phase |
| 7. Spatial Confinement | Preliminary study of Ge–Si digital alloys |
| Conclusions | Summary of the results, achieved goals, and remaining challenges |

The dissertation also includes appendices containing supplementary derivations, explanations, and theoretical material.

## Repository contents

The project is written in **LaTeX** and is organised into separate files for individual chapters and supporting material.

- `main.tex` – main document file.
- `01-Frontmatter/` – title page, abstracts, acknowledgements, and other introductory material.
- `02-Mainmatter/` – dissertation chapters and conclusions.
- `03-Backmatter/` – bibliography, appendices, acronyms, and symbols.
- `04-Includes/` – figures and other resources used throughout the document.
- `packages/` – LaTeX packages and custom document-class resources.
- `definitions.tex` – custom commands and notation.

## Building the document

The document can be compiled using a LaTeX distribution such as **TeX Live** or **MiKTeX**. An editor such as **TeXstudio** can be used to work with the project.

The main entry point is `main.tex`. The compilation process requires the usual LaTeX, bibliography, and glossary-generation steps. Depending on the local LaTeX installation, the sequence may be:

```bash
pdflatex main.tex
bibtex main
makeglossaries main
pdflatex main.tex
pdflatex main.tex
```

Some additional LaTeX packages may be required. They should be installed through the package manager provided by the chosen LaTeX distribution.

## Scientific context

The central motivation of this work is the possibility of engineering the electronic properties of group IV semiconductors while retaining compatibility with established semiconductor technologies.

The investigated approaches can modify fundamental band gaps, change their direct or indirect character, affect band-edge positions, and alter the effective masses of electrons and holes. These effects are relevant when considering materials for optoelectronic devices and other semiconductor applications.

The dissertation combines theoretical background, computational methodology, numerical results, and physical interpretation. It is intended to provide both a discussion of the investigated material systems and a broader introduction to the methods used to study their electronic properties.

## Citation

If you use this work or refer to its contents, please cite the dissertation and make clear which version of the document you consulted.

Bibliographic details and the appropriate citation format can be added here once the repository's publication information has been established.

## Acknowledgements

Special thanks to [@andywiecko](https://github.com/andywiecko) for creating the original LaTeX thesis template on which this project is based.

I am grateful for the time and effort put into developing the template, which provided the foundation for this work.
