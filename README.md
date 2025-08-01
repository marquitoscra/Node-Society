# Node Society
Welcome to Node Society, a collaborative Houdini community dedicated to making the learning journey smoother for everyone.

Our goal is to bring artists together to share knowledge, tips, and resources that help demystify Houdini’s complexities. Whether you’re just getting started or looking to deepen your understanding, this space is built to support your growth through community-contributed files and examples.

By contributing and learning together, we aim to lower the barrier to entry and create a space where everyone can thrive. We truly believe that everyone deserves the opportunity to bring their imaginations to life and in doing so it will push everyone to improve further. 

## Finding Projects
The best way to find projects that you are looking for is by using the search functionality built into [node-society.com.](https://node-society.com/) The website pulls all of the submissions from the github repository and allows users to search through all of the metadata and filter to exactly what they are looking for.

## Who Can Contribute

Anyone is welcome to contribute to the community. This project is focused on education and skill development, so contributions should be made with the intent to help others learn Houdini more effectively.

To support that goal:

All submissions must follow the rules outlined in [Contributing](./CONTRIBUTING.md) and include a metadata file that exactly matches the format generated by the official upload script.
Submissions with custom or incorrectly formatted metadata will not be accepted.

We strongly recommend using the [community upload tool](./Upload%20Tool/) to prepare your contribution.
This tool automatically generates all required metadata and ensures your submission follows the correct structure. While use of the script is not mandatory, it greatly streamlines the process and helps maintain consistency across the repository. If you don't want to use the tool to upload you can still use it to generate your metadata file to ensure it follows the correct structure.

Please include comments or notes inside your .hip files wherever possible.
Clear explanations of node networks, parameters, and workflows significantly increase the educational value of your contribution.


The goal of every submission should be to help others learn Houdini more effectively. Thank you for contributing to the community.

## Upload Tool

The Upload Tool is a standalone utility designed to streamline the process of submitting Houdini projects to the Node Society repository. It automatically generates the required metadata, ensures correct folder structure, and creates a pull request to the repository on your behalf.

Using this tool helps maintain consistency across submissions and significantly reduces the chances of formatting errors. While not mandatory, it is strongly recommended for all contributors.

## SmartScreen Warning on Windows

When downloading or running the Upload Tool executable, you may encounter a Windows SmartScreen warning that marks the file as potentially unsafe. This is expected behavior for new applications that haven’t yet been reviewed by Microsoft’s reputation systems.

To proceed:

1. Click **"More info"** when the warning appears.
2. Click **"Keep"** on the prompt.
3. Run the tool as normal.

This does not mean the file is unsafe—only that it is not yet commonly downloaded.

## Source Code Transparency

The full Python source code for the Upload Tool is available in the [Upload Tool](./Upload%20Tool/) folder. You are welcome to inspect, audit, or run the script manually if you prefer not to use the compiled version.

This transparency ensures that the tool remains trustworthy and adaptable for contributors who wish to see exactly how their data is handled.

## Creating a Github Token
The Upload Tool requires a github token from your account with public repo access in order to submit files on your behalf. You can generate a token by going to [github.com/settings/tokens](https://github.com/settings/tokens).

To generate a token click on Generate bew token and select the Generate new token (classic) from the drop down.

Give your token a name and set an expiration date.

**Important** Under the Scopes select public_repo. Without this the tool will not be able to submit. Your access should look like this:

![repo_access](https://github.com/user-attachments/assets/193c8b0d-948f-4d97-8beb-568f107248f8)

Click generate token at the bottom of the page.

Copy the token and paste it into the Upload Tool. Github will not show you this token again so save it somewhere if you don't want to generate another in case you accidentally delete it. The Upload Tool will store your token until you clear it once you submit the first time.

## Usage

The files shared within this community are intended solely for educational purposes. If you're contributing, please keep in mind that the goal is to support others in learning and developing their Houdini skills.

This community is not a platform for self-promotion, portfolio exposure, or driving traffic to external sales funnels. Contributions should be made with the intent to educate, inspire, and elevate others.

Please share resources that reflect the spirit of collaboration and growth.

With that in mind, you are allowed to include a AuthorInfo.txt file that includes links to your social media, website, Patreon etc.

## License

All contributions to this repository are covered under the [Community Houdini File License](./License.txt) by default.

Contributors may override this license by including a clearly labeled `LICENSE` file within their submission. In such cases, that file’s terms will apply to that specific content only.

