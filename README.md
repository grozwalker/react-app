## Usage

### Scaffold raect application

With create-react-app:

```
mkdir your-folder
cd your-folder
docker run -it --rm -v $(pwd):/src grozwalker/react-app npx create-react-app ./
```

Run it:

```
docker run -it -p 9000:9000 -p 35729:35729 --rm -v $(pwd):/src grozwalker/react-app npm start
```