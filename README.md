# Palaeoverse Workshop Template

## Purpose

The aim of this template is to provide a set structure for the organisation of content and materials for workshops run by [Palaeoverse](https://palaeoverse.org). It is established for the internal Palaeoverse team and is therefore specific to our needs. However, if useful, anyone is free to download or reuse the template for their own purposes.

## Instructions

So, we're doing another workshop are we!? Follow this helpful checklist to get started with this template.

1. On the main page of the repository, click 'Use this template' (top right) and select 'Create a new repository'
2. Enter a suitable repository name for the workshop, including the year and place/event (e.g. 2022-UCL-workshop, 2024-NAPC-workshop)
3. You are now ready to start creating your workshop content and materials. Start by updating the `README.md` file in the repository. You may wish to include information about the workshop (e.g. who it is run by, where and when, funding support, etc) and archiving information. Archiving should be done via continuous integration with Zenodo, implemented through version controlled releases (a manual process when all content has been prepared).
4. At this point you should edit the `index.qmd` in the top-level of the directory. There is placeholder text in the file, so just update accordingly!
5. You can now prepare your course materials. Each unit of the workshop should have a designated folder (with an informative name). Placeholder folders have been included (e.g. `01_UNIT_NAME`), which you can rename, delete, or add to as you please. **Important: within each unit folder, you should have an `index.qmd` file. This is the file you populate with workshop content. The `order` in the YAML should to be updated to reflect the order of content as 1 + n.** Within each unit folder, you can structure your materials as you please, but in general, we recommend being organised - this means having a dedicated folder structure such as `materials/data`.
6. Once you have completed preparing your content, sit back and relax while the [workshop website](https://workshop.palaeoverse.org) is updated!

## Folder structure and content

```bash
├── workshop-template
│   ├── README.md
│   ├── index.qmd
│   ├── 01_UNIT_NAME
│   │   ├── index.qmd
│   ├── 02_UNIT_NAME
│   │   ├── index.qmd
│   ├── 03_UNIT_NAME
│   │   ├── index.qmd
│   ├── 04_UNIT_NAME
│   │   ├── index.qmd
│   ├── 05_UNIT_NAME
│   │   ├── index.qmd
│   ├── images
│   │   ├── logo.png
├── LICENSE
├── workshop.Rproj
├── .github
│   │   ├── workflows
│   │   │   ├── quarto-publish.yml
└── .gitignore
```

![](images/logo.png)