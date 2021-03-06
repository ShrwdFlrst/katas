# Banking Kata

Congratulations! You've been selected to upgrade the banking systems of MegaBank Inc. using your favourite language, PHP!

They're aiming for simplicity this time around and accordingly have provided a minimal spec of what the system should do at MVP stage:

- Implement a simple account overview page that shows a users account history
- Implement an `Account` class with the following functions:
    - `deposit(int): void {}`
    - `withdraw(int): void {}`
    - `printStatement(): String {}`
 - The output of the `printStatement()` function should be in a similar format as:
 
 |Date|Amount|Balance|
 |----|------|-------|
 |24-12-2019|+500|500|
 |23-8-2018|-100|400|

Things to keep in mind for this Kata are: 
- The S from SOLID principals ([Single Responsibility Principal](https://medium.com/prod-io/solid-principles-takeaways-ec0825a07247))
- [Outside-In](https://www.codecademy.com/articles/tdd-outside-in) approach
- [Mocking](https://symfonycasts.com/screencast/phpunit/prophecy-mocking) dependencies
