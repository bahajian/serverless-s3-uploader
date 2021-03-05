
<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/bahajian/serverless-s3-uploader">
    <img src="logo.png" alt="Logo" width="80" height="80">
  </a>
  <h1 align="center">FE File Uploader</h1>
  <p align="center">
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about">About</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About

# 

The client applications using pre-signed URL and picture file to upload an image to API.
This project created by Reactjs.




<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
For installing all dependencies please flow the instruction.

### Installation

* npm
    ```sh
    npm install 
    ```
* serve
    ```
    npm install -g serve
    ```

### Build project

```
npm test
npm run build
```

### Run and deploy Built project

```
npm start .or.
serve -s build
 .OR. serve -s build -l 5000
```


<!-- USAGE EXAMPLES -->
## Usage
Open a browser and run to this url: [localhost:5000](http://localhost:5000)

Then need to get the url from aws API gateway.
After running the url in postman or explorer, you will get a new url contain token. By pasting this url to url field and attaching the picture in attache space, you file or picture will uploaded to s3 under a unique uuid name.


<!-- CONTACT -->
## Contact


Project Link: [github.com/bahajian/serverless-s3-uploader](https://github.com/bahajian/serverless-s3-uploader)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [GitHub Sheet](https://github.com/bahajian)




<!-- LICENSE -->
## License

Distributed under the Bahram([TechHeed](https://techheed.ca)) License. See `LICENSE` for more information.
