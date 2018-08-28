## Usage

### Scaffold react application

With create-react-app:

```
mkdir your-folder
cd your-folder
docker run -it --rm -v $(pwd):/src grozwalker/react-app npx create-react-app ./
```

### Run application

```
docker run -it -p 3000:3000 -p 35729:35729 --rm -v $(pwd):/src grozwalker/react-app npm start
```

Then open http://localhost:3000/ to see your app.

### Build Application

When you’re ready to deploy to production, create a minified bundle with 

```
docker run -it --rm -v $(pwd):/src grozwalker/react-app npm run build.

```

See more: https://github.com/facebook/create-react-app