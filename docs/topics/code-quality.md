# Code Quality

## (CQ-100) High Maintainability

Requirements:

- All repositories *must* maintain their `master` branch at a Code Climate maintainability
  score of C or above.
- This score *must* be updated immediately after code is merged into the `master`
  branch.
- The score must be displayed on the README at the root of the repository.

Rationale:

- Code Climate provides a robust and industry standard measure for the
  maintainability of a code base. While this is only one of many possible
  measures, Code Climate provides a solid baseline for measuring code quality.

Exceptions:

- Programming languages not currently supported by Code Climate
- The following types of code are currently exempt from code maintainability:
    - Test code
    - Data migration code

---

## (CQ-200) Robust Test Coverage

Requirements:

- All repositories are required to maintain a test code coverage level of 30% and
  above for their `master` branch.
- Code coverage percentage *must* be updated at immediately after code is merged
  into the `master` branch.
- The coverage percentage must be displayed on the README at the root of the repository.
- All application code *must* be included in the coverage percentage, even if tests
  have yet to be written for the code.

Rationale:

- Code coverage is an indicator of how well test cases cover the codebase. While
  not a singular indicator of test quality, it is an important factor in ensuring
  that test cases cover a wide area of the codebase.

Exceptions:

The following types of code are currently exempt from code coverage:

- Test code
- Data migration code

---

## (CQ-300) Code Cleanliness

When code is no longer wanted, delete it. Never commit commented out code.

PRs should not be approved when these comments are found.

Rationale:

- Standard git usage already tracks removed code so that it's not lost.
- Leaving commented code leave the code base `littered` with distractions to
  the actual code flow.

Exceptions:

- None
