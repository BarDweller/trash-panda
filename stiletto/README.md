Stiletto Parent Pom 

Intended to provide a "parent managed" approach to dependency & version management for child projects.

Can be used to set level of Spring Boot, and control versions of dependencies, and more.

Built from github directly as a Maven dependency using JitPack, the `jitpack.yml` on the project root
tells JitPack what to do when building the GitHub repo, resulting in the export of this parent pom as
a maven artifact.

Note that the maven coordinates declared by the parent pom in this folder are dummies, as JitPack will
overwrite them with the ones required to access the resource via the JitPack repository.
