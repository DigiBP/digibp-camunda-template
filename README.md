# DigiBP Camunda Boot Project Template for Archetype

## Summary
Based on this project a Maven archetype for Camunda Spring Boot can be generated. 

## Procedure for Creating a new Version
1. Clone this repository and make your changes.
2. Make sure that you increase the version in the Maven `pom.xml`.
3. Generate the archetype from the project `clean archetype:create-from-project -Darchetype.properties=archetype.properties`.
4. Clone the gh-pages branch and copy your generated archetype files to the gh-pages branch.
5. Optional: `clean install archetype:update-local-catalog` and copy the entries to the `archetype-catalog.xml`.
6. Deploy the artifacts to the main folder of the gh-pages branch using `deploy -DaltDeploymentRepository=internal.repo::default::file://${basedir}`
7. Commit and push the gh-pages branch.

## Maintainer
- [Andreas Martin](https://github.com/andreasmartin)

## License

- [Apache License, Version 2.0](https://github.com/DigiBP/digibp-archetype-camunda-boot/blob/master/LICENSE)
