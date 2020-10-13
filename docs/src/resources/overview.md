# Overview

## Web Development Building Blocks

  ### HTML5 and Beyond

  HTML is the cornerstone of the mordern web. These companying resources will help grow and suppliment any
  current knowledge you may have about HTML and any new specs and improvements to the standard.

  ### CSS3 and Beyond

  CSS is what has made websites pretty. There are tons of pre-processors and fun innovations that have
  occured in tooling for css in the past few years in order to make it more accessible and maintainable to
  web developers. There will be resources for different pre-processors, the CSS spec it's self as well as
  blogs and other websites that stay current about CSS and where it is going.

  ### Javascript (ES5 -> ES2019)

  Javascript has really lead the rennesaince when it comes to innovation and workflow in the modern web.
  There are countless improvements to make javascript more accessible and easier to use by there being
  many new javascript frameworks to stream line a once fragmented javascript ecosystem on the web.
  There will be resources for the current and future javascript (ECMA) standards as well as blogs,
  documentation, and other resources that expose you to more of the javascript ecosystem.


## JS Frameworks

  ### Vue

  Vue is one of the new kids on the block. It has been around for only about 2 years and came from Evan You who for a
  while has been the soul maintainer and creator of Vue. He was a Google employee who was interested in created a modern
  javascript framework that solved many of the issues of prior frameworks. Vue is a mixture of many of the features and
  concepts from React and Angular with a few new features and ideas of their own. They have really simplified developing
  single page applications while giving developers a rich feature set and still supplying a small bundle payload.

  ### React

  React is the baby of Facebook. It was initially used for many of their internal projects in order to remove some of the
  reliance on php and other antiquated web technologies in favor of a javascript based platform. Facebook redid Messenger
  and several other main parts of Facebook and other websites that they own with React. Instagram was also re-written
  with React Native (Mobile). This shows how impactful javascript and JS frameworks have been and how widely used they
  are by large organizations in order to deliver content to many users. React is one of the best and most widely used
  javascript frameworks for making modular and high-performant web applications while maintaining an excellent developer
  experience.

  ### Angular

  Angular was the first major kid on the block when it comes to javascript frameworks. Many of the modern web development
  and framework paradigms were first put into a production ready framework from the Angular team that was founded from Google.
  Angular brought the idea of modular 'component' based design to the web by allowing developers to easy organize and structure
  their web applications based on a collection of components that form pages, instead of thinking of sites in terms of just pages.
  The popularity of Angular has been waining the past few years as their development cycle and fragmented releases have alienated
  many early adopters of the framework as well as other javascript frameworks out innovating and focusing more on improving the
  overall general javascript developer experience.

## UI Frameworks

  UI Frameworks have helped web developers focus less on the design of components and more on how a web application should function.
  Their general purpose is to relieve some of the burden of styling a web application, as well as empowering users to build fluid
  and responsive single page web applications that work well on many types of displays as well as having modern and visually appealing
  designs. These frameworks often cover base functionality that is require from such UI components such as search capabilities, caching,
  changing colors and other attributes for a given component. The functionalty for components is often changeable through props which are
  passed down from parent components. This allows a generic component to become more customizable for a particular usecase without requiring
  the web developer to implement common base functionalty and is necessary for every web application.

  ## Bootstrap

  Bootstrap was created by Twitter to be a responsive, mobile-first UI framework. It is really useful for rapidly protyping UI layouts. As well as
  creating consistent, responsive, and pleasant user experiences across any web applications. It is easy to use and covers most usecases that users have.
  It also provides helper utitlities and a well thoughtout CSS grid system and flexbox implementation that makes laying out user interfaces trivial.

  ## Material Design Lite (MDL)

  Material Design Lite was created by Google that allows users to add a Material Design look and feel to their websites. MDL was designed to be mobile first
  and follows the design principles around a 'flat' or 'material' design. There was extensive design and research put into this system that Google utilizes
  in many of it's child products. The MDL framework allows developers to create consistent, beautiful UI's that are intuitive and responsive for any device.
  This project is ever growing and we are expecting MDL 2 to be coming out soon which will iterate on the successes of MDL and improve some flaws.


## Package Managers

  Package managers as the name gives away are what is used to download and provision dependencies that are used in modern web
  development. They also keep track of the currently install packages as well as the versioning for each package. Package managers
  are one of the major reasons that the web development space has taken off as it has with the ease of installing and maintaining packages
  and versioning.

  ### NPM

  NPM is the native package manager for node. The npm registry boasts the world's largest software registry. NPM is what is used to install
  packages and dependencies for a given project. It's package.json file is what is used to track packages and their currently installed versions.
  The package.json is also used to store development and deployment alias' for tasks so that they are easily accessible for developers.

  ### Yarn

  Facebook developed Yarn in order to iterate on and improve npm's short comings such as caching packages, parallel dependency installs and verifying check
  sums before installs. It is still the new kid on the block, but it's registry and community support has been growing. With that said new versions of npm
  have tried to fix some of the underlying issues with their package manager.

## Tooling

  Tooling for the modern web has changed at a break neck pace. Every 2 years there is a new mover and shaker
  who has fixed the previous generations glaring flaws while often times introducing new issues and pain points.
  In this section we will cover some of the main tools that are crucial to modern web development.

  ### Webpack

  Webpack is a dependency bundler and injector for web development assets. It's output is traditionally a single javascript bundle. It has been a revolutionary
  tool as it has allowed developers to use whatever prepressors and plugins they want with minimal involvement after initial setup. Webpack has
  also brought in many cool development productivity tools such as hot module replacement (HMR). Webpack's feature set is easily extensible
  through it's growing plugin system.

  ### Babel

  Babel is javascript compiler that is often used in conjunction with webpack in order to allow new and proposed javascript functionality to be used before the (ECMA) standard is finalized. It is also used to poly-fill and support legacy browsers (IE), and to allow support for typescript and other javascript variants.