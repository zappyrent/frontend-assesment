# Assessment for Frontend Position

Welcome, candidate! Here at Zappyrent our mission is to make renting a fast and convenient experience for tenants and safe for landlords. To achieve this, we also need beautiful and easy-to-use interfaces, designed to be understandable and easy to maintain.

Our frontend stack is based upon the [React](https://reactjs.org/) ecosystem; we use [Create React App](https://create-react-app.dev), [Next](https://nextjs.org), [Gatsby](https://www.gatsbyjs.com), [TypeScript](https://www.typescriptlang.org), [Styled Components](https://styled-components.com).

## Introduction

For this assignment what you are going to build is a single page JavaScript application, preferably with React. You can choose to use another UI library (e.g. Vue) if you feel more confident with it.

## Tasks

The main view your are going to build is a listing page (PLP), consisting of 10 property items (apartaments). 

You should build the PLP interface following the specifications of the graphic mockup and populating it consuming [this API endpoint](https://my-json-server.typicode.com/zappyrent/frontend-assessment/properties) through an asyncronous GET call.

The aforementioned endpoint can be filtered: you should then implement the designed filters by passing the appropriate query string to the API call. For example, acting on the "available" filter, you should only show the available apartments. If using the filter (or filters) the call does not return any apartment, you should return a warning message "no properties available for the specified filter".

The following points will be considered plus:
- Make sure that the user, by clicking on an item of the PLP, can view the details of that specific apartment in a modal window (a sort of detail page, PDP). This action must correspond to a change in the page url which must be unique for each item of the PLP. Similarly, if I land directly on one of the specific URLs of the apartments, I have to see the modal window already open, without the need for any click.
- Use of TypeScript (strict mode)
- Writing unit tests for the components created

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
