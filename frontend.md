# Frontend section

## Tech stack
* ReactJS
* CSS with TailwindCSS
* Call Backend API with Axios library
* UI Testing with Playwright

## Project structure

## AI tools
* Design User interface
  * Figma
  * Excalidraw
  * MakeReal
* Generate code
  * https://bolt.new/
  * https://lovable.dev/
  * https://v0.dev/
* IDE
  * VS Code + GitHub Copilot
  * Cursor 
  * Windsurf

## Coding guideline
* Use early returns whenever possible to make the code more readable.
* Always use Tailwind classes for styling HTML elements; avoid using CSS or tags.
* Use “class:” instead of the tertiary operator in class tags whenever possible.
* Use descriptive variable and function/const names. Also, event functions should be named with a "handle" prefix, like "handleClick" for onClick and "handleKeyDown" for onKeyDown.
* Implement accessibility features on elements. For example, a tag should have a tabindex=“0”, aria-label, on:click, and on:keydown, and similar attributes.
- Use consts instead of functions, for example, "const toggle = () =>"". Also, define a type if possible.