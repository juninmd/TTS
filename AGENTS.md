```markdown
# AGENTS.md - AI Coding Agent Guidelines

These guidelines outline the approach for developing AI coding agents within this repository. Adherence to these principles is crucial for maintaining code quality, scalability, and maintainability.

## 1. DRY (Don't Repeat Yourself)

*   **Modular Design:** Each agent component should have a single, well-defined responsibility.
*   **Abstraction:** Utilize abstraction to hide internal complexities and create reusable components.
*   **Single Responsibility Principle:** Each module should focus on a single, logical function.
*   **Template Code:** Employ templates for common structures (e.g., agent data structures, utility functions) to reduce repetition.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimalism:** Strive for the shortest possible code without sacrificing clarity.
*   **Readability:** Prioritize code that is easily understood by others.
*   **Simplicity:** Design algorithms with straightforward logic.
*   **Avoid Over-Complexity:** Resist introducing unnecessary features or convoluted constructs.

## 3. SOLID Principles

*   **Single Responsibility Principle:**  Each class/module should have a single, well-defined purpose.
*   **Open/Closed Principle:**  New features or modifications should be implemented as separate, independent components without modifying the core code.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:**  Clients should not be forced to depend on methods they do not use.
*   **Dependency Inversion Principle:**  High-level modules should be dependent on low-level modules, not vice versa.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Avoid Over-Engineering:** Don't implement features or code that isn't currently required.
*   **Focus on Functionality:** Prioritize delivering the core functionality first.
*   **Refactor Later:**  Don't prematurely refactor code; focus on solving the current problem.

## 5. Development Workflow

1.  **Planning:** Define the agent's purpose, requirements, and expected inputs/outputs.
2.  **Component Creation:** Develop each agent component as a separate, self-contained unit.
3.  **Unit Testing:** Write tests for each component to ensure correctness.
4.  **Integration Testing:** Test the interaction between components.
5.  **Code Review:** Peer review of code to ensure adherence to principles and best practices.
6.  **Documentation:**  Document the agent's purpose, inputs, outputs, and any relevant dependencies.
7.  **Continuous Integration (CI):** Automate testing and building processes.

## 6. Code Length Constraint (180 lines max)

*   All code must be strictly adhered to this limit.

## 7. Test Coverage (80%+)

*   Automated tests must cover 80% of the agent's functionality.
*   Unit tests must pass with a high percentage of cases.
*   Integration tests must accurately simulate expected interactions.

## 8. Data Handling

*   All data interactions must be encapsulated within functions, avoiding global state.
*   Data should be represented using appropriate data structures (dictionaries, lists, etc.).
*   Error handling must be implemented effectively.

## 9.  Environment Considerations

*   The agent should be designed to run effectively across different environments.
*   Consider the impact of environmental variables on agent behavior.
*   Robust error handling should be implemented to gracefully handle environment issues.

## 10. Code Style & Formatting

*   Use a consistent code style (e.g., PEP 8).
*   Employ consistent indentation and spacing.
*   Add comments to explain complex logic.

## 11.  Maintainability & Readability

*   Use meaningful variable and function names.
*   Break down complex logic into smaller, manageable functions.
*   Document code thoroughly.


```