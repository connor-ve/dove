## Welcome to Dove

`Dove` is a documentation builder with a built in focus on Rest API documentation and software installation guides. `Dove` is an incredibly easy solution to a tough problem. I am a developer, I hate documentation. Like all of us I wanted a solution that wasn't a bother to work with. In essence these were my goals. `All documentation should be managed in markdown`, `integration with Obsidian is a must`, `cli should install, build transfer and compile`.

After many years of using docusaurus, I found a reason to reinvent this wheel. The process can be configured differently sure... but as all of us Developers; I am highly particular of my tools. So lets get started.

### Quick Start

The CLI for `Dove`, aka [dove-cli](##), is built in Golang. It is needed for the installation of any `Dove` project. If you are familiar with golang and have it installed, please install the cli using the command below.

```bash
go install dove-cli
```

If you do not have golang installed and dont plan to install it, the following release links allow you to download the executable for your OS.

[Link to Releases](##)

Once the executable is installed and usable. Check the installation with the command :

```bash
dove version
```

If dove has been installed properly, a version number should be visible.

Lets now initialize a `Dove` documentation site. Running the following command will create a `Dove` project for you.

```bash
dove create project-name -v
# -v (not required) : verbose response will return data about how the project was created etc. Also will note the markdown bin you will put files in
```

This will create all the need files for you to start your `Dove` project. When in the project, running `dove start` will locally host your site.

##### Using Obsidian (recommended)

Obsidian is a popular open-source markdown notes app. I greatly recommend using this to manage your markdown files for your dove project. When using dove-cli to build a dove site, the dove create command will create documentation folder. The folder is fully compatable with obsidian as a vault folder. Folder names will be defined as tabs within your documentation pages, while individual files will be handled as doc pages. Some pages names will have specific use cases such as `_index`, which will give the folder a page itself.

##### Without Obsidian

When using dove-cli to build a dove site, the dove create command will create documentation folder. The folder is the structure of your documentation pages. Folder names will be defined as tabs within your documentation pages, while individual files will be handled as doc pages. Some pages names will have specific use cases such as `_index`, which will give the folder a page itself. Feel free to open the `tails` folder to add your documentation md files.

#### Starting

_..._
