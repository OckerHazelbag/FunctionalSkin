# Open Hardware Documentation Template

This repository template presents a structure for describing relatively small hardware projects.  
The main goal of this template is to simplify starting such a repository at an early stage of the project and motivate team members to regularly update their documents in a structured way. 
To keep it agile, filling in the necessary information for the first version repository should not take more than 10 minutes.

[How to use Markdown, GitHubs formatting language](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)

_Tips on how to use the template are put in italic. Remove these as soon as they are irrelevant._

_This introduction paragraph, right under the title, should explain the context of the project as well as why has it been initiated._

## Main features
_This subsection is a very brief introduction to the context and key features of your project that could be interesting for a user in search of a solution_

The most important file in the repository is the README.md in the root folder of the reposity. In this main README try to present only the main information for the viewer to get started. 
Detailed updates or build instructions are better suited for the subfolders such as `./Hardware` or `./Results`.

Next to the README file, a basic folder structure is presented in this repository. 
Each subfolder contains a `_readme.md` file that explains the conventions and purpose of that folder for the (future) collaborators to keep it tidy.

This template is adjusted to the typical needs of a hardware project made for research or education. 

The purpose of each subfolder is explained below:
+ [Hardware](Hardware/_readme.md): Contains all the information related to the hardware construction part of the prototype. Build instructions, (binary) design files and components. Use subfolders for more complex assemblies.
+ [Documents](Documents/_readme.md): Contains all general documents surrounding the project: images, background information, literature sources, hazard documents.
+ [Results](Results/_readme.md): Show your prototype in action, if possible including experimental results.
+ [Software](Software/_readme.md): For hardware projects that have an operating software or firmware.

## Build instructions
_Guide the reader with the order of browsing your project repository for an optimum building experience_
 
When you want to start a new repository, it is better that you copy this repository to your project repository and start by changing all the description.
All instructions and (sub)headers are suggestions. You can change the style, order, or composition as you see necessary. 


## Outcomes
_Here you can list the outcomes of the project that you would like to hightlight. It does not need to be an exhaustive list_

We will list some best practices and good examples from projects that have used this template for their documentation.

## Team
_Even though platforms such as github show a list of user accounts for contributors for a project or repository, the past contributors or external collaborators also deserve a place here_

+ Project initiator: Sanli Faez @sanlifaez
+ Contributors:
	+ _add a list of main contributors_


## Get involved
_Especially for open source projects, it is beneficial to motivate potential users of the project to contribute back or share their feedback. Make it easy for them._

Comments and suggestions on this folder structure are always welcome. Please create an issue to share your feedback or question, or if you prefer send a pull request. 

Better structured projects can explain a number of options for contributors such as: 
+ (where to start)
+ (issue template)
+ (direct contact)
+ (pull requests)

## License
_After the README, A LICENSE is the most important file in the project documentation. Without a license, there is too much uncertainty to try building anything on top of the original project._

This project is released under CC0 1.0 Universal. 
You can modify an reuse as you like.
The project team appreciates your suggestions or examples for enhancing the repository, but your consistent documentation of your project is the best gift to the world. Hopefully, this template could make that a bit easier for you. 

### (How to cite:)
_Additionally, you can specify how others can cite your project._

## (Funding)
_Be kind to your funders and mention their support visibly and consistently. They also need to show their resources are wisely spent._

This template can be copied free of charge. 

<div style="display: flex; justify-content: space-between;">
  <img src="./Documents/Images/lpl_sharing.jpg" alt="lpl sharing" style="width: 30%;"/>
  <figcaption>Figure: LPL shop front with current and future letters<figcaption>
</div>