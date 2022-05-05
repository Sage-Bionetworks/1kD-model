## 1kD Data Model

This is a data model started by the Data Modeling Group at Sage Bionetworks. 
We maintain the model in the [LinkML](https://linkml.io/linkml/index.html) YAML format.
For interop, this can be easily serialized to a number of other formats using LinkML's [generators](https://linkml.io/linkml/generators/index.html).
All generated formats are in the `gen/` directory.
Currently, the main generated format available is `.jsonld`, though other formats might be made available later as part of an automated build process.
Also refer to the `Makefile` for which/how other formats are generated.

Note: Do not edit files in `gen/` directly (they will be overwritten)! 

### For Contributors

- Install LinkML following directions at [linkml/install](https://linkml.io/linkml/intro/install.html). 
Note that the Docker image they offer is somewhat outdated, so if you want to use Docker for development, we recommend building the image using the `linkml/Dockerfile`.
- Create a branch from `main` for new features, etc., and use PRs to propose applying your changes.







