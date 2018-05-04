## Cisco DevNet Learning Labs: pyats-labs

These self-paced interactive tutorials provide instructions for developers to to start with small, simple and linear test cases and easily scale towards large, complex and asynchronous test suites.

We write these labs for display within the [Cisco DevNet Learning Labs system](https://learninglabs.cisco.com).

Contributions are welcome, and we are glad to review changes through pull requests. See [contributing.md](contributing.md) for details.

Once approved, Cisco DevNet reviewers then create a release to publish through our Learning Labs system.

The goal of these learning labs is to ensure a 'hands-on' learning approach rather than theory or instructions.

## About these Learning Labs

* Learn about the benefits of pyATS
* Review some sample test cases
* Execute your first pyATS test job


## Contributing

These learning modules are for public consumption, so you must ensure that you have the rights to any content that you contribute.

Write your content in Markdown. DevNet staff reviews content according to the [Cisco Style Guide](http://www-author.cisco.com/c/en/us/td/docs/general/style/guide/Latest/stylegd.html). (Link available on Cisco VPN only.)

### Previewing content

After you have made your edits, you can simulate the user experience by running

  ```
  make preview
  ```
  from the root of this repository

#### Publishing Requirements

To create and publish a new lab, take the following steps:
- Add a new folder under `labs`.
- Create a JSON file with the same name as the `labs/`_folder_ name.
- Create markdown files named 1.md, 2.md, and so on; refer to those files in the `labs/`_folder_ JSON file.
- Ensure that the JSON file contains appropriate page titles and file references.
- Send a pull request to get the files committed and merged to `master` by a DevNet reviewer.

A DevNet reviewer then creates a release on the repository with the latest `master` and publishes through the admin interface.

#### Editors

You can write Markdown in a plain text editor, and desktop and Web-based options allow you to write and preview your work at the same time. We recommend Visual Studio Code [Download](https://code.visualstudio.com/) for these reasons:
- Lightweight environment for coding (or writing Markdown)
- Available on Mac OS, Linux or Windows
- Github Client integration
- Great Markdown preview features native in the editor
- Intuitive operation and structure

You can validate a JSON file by using the [online formatter and validator](https://jsonformatter.curiousconcept.com).

## Getting Involved

* If you'd like to contribute to an existing lab, refer to [contributing.md](contributing.md).
* If you're interested in creating a new Cisco DevNet Learning Lab, please contact a DevNet administrator for guidance.
