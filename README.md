
# AI-PRESENTATION: An OpenAI Slide Deck Generator with Reveal.js

This Node.js application uses OpenAI's API to generate a slide deck on a given subject. The program prompts the user for a subject, uses OpenAI to generate an outline and slide contents, and then creates an HTML file with the slide deck using Reveal.js.

## Table of Contents

-   [Requirements](#requirements)
-   [Installation](#installation)
-   [Usage](#usage)
-   [License](#license)
-   [Contributing](#contributing)
-   [Credits](#credits)

## Requirements

-   Node.js 12.0 or higher.
-   An OpenAI API key.
-   The dependencies listed in the `package.json` file.

## Installation

Clone the repository and install the dependencies:

```js
git clone https://github.com/nooqta/ai-presentation.git
cd ai-presentation
npm install
``` 

All the required dependencies must be installed for the application to run correctly.

## Usage

This application requires an OpenAI API key, which should be set as an environment variable named `OPENAI_API_KEY`. You can set this in a `.env` file in the root directory of the project.

To run the application, use the following command:


```sh
node app.js
``` 

When prompted, input the subject of the slide deck. The program will generate an outline, slide contents, and then create an HTML file using Reveal.js.

The HTML file can be opened in a web browser and the presentation can be navigated using the arrow keys.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

## Credits

This project uses the following open-source packages:

-   [openai](https://www.npmjs.com/package/openai)
-   [dotenv](https://www.npmjs.com/package/dotenv)
-   [node-fetch](https://www.npmjs.com/package/node-fetch)
-   [slugify](https://www.npmjs.com/package/slugify)
-   [reveal.js](https://revealjs.com/)