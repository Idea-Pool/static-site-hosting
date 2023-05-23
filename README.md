# Guide to Hosting Static Websites

Hosting static websites, whether it's documentation or a React website, is a common practice. There are numerous options
available, both paid and free, catering to different levels of load and technical expertise.

This guide aims to compare several hosting options, providing examples and working templates to help you make an
informed decision. It begins with a general introduction to static website hosting and covers the following options:

- **GitHub Pages**: Host your static website directly from a GitHub repository.
- **AWS S3**: Utilize Amazon S3 for reliable and scalable static website hosting.
- **Azure Storage**: Leverage Azure Storage to deploy and manage your static website.
- **Google Cloud Web Hosting**: Deploy your static website on the Google Cloud platform.
- **VM Hosting**: Set up a virtual machine to host your static website.
- **Netlify**: Explore the powerful features of Netlify for static website hosting and continuous deployment.
- **Cloudflare**: Discover how Cloudflare can enhance your static website's performance, security, and availability.

This repository contains the source of this guide as well as the scripts for implementing the various solutions
discussed.

Given the ever-evolving nature of these options and the multitude of alternatives for hosting static websites, we
encourage you to contribute to this guide. **Your insights and expertise are valuable in keeping this resource
up-to-date and comprehensive.**

Thank you for your contributions and happy hosting!

## Development

The site is built using [MkDocs](https://www.mkdocs.org/).

### Prerequisites:

- Python 3.8+

### Install

1. Optionally, create a new [virtual environment](https://docs.python.org/3/library/venv.html).
2. Install dependencies:
    ```commandline
    pip install -r requirements.txt
    ```

### Build

* For development of the site, you can use the `serve` command: `mkdocs serve`. This will host the site locally on
  the `http://127.0.0.1:8000/`
* To build the final static site, you can use the `build` command: `mkdocs build`. This will generate the static site to
  the `site` folder.