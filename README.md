# A modern, minimal, and easy to use boilerplate for developing in React with the least amount of dependencies.

## Why?

If you are tired of the immense, unnecessary boilerplate that is `create-react-app`, and you want something a lot lighter, and more barebones (while still being modern in its approach). Then this might be for you.

This will get you right into coding, and building out your ideas with the least amount of dependencies. Besides the benefits of starting with reduced dependencies, and a simpler file structure, it also uses a more modern approach with bundling. This keeps things simple and lightweight, yet still steps closer to shipping production-ready code. This was taken from [Ivad Yves HABIMANA](https://dev.to/ivadyhabimana)'s great article on the topic.

Outside of the expected required packages to run React (Babel, React), this uses Webpack for bundling files, as well as its dev server (served at `http://localhost:5000/`).

I also added the ability to use CSS from the jump (via the `css-loader` NPM package), so that I could just start creating quickly without too much additional setup. This can easily be replaced with your personal tastes (SASS, Tailwind, etc).

## Getting Started

Download or clone the repo and navigate to that folder in your terminal of choice. Simply run the command:

```console
npm start
```

That's it.

There is no need to `npm run build`, because that is taken care of with Webpack.

When you run the command, your browser should automatically open up `http://localhost:5000/`, but if not, just open up a new tab or window in your browser and type it in yourself. You should see this in your browser:

![Screenshot of localhost:5000](https://www.dropbox.com/scl/fi/1bglm2wu71boy5mgxeu1t/simple-react-boilerplate.png?rlkey=vp74g5db1xzsi7q39bb9bxgpd&raw=1 "Your localhost should look this.")

# Happy Coding!

### Credits

[Ivad Yves HABIMANA](https://dev.to/ivadyhabimana)
[Jonah B.](https://github.com/jonahvsweb)
