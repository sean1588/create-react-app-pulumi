# Create React App - Deployed with Pulumi

This is a sample project generated with create react app. This demonstrates how to use Pulumi to deploy the site to AWS using the aws-static-website component with YAML. The Pulumi related infrastructure configuration can be found in the `infrastructure` directory. This will deploy the site to S3 along with a CloudFront CDN.

## Deploying to AWS

### Prerequisites
1. AWS account and credentials for access to AWS configured in your shell.
1. Pulumi installed on your machine. See our [getting started](https://www.pulumi.com/docs/get-started/aws/) guide for information on how to get this set up.

### Deploying with Pulumi
1. Navigate to the `infrastructure` directory of this repository.
1. Run `pulumi up` to start the deploy. There will be a preview shown in the CLI output of the resources that will be provisioned. Once confirmed the deployment process will begin.

## Create React Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

