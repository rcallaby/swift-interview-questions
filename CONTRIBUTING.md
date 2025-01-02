# Contributing to Swift Interview Questions

Thank you for considering contributing to the **Swift Interview Questions** repository! This project is dedicated to creating a comprehensive collection of technical interview questions for the Swift programming language on macOS. Whether you're a seasoned developer or a newcomer to Swift, your contributions are welcome and highly valued.

This document outlines the guidelines for contributing to this project to ensure consistency and maintain high-quality content.

---

## Table of Contents
- [How to Contribute](#how-to-contribute)
- [Code of Conduct](#code-of-conduct)
- [Types of Contributions](#types-of-contributions)
  - [Adding Questions](#adding-questions)
  - [Submitting Answers](#submitting-answers)
  - [Improving Existing Content](#improving-existing-content)
  - [Reporting Issues](#reporting-issues)
- [Style Guide](#style-guide)
- [Submitting a Pull Request](#submitting-a-pull-request)
- [License](#license)

---

## How to Contribute

1. **Fork the Repository**: Create a copy of this repository by forking it to your GitHub account.
2. **Clone the Repository**: Clone the forked repository to your local machine:
   ```bash
   git clone https://github.com/your-username/swift-interview-questions.git
   ```
3. **Create a Branch**: Create a new branch for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Make Your Changes**: Add your content or code in the appropriate section of the repository.
5. **Commit Your Changes**: Write a clear and descriptive commit message:
   ```bash
   git commit -m "Add: New question on optionals"
   ```
6. **Push to Your Branch**:
   ```bash
   git push origin feature/your-feature-name
   ```
7. **Submit a Pull Request (PR)**: Open a PR to the `main` branch of this repository. Follow the pull request template and provide a detailed description of your contribution.

---

## Code of Conduct

This project adheres to a [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you agree to uphold this code and foster a welcoming and inclusive environment.

---

## Types of Contributions

### Adding Questions
- Ensure your questions are relevant to Swift and technical interviews.
- Provide clear and concise wording.
- Questions can be theoretical, practical, or scenario-based (e.g., "What are the differences between structs and classes in Swift?").
- Add questions under the appropriate category (e.g., "Data Structures," "Concurrency," "iOS Development").

### Submitting Answers
- Provide detailed and accurate answers for questions.
- Include code snippets where applicable. Use proper syntax highlighting for Swift:
  
  ```swift
  let message = "Hello, Swift!"
  print(message)
  ```
- Please provide detailed explainations

### Improving Existing Content
- Enhance existing questions or answers for clarity or accuracy.
- Fix typos, grammar, or formatting issues.
- Add relevant references or links to official Swift documentation.

### Reporting Issues
- If you find a problem (e.g., incorrect answers, outdated content), please open an issue.
- Clearly describe the problem and provide suggestions for improvement, if possible.

---

## Style Guide

### General Guidelines
- Use proper markdown syntax.
- Avoid jargon unless widely understood in the Swift community.
- Write in American English.
- Follow consistent formatting for questions and answers.

### Question Format
```markdown
### Question
What is the difference between `weak` and `unowned` references in Swift?
```

### Answer Format

#### Answer
A `weak` reference is an optional reference that does not increase the reference count of an object, whereas an `unowned` reference is a non-optional reference that assumes the object will never be deallocated. For example:

```swift
class Owner {
    var pet: Pet?
}

class Pet {
    weak var owner: Owner?
}
```
Refer to the [Swift documentation](https://swift.org/documentation/) for more details.


---

## Submitting a Pull Request

- Ensure your PR description includes:
  - A summary of the changes made.
  - The type of contribution (e.g., new question, updated answer).
  - Any references or resources used.
- Link any related issues in the description (e.g., "Closes #42").
- Ensure your changes follow the [Style Guide](#style-guide).
- Be responsive to feedback during the review process.

---

## License

By contributing to this repository, you agree that your contributions will be licensed under the [MIT License](LICENSE).

---

Thank you for helping make this repository a valuable resource for Swift developers!

