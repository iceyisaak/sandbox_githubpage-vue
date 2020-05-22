# sandbox_githubpage-vue

Test Deploying a react project on Github Page using the `gh-pages package`

---

> By installing the **gh-pages**, `gh-pages branch` is created automatically where the page will be created and hosted instantaneously.

### Steps to deploying with gh-pages

1. Run `npm run build`
2. Run `npm install gh-pages`
3. Add `"deploy": "gh-pages -d dist"` to the Script in the `package.json`
   - the `dist` folder, _by VueJS default_, contains files to be deployed on the Github Page
4. Add `"homepage": "https://<USERNAME>.github.io/<PROJECT-NAME_LOWERCASE>"` as a new property
5. Run `npm run deploy`
6. Access the link provided by Github under `settings > Options > Github Pages`

---

### Possible Errors & Solutions

- fatal: A branch named 'gh-pages' already exists.  
  https://github.com/transitive-bullshit/react-modern-library-boilerplate/issues/15
