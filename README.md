# Project 6: List with Retreat

CSE 2231 — Autumn 2026

Eclipse project: **ListWithRetreat**

Starter files imported from the course-provided `ListWithRetreat.zip`. Assignment implementation and additional tests have not been completed.

## Open in Eclipse

1. Clone this repository.
2. Choose **File > Import > General > Existing Projects into Workspace**.
3. Select this repository directory as the root and import **ListWithRetreat**.
4. Ensure Eclipse has the course Java setup: the `OSU_CSE_LIBRARY` classpath variable, JUnit 4, and the OSU Checkstyle configuration. The supplied project also references the course FindBugs plugin.
5. Enable assertions (`-ea`) in the JUnit launch configuration.
6. Run `test/List3Test.java` as a **JUnit Test** after implementing the missing methods.

## Assignment work

- Complete `createNewRep`, the constructor, and kernel methods in `src/List3.java`.
- Implement `retreat` and `moveToFinish` directly with the doubly linked representation.
- Keep the required methods constant time, independent of list size.
- Add specification-based `retreat` tests at the end of `test/ListTest.java`.
- Replace the starter author placeholder with the team members' names.

The starter contains unfinished method bodies; this initial setup is not a completed solution. Generated classes from the ZIP are intentionally excluded so Eclipse builds from source.

[Assignment instructions](https://cse22x1.engineering.osu.edu/2231/assignments/projects/list-with-retreat/list-with-retreat.html)

Submit the whole Eclipse project as a ZIP according to the course instructions.
