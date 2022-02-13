# Code Kata

A kata is a way to practice fundamental elements of a craft in isolated, repeatable ways. The aim of katas is to improve
mastery of a craft with over time, making tiny improvements with each iteration. Over time, these katas can build on
each other and concentration can be placed at a broader scope, with knowledge that any element need has been habitually
ingrained and will be masterfully performed at any time.

Since software does not have in its root an element of physical control, we can not rely on muscle memory to guide us
through execution of tasks. Instead, the habits mastered will be how we craft our software, how we disassemble tasks
into small working elements--in essence, how we solve problems. By using constraints, we can unlock further challenges,
so the repetition of a kata does not become an exercise of writing steps from memory, but instead strengthens creativity
and understanding of the craft of software development.

Time spent on a kata should be time boxed--these are akin to warm-up exercises, after all. The goal is to instill habits
for daily use, not to solve a puzzle. Take what you have learned from the kata and apply it to your normal coding
practices. Use katas as a way to ensure you are thinking about software development correctly for yourself, so you can
continue on throughout your day in the right frame of mind. Any practice is a performance in itself; to treat practice
differently diminishes the experiences gained in practice from being used in performance, so make sure you are treating
these katas how you envision an ideal coding session.

## Usage

This template can be used as a skeleton to get you started with your kata journey. This particular template uses
JavaScript and Node.js with ESM modules, Yarn for package manager, and Jest for testing.

To install required dependencies, run `yarn install`. Tests can be run with `yarn test`. Since ESM modules are being
used, you will need to add `NODE_OPTIONS=--experimental-vm-modules` to the test runner if not running all tests with the
built-in yarn command. To check your code, you can use eslint by running `yarn lint`.

To start a new kata, create a file in the `src/` directory, and a corresponding test file in the `test/` directory.
example:

```bash
touch src/newKata.js && touch test/newKata.test.js
```

From here you can start writing your first test and start your kata journey.

## Katas to try:

Here are some links with great katas to try out.

* [Coding Dojo](https://codingdojo.org/kata/)
* [TDDBuddy](http://www.tddbuddy.com/)
* [Kata Log](https://kata-log.rocks/tdd)
* [TDD Manifesto](https://tddmanifesto.com/exercises/)