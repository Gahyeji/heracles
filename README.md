# Heracles
A visual interface for hydra written in C and using GTK. Aim to replace xHydra, which was truly a handful for pentesting. I DIDN'T CREATE HYDRA, this achievement belongs to @pseudo. 

## Table of Contents
- [Preview](#preview)
- [Description](#description)
- [Usage](#usage)
- [Install](#install)
- [Release](#release)
- [Issues](#issues)
- [Contributing](#contributing)
- [License](#license)

## Preview
A quick overview about how the app looks.
![Basic page](path_to_image)
And here is the ouptput which will show the results of the query, made to be as "beginner-friendly" as possible.
![Ouptut page](path_to_image)

## Description
This app is based on Hydra, a pentesting tool used to test credentials against network interfaces with bruteforce technique. xHydra was a pretty good GUI I used for a while, but now that it is gone I figured I may do something similar myself. 

What I wanted to add is more clarity for the output, which really looked like all CLI tools output : lots of words but not enough clarity on what's really happening. Of course, if you want the exact same output as the CLI version, the "verbose" mode is here for you, as well as other advanced options if you need. 

But, overall, expect this GUI to be easier by default, since hydra is mainly used to test weak credentials, I figured most people were gonna use wordlists and basic options.

## Usage
In order for the tool to work, you need to put at least :
A target (IP or URL), a port, a username, and a password (either wordlist or single entry for each).

As mentionned above, if you want the ouptut to be exactly as the CLI Hydra one, then you should tick the "verbose" mode. Otherwise, the output will be translated to a simpler version, which means that all unnecessary steps or description will be skipped, only to show the results in a simplified way.

In the "advanced" window, you'll have the opportunity to add more options, like multi-threading, or other advanced tweaks.

I also plan to add a wordlist creator that you'll be able to launch instead of premade wordlists.

## Install

## Release
No release yet, project in construction.

## Issues
Every user can create an issue if they need to, but please follow the following rules in order for every submission to be taken seriously and fixed :

## Contributing
I encourage anyone to contribute if they're willing to. I'm still a beginner in both coding and cybersecurity so any help would be warmly welcomed.

If you want to, then you only need to follow below steps :
1. Clone the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes.
4. Push your branch: `git push origin feature-name`.
5. Create a pull request.

I'll check every request and answer as fast as I can.

## License
This project is licensed under the [MIT License](LICENSE).