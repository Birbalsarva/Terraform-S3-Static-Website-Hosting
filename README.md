 # Terraform-S3-Static-Website-Hosting

This repository contains a Terraform script to set up an AWS S3 bucket for hosting a static website. It includes configuration for creating the bucket, defining the website index and error documents, and uploading the necessary files.

**Getting Started**
1. Clone this repository: `git clone https://github.com/your-username/terraform-s3-static-website.git`
2. Open `main.tf` and update the `bucketname` variable with your desired S3 bucket name.
3. Run Terraform: 
   ```
   terraform init
   terraform apply
   ```

**Project Structure**
```
terraform-s3-static-website/
|-- main.tf
|-- variables.tf
|-- outputs.tf
|-- index.html
|-- error.html
|-- profile.png
|-- README.md
```

**Deployment**
- Follow the steps in "Getting Started" to deploy the static website on S3.

**Customization**
- Customize `index.html`, `error.html`, and `profile.png` to match your website's content.

**Contributing**
- Contributions, issues, and pull requests are welcome.

**License**
- This project is licensed under the MIT License.

For detailed instructions, please refer to the [README.md](https://github.com/your-username/terraform-s3-static-website/blob/main/README.md) file.
