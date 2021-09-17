
## Requirements

- Node version 8 or higher
- A preconfigured Selenium Grid, preinstalled browser driver or cloud provider account



## Quick start

Choose one of the following options:

1. Download the latest stable releaseo r clone the git repo


2. Install the dependencies (`npm install`)



# Features (scenarios) tested:

- Cart (Add item to the cart, Edit item quantity from the cart, Remove item from the cart)
- SignIn (SignIn with invalid email, SignIn with valid email and empty password, SignIn with valid email and wrong password, SignIn with valid credential  )
- QuickView (Check the Quickview informations)

# Running single feature
Sometimes it's useful to only execute a single feature file, to do so use the following command:

```sh
$ npx wdio wdio.conf.js --spec ./src/features/SignIn.feature
```
