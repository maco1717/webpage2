# Basic website

Decide if we are going to use static HTML+CSS+JS code or create a Jekyll site

We will start by creating a blank Jekyll project.

I have run the following commands to initialise an empty Jekyll project.
```
bundle init
jekyll new . --blank --force
```

Which created the following files. **NOTE** README.md had already been created.
```
.
├── Gemfile
├── Gemfile.lock
├── README.md
├── _config.yml
├── _data
├── _drafts
├── _includes
├── _layouts
│   └── default.html
├── _posts
├── _sass
│   └── base.scss
├── assets
│   └── css
│       └── main.scss
└── index.md

8 directories, 8 files

```

I build the site using the following command
```
bundle exec jekyll build
```

The folder structure now look like this
```
.
├── Gemfile
├── Gemfile.lock
├── README.md
├── _config.yml
├── _data
├── _drafts
├── _includes
├── _layouts
│   └── default.html
├── _posts
├── _sass
│   └── base.scss
├── _site
│   ├── README.md
│   ├── assets
│   │   └── css
│   │       ├── main.css
│   │       └── main.css.map
│   └── index.html
├── assets
│   └── css
│       └── main.scss
└── index.md

11 directories, 12 files
```

