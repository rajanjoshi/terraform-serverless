# My cat photo identification service

To deploy using Terraform:

 * Create a new project on Google Cloud with [billing enabled](https://cloud.google.com/billing/docs/how-to/modify-project), and launch [Cloud Shell](https://cloud.google.com/shell/docs/using-cloud-shell).
 * Clone this repo (or open automatically in [Cloud Shell][shell_link])

    ```shell
    git clone https://github.com/GoogleCloudPlatform/serverless-expeditions 
    cd serverless-expeditions/terraform-serverless
    ```

  * Build the base service container:

    ```
    gcloud builds submit
    ```

  * Initialize and apply the Terraform manifests: 

    ```
    terraform init
    terraform apply
    ```
 


