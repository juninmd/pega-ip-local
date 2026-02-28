```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure the consistent, maintainable, and high-quality development of the AGENTS repository. Adherence to these principles is mandatory for all AI coding agents.

## 1. DRY (Don't Repeat Yourself)

*   **Single Responsibility Principle:** Each agent should have a single, well-defined responsibility. Avoid creating multiple agents with overlapping functionality.
*   **Code Reuse:** Leverage existing components and libraries wherever possible.  When necessary, refactor code to improve reusability.
*   **Avoid Redundant Logic:**  Identify and eliminate duplicated code segments.  Refactor to reduce complexity.

## 2. KISS (Keep It Simple, Stupid)

*   **Simplicity:**  Strive for the simplest possible solution. Avoid overly complex logic or intricate algorithms unless absolutely necessary for a specific, well-defined task.
*   **Readability:** Prioritize code that is easy to understand. Use clear naming conventions and comments judiciously.
*   **Minimalism:** Only include what is absolutely required for the current task. Avoid unnecessary complexity.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Apply SOLID principles to agent design. Each agent should adhere to a single, cohesive design.
*   **Open/Closed Principle:**  Design agents to be open for extension, but closed for modification. This allows new features without affecting existing functionality.
*   **Liskov Substitution Principle:**  Ensure that derived classes can be substituted for their base classes without affecting the program's correctness.
*   **Interface Segregation Principle:** Each interface should define only the methods that implementation needs, reducing coupling.
*   **Dependency Inversion Principle:**  Dependency on other components should be minimized and replaced with abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Future-Proofing:**  Avoid adding features or logic that are not currently required.  It’s better to leave things out than to add them prematurely.
*   **Constraints:**  Clearly define the boundaries of each agent's functionality.
*   **Scope:** Limit the scope of each agent to its specific role.

## 5. Development Workflow & Best Practices

*   **Version Control:**  Use Git for version control. Commit frequently with concise, descriptive messages.
*   **Code Reviews:** Implement a mandatory code review process. Any proposed changes should be reviewed by at least one team member.
*   **Unit Testing:**  All agents MUST have at least 80% automated unit tests covering core logic.  Test cases should be comprehensive and cover edge cases.
*   **Test Coverage:**  Achieve a minimum of 80% test coverage across all agent files.
*   **Documentation:**  Provide clear and concise documentation for each agent, explaining its purpose, inputs, outputs, and any dependencies.
*   **Error Handling:**  Implement robust error handling to prevent unexpected crashes.
*   **Logging:** Implement logging for critical events and debugging.
*   **Configuration:**  Use configuration files to manage agent settings. Avoid hardcoding values.
*   **Modularity:** Design agents to be easily modularized and extended.

## 6. Code Length Constraint (180 Lines Max)

*   **Maximum Code Length:** Each file should not exceed 180 lines of code.
*   **Code Splitting:**  Consider code splitting techniques to break down large agents into smaller, more manageable components.

## 7.  Structure & Organization

*   **Modular Design:**  Organize agents into modular units that are loosely coupled.
*   **Clear Names:**  Use descriptive and consistent naming conventions for variables, functions, and classes.
*   **Comments:**  Provide clear and concise comments explaining complex logic and non-obvious behavior.

## 8.  Testing - Mocking Only**

*   **Mocking:** All tests must be performed using mocks or stubs.  No real dependencies or implementations should be used.
*   **Test Isolation:** Tests should be isolated and independent of each other.
*   **Testability:** Design agents to be easily testable through unit testing.

## 9.  File Structure

*   **Root Directory:**  The `AGENTS.md` file should be placed in the root directory of the repository.
*   **Directory Structure:**  Maintain a clear and logical directory structure within the repository.

## 10.  Future Considerations

*   **API Documentation:**  Consider integrating API documentation generation.
*   **Data Flow Diagrams:**  Visualize data flow and dependencies.
*   **Static Analysis:**  Implement static analysis tools to identify potential issues.

These guidelines are intended as a foundation for the development of the AGENTS repository. Continuous monitoring and refinement will be essential for maintaining high-quality code.
```