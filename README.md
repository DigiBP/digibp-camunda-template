# DigiBP Camunda Boot Archetype

## Summary
Based on this project a Maven archetype for Camunda Spring Boot can be generated. 

## Create Archetype
Make sure that you are increase the version, before push a new archetype to the repository.   

### Generate Archetype from Project
```text
clean archetype:create-from-project -Darchetype.properties=archetype.properties
```

### Push to maven repository
Clone the gh-pages branch and copy your generated artifacts to a new version folder and commit & push.

## Create a new project
Create a new project using the archetype published here: https://digibp.github.io/digibp-archetype-camunda-boot

### Create a new project in IntelliJ

- Create new project `File > New > Project`
- Click Maven on the left hand side of the new project dialog
- Check `Create from archetype`
- Click the `Add Archetype` button
- Set `Group Id` to `ch.fhnw.digibp.archetype`
- Set `Artifact Id` to `digibp-archetype-camunda-boot`
- Set `Version` to `1.0.0`
- Set `Repository` to `https://digibp.github.io/digibp-archetype-camunda-boot`
- Click next and create the project

### Creating a new project in Eclipse

- Create new project `File > New > Maven Project`
- Make sure `Create a simple project` option is not selected
- Click `Next` to navigate to `Select an Archetype` screen
- Make sure `Include snapshot archetypes` is selected
- Click `Add Archetype` button
- Set `Archetype Group Id` to `ch.fhnw.digibp.archetype`
- Set `Archetype Artifact Id` to `digibp-archetype-camunda-boot`
- Set `Archetype Version` to `1.0.0`
- Set `Repository URL` to `https://digibp.github.io/digibp-archetype-camunda-boot`
- Click `OK` so the Archetype is added to the list
- Click `Next` and create the project

## Releases

### 1.0.1

Fixing the basic package

### 1.0.0

Initial version

## Maintainer
- Andreas Martin

## License

- https://github.com/DigiBP/digibp-archetype-camunda-boot/blob/master/LICENSE