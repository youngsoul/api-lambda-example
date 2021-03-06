# CDK V2 Example creating an HttpApi to Lambda Function

It does not get easier than this, but it is still helpful to start out easy.

![TI](./media/title_image.png)


This repo contains a short example of how to use the v2/alpha CDK to create a simple HttpApi gateway proxy to a Lambda function using the latest ( 3/4/2022 ) CDK contructs

## AWS CDK V2 

https://aws.amazon.com/blogs/developer/experimental-construct-libraries-are-now-available-in-aws-cdk-v2/

### CDKv2 Python Reference

https://docs.aws.amazon.com/cdk/api/v2/python/index.html



### Welcome to your CDK Python project!

This is a blank project for Python development with CDK.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

This project is set up like a standard Python project.  The initialization
process also creates a virtualenv within this project, stored under the `.venv`
directory.  To create the virtualenv it assumes that there is a `python3`
(or `python` for Windows) executable in your path with access to the `venv`
package. If for any reason the automatic creation of the virtualenv fails,
you can create the virtualenv manually.

To manually create a virtualenv on MacOS and Linux:

```
$ python3 -m venv .venv
```

After the init process completes and the virtualenv is created, you can use the following
step to activate your virtualenv.

```
$ source .venv/bin/activate
```

If you are a Windows platform, you would activate the virtualenv like this:

```
% .venv\Scripts\activate.bat
```

Once the virtualenv is activated, you can install the required dependencies.

```
$ pip install -r requirements.txt
```

At this point you can now synthesize the CloudFormation template for this code.

```
$ cdk synth
```

To add additional dependencies, for example other CDK libraries, just add
them to your `setup.py` file and rerun the `pip install -r requirements.txt`
command.

## Useful commands

cdk bootstrap --profile pryan
- creates a cloudformation stack called:  'CDKToolkit'

 * `cdk ls`          list all stacks in the app
 * `cdk synth`       emits the synthesized CloudFormation template
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk destroy`     destroy this stack
 * `cdk diff`        compare deployed stack with current state
 * `cdk docs`        open CDK documentation

Enjoy!
