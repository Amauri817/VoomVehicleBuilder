# Vehicle Builder

## Description [![License](https://img.shields.io/badge/License-EPL_1.0-red.svg)](https://opensource.org/licenses/EPL-1.0)
Your task is to update an existing TypeScript command-line application that builds and uses cars to have additional options for motorbikes and trucks. The application prompts the user to create a new vehicle or select an existing vehicle. After going through the creation process or the selection process, the user is able to perform certain actions with the selected vehicle. The user is returned to the actions menu after each action until they decide to exit the application.

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Installation
Download it from 'code', don't forget to npm i

## Usage
To showcase being able to use to terminal and cli so the user can create a vehicle, use an existing vehicle, and perform actions with the vehicles.

## License
Eclipse Public License 1.0 
 - This application is covered under the Eclipse Public License (EPL) is an open-source software license used primarily for projects developed by the Eclipse Foundation. It is designed to provide a balance between freedom and control, aiming to encourage collaboration while protecting the interests of contributors.


## Contributing
Amauri

## Tests
A lot

## Walkthrough
[Walkthrough](https://drive.google.com/file/d/1a7UvuNXYNVH6g85-Uwt4hZxkYck6kUCL/view?usp=sharing)

## Questions
Not many
For more personal questions, contact me at github.com/Amauri817
or email me @ brownamauri@icloud.com, I will try to reply as soon as I can.

## Acceptance Criteria

```md
GIVEN a command-line application that accepts user input
WHEN I am prompted to create a new vehicle or existing vehicle
THEN I can choose between the two options
WHEN I am prompted to choose the vehicle type during creation
THEN I can choose between car, truck, and motorbike
WHEN I am prompted for details about the vehicle
THEN I can enter the vehicle information
WHEN I have entered all the vehicle information
THEN I can use the created vehicle
WHEN I select an existing vehicle
THEN I can use the selected existing vehicle
WHEN I have created a new vehicle or selected an existing vehicle
THEN I can perform actions with that vehicle
WHEN I perform an action with a vehicle
THEN I see the result of the action in the command-line
WHEN I complete the process of performing an action
THEN I can perform additional actions until I choose to exit
```

## Additional Requirements

This Challenge combines many of the skills covered so far. In addition to the user story and acceptance criteria, we've provided some guidelines to help you get started.

Because this Challenge requires a video submission, refer to the [Full-Stack Blog video submission guide](https://coding-boot-camp.github.io/full-stack/computer-literacy/video-submission-guide) for guidance on creating and sharing a video.

Your application should use [Inquirer](https://www.npmjs.com/package/inquirer) for collecting input from the user. The application will be invoked by using the following command:

```bash
npm start