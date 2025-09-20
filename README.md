# Tiptap Shadcn Vue 🎨

Welcome to the **Tiptap Shadcn Vue** repository! This project integrates the powerful Tiptap editor with Vue and Nuxt, providing a seamless experience for developers looking to implement rich text editing in their applications.

[![Releases](https://img.shields.io/badge/Releases-v1.0.0-blue)](https://github.com/JINKSY00101/tiptap-shadcn-vue/releases)

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Rich Text Editing**: Utilize Tiptap's extensive features for a rich text editing experience.
- **Vue and Nuxt Support**: Built specifically for Vue and Nuxt applications, ensuring compatibility and ease of use.
- **Customizable**: Easily customize the editor to fit your application's needs.
- **Lightweight**: Designed to be efficient and lightweight, ensuring quick load times.

## Installation

To get started with Tiptap Shadcn Vue, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/JINKSY00101/tiptap-shadcn-vue.git
   ```

2. Navigate to the project directory:
   ```bash
   cd tiptap-shadcn-vue
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

4. Run the development server:
   ```bash
   npm run dev
   ```

## Usage

To use Tiptap in your Vue or Nuxt application, follow these steps:

1. **Import the Editor**:
   Import the Tiptap editor in your component:
   ```javascript
   import { EditorContent, useEditor } from '@tiptap/vue-3';
   ```

2. **Set Up the Editor**:
   Create a new editor instance in your component's setup function:
   ```javascript
   const editor = useEditor({
     content: '<p>Hello World!</p>',
     extensions: [
       // Add Tiptap extensions here
     ],
   });
   ```

3. **Render the Editor**:
   Use the `EditorContent` component to render the editor in your template:
   ```html
   <EditorContent :editor="editor" />
   ```

4. **Handle Updates**:
   Listen for updates and handle the content as needed:
   ```javascript
   watch(() => editor.getHTML(), (newContent) => {
     console.log(newContent);
   });
   ```

For more detailed examples and advanced usage, please refer to the [Tiptap Documentation](https://tiptap.dev/).

## Contributing

We welcome contributions! If you'd like to help improve this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your forked repository.
5. Create a pull request.

Please ensure your code adheres to our coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any inquiries or issues, please reach out via GitHub or open an issue in the repository.

## Releases

To download the latest release, visit the [Releases](https://github.com/JINKSY00101/tiptap-shadcn-vue/releases) section. You can find the latest files to download and execute.

## Topics

- shadcn-tiptap
- tiptap
- tiptap-nuxt
- tiptap-v3
- tiptap-vue

Thank you for checking out **Tiptap Shadcn Vue**! We hope you find it useful for your projects. Happy coding! 🚀