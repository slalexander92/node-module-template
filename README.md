# The Spacebar Node Module Template

To start your new project, follow these steps

#### 1. Clone this repository

``` git clone https://github.com/SpacebarTech/node-module-template.git ```

#### 2. Install all the packages

``` npm install ```

#### 3. Create a new repository for your project

Do this on github, or send Tim a request to have it done.

#### 4. Remove template.git from your project

``` git remote remove origin ```

#### 5. Add your repository to your project

``` git remote add origin https://github.com/SpacebarTech/[YOUR_PROJECT].git ```

#### 6. Update your package.json so that all fields are filled out correctly

In your package.json, make sure that "name," "description," "repository," "bugs," and "homepage" are all the correct values for your repository, and not for template.git


#### 7. Update webpack.config.js

Change [MODULE_NAME] to the name you want

# Publish module

#### 1. Build dist
``` npm run build ```

#### 2. Push up to master
``` git add . ```
``` git commit -m “Initial release” ```
``` git push origin master```

#### 3. Publish package
Login
``` npm login ```

For private org
``` npm publish ```

For public
``` npm publish --access=public ```

If you have already published that version to npm you need to update the version
``` npm version major | minor | patch ```
major 1.0.0 -> 2.0.0
minor 1.0.0 -> 1.1.0
patch 1.0.0 -> 1.0.1

Update Repo
``` git add . ```
``` git commit -m "update to version x.x.x ```
``` git push origin master ```

# Update README.md
  1. Delete instructions
  2. use template below

[NAME OF MODULE]
========

[DESCRIPTION]

## Installation

    `npm install @spacebartech/[NAME OF MODULE]`
