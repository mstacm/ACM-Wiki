# Missouri S&T ACM Wiki

## Introduction 

Hello! This is the Wiki for all things Missouri S&T ACM Wiki. This is meant to teach anyone about how our ACM Chapter works from our events to how to get involved. There is a lot to know and do with ACM so let's get started. 

Below you will find information on how to contribute to the Wiki but if you are here to learn let's get started! 

## Wiki Contributions 

This Wiki is completely open source! This means you can clone it on [GitHub](https://github.com/mstacm/ACM-Wiki), edit it, fork it, and contribute to it to become better. This is mean to serve as a living document and guide to being inside of ACM so all contributions are welcome! 

Also if you have question's about the Wiki please feel free to ask in our [Discord](https://discord.gg/VgFGtz4TJY) or email us at acm@mst.edu. 

### Setting Up The Wiki For Editing. 

This Wiki is built using [Mkdocs](https://www.mkdocs.org/) so everything is written in Markdown (.md) and can be convert to a web page that is hosted on GitHub Pages. 

To get start you will need to download Mkdocs using pip: `pip install mkdocs` more documentation can be found [here](https://www.mkdocs.org/user-guide/installation/)

#### Comamands For Developing 

* `mkdocs serve` - Start the local live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

run ```mkdocs gh-deploy``` to publish to GitHub pages 

#### Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

