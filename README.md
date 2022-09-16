# juleskzl-github.io

```
git clone https://github.com/JulesKzl/juleskzl-github.io.git
cd juleskzl-github.io
npm install -g gatsby-cli
npm install gatsby gh-pages --save-dev
gatsby new my-new-blog https://github.com/gatsbyjs/gatsby-starter-blog
cd my-new-blog
gatsby develop
npm run deploy  
```

Add to package.json
```
    , 
    "scripts": {
        "deploy": "gatsby build && gh-pages -d public -b main"
    }
```