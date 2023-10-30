# ECE444-F2023-Lab5 - Tenzin Mahabir

## Unit tests written by me for Blue Surf

Tests for Flask backend login route:
- [test_login_route](https://github.com/ECE444-2023Fall/Blue-Surf/blob/0bbc382c404f2d25c1f97929aad79925bcc3e891/backend/tests/test_app.py#L11C5-L14C62)

Tests for React frontend SearchBar component:
- [fetches suggestions on user input change](https://github.com/ECE444-2023Fall/Blue-Surf/blob/91163c1c85e572fa9b9ae571785a02b2e10af9fe/src/components/SearchBar.test.js#L43C3-L56C6)
- [triggers search on pressing Enter](https://github.com/ECE444-2023Fall/Blue-Surf/blob/91163c1c85e572fa9b9ae571785a02b2e10af9fe/src/components/SearchBar.test.js#L59C3-L72C6)

## Pros and Cons of Test-Driven Development (TDD)

### Pros

- Elevated Code Quality: TDD prioritizes meeting specific test criteria, resulting in software of higher quality that is more robust and maintainable.

- Reduced Bugs: By identifying and addressing issues early in the development process, TDD leads to fewer bugs as tests are created prior to the code.

- Improved Design: TDD encourages a more modular and adaptable design, facilitating better software architecture as developers write code that is easily testable.

- Refactoring Confidence: With a suite of tests in place, developers can confidently refactor code without compromising the system's stability.

- Long-Term Development Efficiency: While the initial stages might seem slower, TDD often accelerates the development process by reducing time spent on debugging and rework.

### Cons

- Initial Learning Curve: Adapting to TDD requires a shift in mindset and might pose challenges, especially for developers new to this methodology.

- Time Consumption: Writing tests before coding can be time-intensive, particularly in the early stages of development.

- Test Quantity and Maintenance Challenges: Striking a balance in the number of tests and maintaining the test suite can be complex, leading to potential over-testing or under-testing.

- False Sense of Security: Passing tests only confirm the code's behavior based on written tests, not the absence of all bugs or logical issues.

- Test Maintenance: Test suites need consistent updates as the codebase evolves, demanding effort comparable to maintaining the code itself.
