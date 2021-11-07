# From Github
```
npm install
```
----

# Manual Process

## Create package.json file
```
npm init -y
```

## Install NPM packages
```
npm install -D tailwindcss postcss autoprefixer vite
```

## Add Dev Script to package.json
```
...
"scripts": {
    "dev": "vite"
}
...
```

## Configure Tailwind and PostCSS
Accept the command prompt
```
npx tailwindcss init -p
```

## Run Vite Server
```
npm run dev
```

## Option: Build Once Using Input and Output Parameters
```
npx tailwindcss -i css/tailwind.css -o build/tailwind.css
```
