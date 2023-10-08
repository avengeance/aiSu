# Webpage Summarizer App

![Webpage Summarizer App](your-app-screenshot.png)

This is a webpage summarizer app that uses OpenAI's GPT to extract and summarize news or article content from a given URL. It is a useful tool for text mining purposes and can optionally translate the article content. The app leverages a powerful web scraping engine, ScrapeNinja.net, with high-quality rotating proxies to access web content.

## Features

- Extract and summarize news or article content from any URL.
- Optionally translate the article content.
- Utilizes OpenAI's GPT for high-quality summaries.
- Supports React and Redux for efficient state management.

## Dependencies

- [@reduxjs/toolkit](https://github.com/reduxjs/toolkit): State management library for React applications.
- [react](https://reactjs.org/): JavaScript library for building user interfaces.
- [react-dom](https://reactjs.org/docs/react-dom.html): Provides DOM-specific methods for working with React.
- [react-redux](https://react-redux.js.org/): Official React bindings for Redux.
- [@types/react](https://www.npmjs.com/package/@types/react): Type definitions for React.
- [@types/react-dom](https://www.npmjs.com/package/@types/react-dom): Type definitions for React DOM.
- [@vitejs/plugin-react](https://github.com/vitejs/vite/tree/main/packages/plugin-react): Vite plugin for React support.
- [autoprefixer](https://github.com/postcss/autoprefixer): PostCSS plugin to parse CSS and add vendor prefixes.
- [postcss](https://postcss.org/): CSS post-processing tool.
- [tailwindcss](https://tailwindcss.com/): Utility-first CSS framework.
- [vite](https://vitejs.dev/): Build tool for JavaScript and TypeScript projects.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/avengeance/aiSu
   ```

````

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Access the app in your browser at `http://localhost:3000`.

## API Integration

This app integrates with the ScrapeNinja.net API to extract news/article content from URLs. You will need to obtain API credentials from ScrapeNinja.net and set them up in your app's configuration.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thank you to the [ScrapeNinja.net](https://scrapeninja.net/) team for providing the web scraping capabilities used in this app.

Feel free to modify this README to add more specific details about your project, usage instructions, and any other relevant information.

```
````
