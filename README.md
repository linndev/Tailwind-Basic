Install and setup configuration
1. npm install -D tailwindcss
2. npx tailwindcss init
3. /** @type {import('tailwindcss').Config} */
    module.exports = {
      content: ["./src/**/*.{html,js}"],
      theme: {
        extend: {},
      },
      plugins: [],
    }
4. @tailwind base;
  @tailwind components;
  @tailwind utilities;
5. npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
