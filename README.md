# A simple static-based articles system

[View Demo](https://ryanbriscall.github.io/SimpleStaticDocs)

Create your articles (as `.md` (Markdown) files) in the `content/` folder.  Then add them to the flat-file database `posts.js`

Lightweight, compatible, single-page web app (<abbr title="Single-page Application">SPA</abbr>) with no dependencies and near-zero additional HTTP requests.

Use this for starting your own collection of articles or documents (docs) on GitHub Pages!

If you want, you can run this from a folder of your website.  E.g. `/docs`

Check out our sister project, [SimpleStaticBlog](https://github.com/ryanbriscall/SimpleStaticBlog), to run your own `/blog` too!


## Usage

1. JavaScript (`posts.js`):
   ```js
   var posts = [
      '2020-06-06-Another-Document-With-Date',
      'Test-Demo-Second-Document-For-Docs',
      'My-First-Document',
   ];
   ```

2. Files:

   ```
   ./content/2020-06-06-Another-Document-With-Date.md
   ./content/My-First-Document.md
   ./content/Test-Demo-Second-Document-For-Docs.md
   ```

## Changelog

### 1.0.0

 - Initial release.

## License

Licensed under the MIT, see the `LICENSE` file for more details.
