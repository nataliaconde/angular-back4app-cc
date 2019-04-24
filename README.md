# Back4App Angular

And you will find an integration with Back4App + Angular, which was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.3.

### Back4App account

If it is your first time with Back4App, [create a account](https://www.back4app.com/docs/platform/get-started/new-parse-app).

#### Replace Keys

Don't forget to paste your Back4App App ID and Javascript Key in the `App.js` file.

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Upload your code to the Back4App server

#### Step 1 - Create a Back4App subdomain

Log in to your Back4App account and go to the `My Apps` option and then click on `Server Settings`. After that, search for the Web Hosting and Live Query block and select Settings.

Now, tick the checkbox with tag `Activate Back4App Hosting` and insert the available Subdomain name you desired to have, and then click on the `Save`.

#### Step 2 - Configuring CLI

Then, you need to setup the Command Line Interface to Parse Server in your machine. Check [this guide](https://www.back4app.com/docs/platform/command-line-interface).

#### Step 3 - Compile your Angular project

Run `ng build --base-href`.

#### Step 4 - Move build folder to cloud code

Then, you need to move the created dist/ in the step above directory to the public folder at your Cloud Code project that was configured using Command Line Interface.

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
