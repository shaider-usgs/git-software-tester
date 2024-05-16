---
title: "Creating Metadata for a Software Release"
teaching: 0
exercises: 0
---

:::::::::::::::::::::::::::::::::::::: questions 

- What is a code.json file?
- How do you create a code.json file?
- What are the required fields in the code.json file for a USGS Software Release?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Explain what a code.json file is and how it is used.
- Create a code.json file with the minimum required fields for a USGS Software Release
- Validate a code.json file against the defined schema
- Update a code.json file for a new version of the software

::::::::::::::::::::::::::::::::::::::::::::::::


::::::::::::::::::::::::::::::::::::: challenge

### Creating a code.json file

Write a code.json metadata file for [this example software release](https://code.usgs.gov).

:::::::::::::::::::::::::::: solution

### Solution

```json
ADD code.json code here
```

:::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::::::::::::::


::::::::::::::::::::::::::::::::::::: keypoints

* A code.json file is a file formatted in JavaScript Object Notation (JSON) and contains project metadata. The code.json file is saved at the top-level of the project. USGS compiles all of the code.json files for all public products into an inventory that is required by Federal policy.
* You can use a [code.json file template](https://code.chs.usgs.gov/software/software-management/-/raw/main/administrative_templates/code.json) to begin creating your project metadata.
The following fields should be included in your code.json file [COMPLETE]

::::::::::::::::::::::::::::::::::::::::::::::::


