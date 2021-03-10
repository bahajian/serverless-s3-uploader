
<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/bahajian/serverless-s3-uploader">
    <img src="logo.png" alt="Logo" width="80" height="80">
  </a>
  <h1 align="center">Serverless S3 Uploader</h1>
  <p align="center">
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about">About</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About

# 

The Serverless S3 Uploader allows you to upload JPG files to Amazon S3 buckets from your web applications using pre-signed URLs.

Important: this application uses various AWS services and there are costs associated with these services after the Free Tier usage - please see the [AWS  pricing page](https://aws.amazon.com/pricing/) for details.

```bash
.
├── README.MD                   <-- This instructions file
├── s3UploaderFunction          <-- Source code for the main lambda function
│   └── app.js                  <-- Main Lambda handler
│   └── testHarness.js          <-- For testing code locally
│   └── package.json            <-- NodeJS dependencies and scripts
├── template.yaml               <-- SAM template
```

Here's why:
* Your time should be focused on creating something amazing. A project that solves a problem and helps others
* You shouldn't be doing the same tasks over and over like creating a README from scratch
* You should element DRY principles to the rest of your life :smile:



A list of commonly used resources that I find helpful are listed in the acknowledgements.

### Built With

This section should list any major frameworks that you built your project using. 
* [Nodejs](https://node.com)
* [React](https://react.com)



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

## Installation

1. Need to install sam client on your machine.
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. To deploy the project please run:
    ```
    sam deploy --guided
    ```
    

<!-- USAGE EXAMPLES -->
## Usage

For using this app need to paste the url in browser or post man and will get the new pre sign url from BE. By copying this url to postman and attaching the binarry file to it, you can upload your file to s3 under uuid.jpg name.




<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/bahajian)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [GitHub Sheet](https://github.com/bahajian)




------------------------------------------------------------------------------------------------------------



## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

<!-- LICENSE -->
## License

Distributed under the Bahram([TechHeed](https://techheed.ca)) License. See `LICENSE` for more information.
