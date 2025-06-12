# Palaeoverse Workshop Template

## Purpose

The aim of this template is to provide a set structure for the organisation of content and materials for workshops run by Palaeoverse. It is established for the internal Palaeoverse team and is therefore specific to our needs. However, if useful, anyone is free to download or reuse the template for their own purposes.

## Instructions

So, we're doing another workshop are we!? Follow this helpful checklist to use this workshop template.

- [ ] On the main page of the repository, click 'Use this template' (top right) and select 'Create a new repository'
- [ ] Enter a suitable repository name for the workshop, including the year and place/event (e.g. 2022-UCL-workshop, 2024-NAPC-workshop)
- [ ] You are now ready to start creating your workshop content and materials. Start by updating the README.md file in the repository. Include information about the workshop and eventually archiving information (e.g. adding a DOI).
- [ ] Now edit the `index.qmd`. There is placeholder text in the file, so just update accordingly!
- [ ] Now you are ready to update the `*_UNIT_NAME.qmd` files. 
- [ ] ...

## Folder structure and content

```bash
├── workshop-template
│   ├── README.md
│   ├── index.qmd
│   ├── 01_UNIT_NAME.qmd
│   ├── 02_UNIT_NAME.qmd
│   ├── 03_UNIT_NAME.qmd
│   ├── 04_UNIT_NAME.qmd
│   ├── 05_UNIT_NAME.qmd
│   ├── images
│   │   ├── README.md
│   ├── materials
│   │   ├── README.md
│   │   ├── 01_UNIT_NAME
│   │   │   ├── README.md
│   │   ├── 02_UNIT_NAME
│   │   │   ├── README.md
│   │   ├── 03_UNIT_NAME
│   │   │   ├── README.md
│   │   ├── 04_UNIT_NAME
│   │   │   ├── README.md
│   │   ├── 05_UNIT_NAME
│   │   │   ├── README.md
├── LICENSE
├── workshop.Rproj
├── .github
│   │   ├── workflows
│   │   │   ├── quarto-publish.yml
└── .gitignore
```

![](https://palaeoverse.org/images/logo.png)