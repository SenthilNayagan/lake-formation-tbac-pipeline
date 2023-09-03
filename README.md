# lake-formation-tbac-pipeline

Making use of a control or configuration file to fully automate AWS Lake Formation **tag-based access control** (**TBAC**) operations.

Using the version-controlled control file, this project automates the entire flow of granting LF-TBAC permissions on the Data Catalog resources to principals without the need to do so via the AWS console or APIs.

When designing a self-serve analytical platform, performing actions such as granting TBAC permissions via console, CLI, or APIs is not an acceptable choice. The complete process should proceed without anyone being involved.
