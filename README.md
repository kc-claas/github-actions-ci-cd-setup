# tech quiz ci-cd
[![Static Badge](https://img.shields.io/badge/License-MIT-blue)](./LICENSE)
## Description
This application contains continuous integration and deployment code for our tech quiz application. It adds functionality to automatically test the code when feature branches are merged into develop and automatically deploy the application when develop is pushed to main.

## Table of Contents
- [Usage](#usage)
- [License](#license)
- [Questions](#questions)

## Usage
Work should be performed on feature branches. When these branches are pull requested into develop, they will need to pass cypress testing before the merge can be completed. Only develop should be allowed to be pulled into main, and when code is merged into main, the live deployment on Render will be automatically re-deployed.

## License
This application is covered under the [MIT](./LICENSE) license

## Questions
Github: [kc-claas](https://github.com/kc-claas)

For additional questions, contact keithclaas@gmail.com
