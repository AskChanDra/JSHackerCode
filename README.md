# Gatsby Demoify

Main code for the demoify.com website.

# Using Gatsby Demoify

This guide will take you through setting up.

### Step 1: Starter installation

##### With `git clone`:

```sh
git clone git@github.com:AskChanDra/Demoify.com.git

cd demoify.com

yarn
```

### Step 2: Develop & Build

Once installed or cloned locally and all packages are installed you can begin developing your site.

```sh
# Run localhost
yarn dev

# Build your Gatsby site
yarn build
```

If wanting to use Netlify CMS as the content editor, then you need to be run the proxy in another terminal tab. Then visit
http://localhost:8000/admin to view the editor.
```sh
# Run proxy
yarn proxy
```