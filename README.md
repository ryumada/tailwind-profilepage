# Profile Page with TailwindCSS

The profile page using Tailwind as the style. There are some folders that I want you to know:

- `src` is the folder to build styles.
- `www` is where the production and static codes go.
- `app.yaml` Google App Engine (GAE) configuration file

## Features

There are some features I built using tailwindcss utility class.

### Bootstrap's `row` and `col`
- `flex` to use `display: flex`
- `flex-wrap` to implement wrapping if the width has met the parent size.
- `basis-X` to implement content sizing. I use `/12` size, for example if I want to make a container that contains two column. I will use `basis-9/12` for the column1 and `basis-3/12` for the column2.

## How to start

### Initialization
```bash
npm i
```

### Build the css file
```bash
npx tailwindcss -i ./src/css/styles.css -o ./www/css/styles.css
```
