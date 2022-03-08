# A modern CSS reset annotated

This project is a fork of Andy Bell's Modern CSS Reset. Modern CSS Reset is a tiny little reset that you can use as the basis of your CSS projects. You can read [Andy's breakdown on his site](https://hankchizljaw.com/wrote/a-modern-css-reset/).

## Why fork the original project?

1. To provide additional information on CSS resets for those unfamiliar with them and to provide a quick reference that more experienced users can refer to to refresh themselves as to why a certain property has a certain value

2. To offer a problem/solution format for quick and easy review of each reset item

3. To accomplish the above items via comments in the source file, rather than a second document

4. To provide citations that are both authoratative and **dated**. I often wonder whether a best practice is still a best practice. Knowing the source of the practice and the date it was created is very helpful in that regard.

## Is a reset really necessary? 

Maybe not. Chris Coyer of CSS Tricks [recently (Jan. 2022) wrote](https://css-tricks.com/notes-on-josh-comeaus-custom-css-reset/) that, if you're targeting mostly recent browswers,

    We’re in something of a new era of CSS resets where… you kind of don’t need one? There isn’t that many major differences between browsers on default styling, and by the time you’re off and running styling stuff, you’ve probably steamrolled things into place. And so perhaps “modern” CSS resets are more of a collection of opinionated default styles that do useful things that you want on all your new projects because, well, that’s how you roll.

That being said, there are still a few things that it might help to reset at the start, in addtion to the opinionated default styles Chris mentions.

## Installation

First, clone this repository:

```console
git clone https://github.com/julianjohannesen/modern-css-reset-annotated.git
```

Then, go to `modern-css-reset-annotated` directory:

```console
cd modern-css-reset-annotated
```

And now, you can minify and move the main reset to the `dist` by running:

```console
npm run build
```

That's it! 🎉

## Contributing

Contribute to the project, if you like. Read the [guidelines](./CONTRIBUTING.md). 

Best practices are ever evolving and new articles appear daily. If you have better information on a subject, please suggest it in issues, or create an issue and make a pull request.

## License

[MIT](./LICENSE)
