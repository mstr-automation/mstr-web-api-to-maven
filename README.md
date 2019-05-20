# mstr-web-to-maven

A simple gradle build file to upload all MicroStrategy Web jar files to a Maven-like repo, for use in downstream projects.

## Usage instructions

Put the `MicroStrategy.war` file into the `src/resources directory`, and run the `gradle publish` task. Configure the repo details and the MicroStrategy version in `gradle.properties` (a sample file is provided).