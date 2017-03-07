# DigiBP Camunda Boot Archetype

## Summary
Based on this project a Maven archetype for Camunda Spring Boot can be generated. 

## Create Archetype
Make sure that you are increase the version, before push a new archetype to the repository.   

### Generate Archetype from Project
```text
clean archetype:create-from-project -Darchetype.properties=archetype.properties
```

### Push to Maven Repository
Clone the gh-pages branch and copy your generated artifacts to a new version folder and commit & push.

## Creating a new Project
Create a new project using the archetype published here: https://digibp.github.io/digibp-archetype-camunda-boot

### Creating a new Project in IntelliJ

- Create new project `File > New > Project`
- Click Maven on the left hand side of the new project dialog
- Check `Create from archetype`
- Click the `Add Archetype` button
- Set `Group Id` to `ch.fhnw.digibp.archetype`
- Set `Artifact Id` to `digibp-archetype-camunda-boot`
- Set `Version` to `<the latest release version>`
- Set `Repository` to `https://digibp.github.io/digibp-archetype-camunda-boot`
- Click next and create the project

### Creating a new Project in Eclipse

#### Add a Remote Archetype Catalog 
- Open `Window > Preferences`
- Go to `Maven > Archetypes` and select `Add Remote Catalog...`
- Set `Catalog File` to `https://digibp.github.io/digibp-archetype-camunda-boot/archetype-catalog.xml`
- Click `OK` so the Archetype catalog is added to the list

#### Creating a new Project in Eclipse using the Catalog
- Create new project `File > New > Maven Project`
- Make sure `Create a simple project` option is not selected
- Click `Next` to navigate to `Select an Archetype` screen
- Select the `Remote https://digibp...` catalog from the `Catalog` dropdown 
- Select the latest archetype `digibp-archetype-camunda-boot` from the appearing list
- Click `Next` and create the project

## Releases

### 1.0.2

Fixing the Eclipse issue

### 1.0.1

Fixing the basic package

### 1.0.0

Initial version

## Maintainer
- [Andreas Martin](https://github.com/andreasmartin)

## License

- [Apache License, Version 2.0](https://github.com/DigiBP/digibp-archetype-camunda-boot/blob/master/LICENSE)