<h1>AWS Fundamentals - Final Task</h1>
<h3>Step 1: Both the repository and the bucket were created.</h3>

![Bucket created](images/image_S3.png)

<h3>Step 2: We enable the option to hosting static websites in the S3 bucket</h3>

![Bucket created](images/image_web.png)

<h3>Step 3: To give Github permission to deploy the code to Amazon S3, an IAM policy was created</h3>

![IAM created](images/image.png)
<p>The IAM user is called: "github", it gives full permissions to Amazon S3, additionally the access keys were created to use the policy in Github</p>

<h3>Step 4: We take the access keys and add them to Github in the secrets section</h3>

![Secret section](images/image_secret.png)

<h3>Step 5: We create the Github Actions workflow to deploy the code stored in the main folder</h3>

![Workflow](images/image_yml.png)

<h3>Step 6: We create the example HTML code and make a commit, let the workflow run</h3>

![Workflow in action](images/image_action.png)

<h3>Step 7: We go to the S3 bucket and make the index.html public using ACL</h3>

![index public](images/image_final.png)

<h3>Step 8: We go to the hosting link of the S3 bucket and see the HTML page</h3>

![Webpage](images/image_webpage.png)

