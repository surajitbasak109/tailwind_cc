# First Tailwind Project
[Tailwind Officeial Website](https://tailwindcss.com/)

## How to install
1) First initialize npm project

```bash
npm init -y
```

2) Install tailwindcss
```bash
npm i tailwindcss --save
```

3) Then create style.css file inside the src folder and crate another style.css file inside the dist folder.

4) Now import following code into your `src/style.css` file:
```txt
@tailwind base;

@tailwind components;

@tailwind utilities;
```

5) Inside the package.json add this command under script
```json
{
    "scripts": {
        "build:css": "tailwind build src/style.css -o dist/style.css"
    }
}
```

6) Now whenever you run `npm run build:css` it will compile the tailwind css.

