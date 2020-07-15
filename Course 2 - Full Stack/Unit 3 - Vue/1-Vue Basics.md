# Vue Part 1

## Review

### Previous lessons:

Students have implemented asynchronous HTTP requests to an API, handled response codes, type checked response data, and mapped over lists of data. Prior to that, they also learned how to traverse and manipulate the DOM with vanilla JavaScript and initiate and capture DOM events.

### Prior knowledge of this topic:

Some students may have used a frontend framework in a bootcamp or other setting, but it likely would have been React, not Vue, and even then we can assume they only have limited understanding of the core fundamentals. For many students, this will be their first exposure to modern frontend frameworks.

### Review questions

## Overview

### Purpose

Direct manipulation of the DOM using vanilla JavaScript and/or jQuery is unmaintainable and error-prone at scale, which is why UI developers today leverage reactive frontend frameworks like React, Vue, and Angular. Therefore, we have only touched on JavaScript minimally and skipped over jQuery entirely, and will proceed directly to Vue.

By the end of this unit, students will be able to construct a fully-fledged Vue frontend using Webpack, TypeScript, and SCSS. In this lesson, they will gain an understanding of the Vue instance, component lifecycle, and build some simple reactive components. They will then use the Vue CLI to create a new codebase for their Library project.

### Preview

So far we've learned how to traverse and manipulate the DOM, but it's a pretty manual process, which is why these days, every development team leverages some kind of framework. There are 2 main types:

- Server-Side Rendering: Dynamic rendering of primarily static sites. Upon request, the server gets data and plugs it into a templating engine that which renders it into HTML, then sends it to the client.

Many people assume you're supposed to learn React, so let's talk a little about why anyone would want to learn Vue. First, let's go over the 3 most popular frontend frameworks and their key differences:

React:

- Most popular in terms of number of downloads
- Most in-demand in the job market
- Very fast, unopinionated, and not super chunky
- Massive ecosystem, most notably Redux and React Router
- React Native is extremely popular in mobile development
- Maintained by Facebook

Angular:

- Oldest, but has changed a lot since Angular 1 (aka AngularJS)
- Written entirely in TypeScript and enforces MVC architecture
- Still popular, but many consider it to be fading away
- VERY chunky and opinionated, with a notoriously steep learning curve
- Still the best choice for large teams building enterprise-level dashboard apps
- Maintained by Google

Vue:

- Comparitively small potatoes, but has most stars on GitHub
- Created by former Google employee Evan You, who based it off of Angular
- Most lightweight and (arguably) easiest to learn
- Ecosystem not as vast as React's, but Vuex and Vue Router are very high quality
- Vue 3 includes a lot more TypeScript support, plus great stuff like Composition API
- Crowd-funded via Patreon

If you learn Vue, you already know about 1/3 of Angular. And while Vue may not be the undisputed heavyweight React is, it's a great way to get introducted to reactivity, lifecycle, components, props, etc, which will all make learning React a lot easier, plus its increasing popularity makes learning Vue a great idea on its own.

## Presentation

### Demonstration ("I do")

### Exercise ("We do")

### Project ("You do")

## Summary

### Key points

### Post-assessments

## Self-Assessment and Lesson Reflection

### How did it go?
