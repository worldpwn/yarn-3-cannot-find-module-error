# Answer
https://stackoverflow.com/questions/70446257/cannot-find-module-using-yarn-v-3/70446622#70446622

I figure out that the problem is that I have to run index.js using this command:

```
$ yarn node index.js
15
```

As I understand it uses PnP to resolve dependencies:

https://yarnpkg.com/features/pnp

https://yarnpkg.com/features/pnp#initializing-pnp

# Problem
I will do step by step installation of yarn from here  https://yarnpkg.com/getting-started/install

## Step 1 Install Corepack
![step 1](./images/step1.png)

## Step 2 Initializing your project
![step 2](./images/step2.png)
![step 2](./images/step2_init.png)

## Step 3 Install Lodash
![step 2](./images/step3.png)

## Step 4 Run hello world
![step 2](./images/step4.png)

## Step 5 Use lodash - ERROR
![step 2](./images/step5.png)
