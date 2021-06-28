# Assessment for Frontend Position

Welcome, candidate! Here at Zappyrent our mission is to make renting a fast and convenient experience for tenants and safe for landlords. To achieve this, we also need beautiful and easy-to-use interfaces, designed to be understandable and easy to maintain.

Our frontend stack is based upon the [React](https://reactjs.org/) ecosystem; we use [Create React App](https://create-react-app.dev), [Next](https://nextjs.org), [Gatsby](https://www.gatsbyjs.com), [TypeScript](https://www.typescriptlang.org), [Styled Components](https://styled-components.com).

## Introduction

For this assignment what you are going to build is a single page JavaScript application, preferably with React. You can choose to use another UI library (e.g. Vue) if you feel more confident with it. You should use a little bit of css and magic 🪄 to create a responsive UI following our designer's mockups.

## Description

The user should be able to see a listing page (PLP) of 10 property items (apartaments).

The user should be able to filter the PLP according to the following fields: `available` and `type`. The user should be informed when no apartaments are showed beacuse of filtering options.

The following points will be considered plus:

- The user, clicking on an item of the PLP, should be able to view the details of that specific apartment in a modal window (a sort of detail page, PDP). This action must correspond to a change in the page url which must be unique for each item of the PLP. If the user lands directly on one of the specific URLs of the apartments, one should see the modal window already open, without the need for any click.
- Use of TypeScript (strict mode)
- Writing unit tests for the components created

## Assets

- [API endpoint](https://my-json-server.typicode.com/zappyrent/frontend-assessment/properties)
- [Design mockups](https://github.com/zappyrent/frontend-assessment/tree/main/mockups)

## Submission

You can submit your work through a [GitHub](https://github.com) repository.
The code must be available to us in order to evaluate your submission. If you prefer to keep your repository private, please make sure you are granting access to [Zappyrent's GitHub user](https://github.com/zappyrent).

Your work should be accompanied by a documentation page explaining how we can run the application locally after cloning it and some of the technical solutions you have taken if you think this is the case, or whatever you think is relevant to us.

## Evaluation

Our goal is to find answers to these questions:

- Can you master your working environment?
- Can you find simple and elegant solutions for everyday problems?
- Can you interpret the designer's needs and translate them into an appealing interface?
- Can your write code that is clean, readable, testable and efficent?
