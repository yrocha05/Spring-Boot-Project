# Spring Boot Project

## VS Code

Open the repository root (the folder containing `course/`) as the VS Code
workspace. The Java project is the Maven project in `course/pom.xml`.

The workspace settings start the Java language server in Standard mode and
update the Java build configuration automatically when Maven files change.
After opening the workspace, wait for the Java language server and Maven import
to finish before using Java commands or autocomplete.

If Java commands or autocomplete remain unavailable:

1. Confirm that the Extension Pack for Java is installed and that JDK 25 is
   configured, as specified in `course/pom.xml`.
2. Run **Java: Reload Projects** from the Command Palette to refresh Maven
   projects without deleting the language server cache.
3. If reloading fails, check **Java: Open Java Language Server Log File** for
   the underlying import or JDK error.
4. Use **Java: Clean Java Language Server Workspace** only as a last resort;
   it rebuilds the index and can make the next startup slower.
