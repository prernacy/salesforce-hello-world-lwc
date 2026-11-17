# Salesforce Lightning Web Components: Hello World

## Overview
A Salesforce DX project featuring custom Lightning Web Components (LWC), including the core helloWorld component along with supporting metadata and UI configurations. Built and deployed using Visual Studio Code and Salesforce CLI to demonstrate component architecture, data binding, and Lightning App Builder integration.

## Key Components and Structure
- *Lightning Web Component (force-app/main/default/lwc/helloWorld):*
  - helloWorld.html – Component markup template defining the user interface.
  - helloWorld.js – JavaScript controller managing reactive properties and logic.
  - helloWorld.js-meta.xml – Metadata configuration exposing the component to Lightning App Builder (App, Record, and Home pages).
  - __tests__/ – Jest unit testing suite for verifying component behavior.
- *Additional Workspace Modules:*
  - bikeCard/ & Event Comms/ – Supplementary LWC practice modules and event communication patterns.
- *Salesforce Metadata (force-app/main/default/):*
  - Configured project structure supporting custom objects, flexipages, page layouts, tabs, permission sets, Apex classes, and triggers.

## Tech Stack
- Salesforce Lightning Web Components (LWC)
- JavaScript (ES6+), HTML5, XML
- Jest (LWC Unit Testing)
- Salesforce DX / Salesforce CLI
- Visual Studio Code
