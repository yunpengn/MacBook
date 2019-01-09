# MacBook Setup Guide

This is a detailed step-by-step guide to help you setup a new MacBook Pro. Before we start, please take note of the following items:

- It is assumed you are using the latest model of MacBook Pro (at least after 2016).
- It is also assumed that you have installed the latest version of MacOS (at least `10.12 Sierra`).
- This guide is tailor-made for a developer or software engineer's personal laptop.
    - In other words, we would install the required tools for personal development. However, we would not focus on tools that are organization-specific.
- This guide is also customized for certain region (Asia/Singapore) & languages (English and Mandarin).

## Background

At the time of writing, I am a [Computer Engineering](http://ceg.nus.edu.sg) undergraduate at the [National University of Singapore] as well as a software development enthusiast.

One day, I received an email from [Apple](https://www.apple.com) with the title _"Important information about your MacBook Pro"_. It said that my MacBook _has an issue that may result in data loss and failure of the drive (SSD)._ See [this page](https://www.apple.com/sg/support/13-inch-macbook-pro-solid-state-drive-service-program/) for more information. Apple offered to provide a service program to fix this problem _(by updating the driver firmware)_ free of charge. So I registered and sent the device to an Apple Authorized Service Provider - [A.Lab](https://www.alab.sg).

I am aware that all data will be erased after the service. However, I am fine with that since almost all important data on my device have been backed up. Nonetheless, I still need an SOP (standard operating procedure) to setup (or re-setup) my MacBook after the service. Thus, I decided to document this process here.

Please notice this guide is opinionated. The following philosophical rules are enforced:

- **Be stingy**: install the minimal set of tools you need. Whenever a new software is installed, a new potential vulnerability is introduced.
- **Be Apple's fun**: use tools provided by Apple by default (opt to an external tool only when absolutely necessary). For example, we use [iTerms 2](https://www.iterm2.com) rather than the [default terminal](https://support.apple.com/guide/terminal/welcome/mac
). However, we would stick with the default [bash](https://www.gnu.org/software/bash/) and never use [zsh](http://www.zsh.org).

## Steps

1. Create a new user account on MacOS:
    - This should be done when you turn on your device for the first time;
    - Set this account as an `administer`;
    - The `full name` field should be your full real name in English (use a single space to separate each word, first letter of which should be captialized);
    - The `account name` field should be your first name in English (all lowercase, alphanumeric only);
    - Do not leave the `password` blank;
    - Do not leave the `hint` field blank as well.
2. If this is not the first time you turn on the device, and you want to change the name of your account:
    - Log into the admin account;
    - Open `System Preferences` -> `Users & Groups`;
    - Click the lock icon and enter admin password;
    - Click the plus icon to create a new account;
        - Follow the instructions in Step 1.
    - Log out and then log into the account created just now;
    - Delete the old account;
    - Alternatively, see this [guide](https://support.apple.com/en-us/HT201548) from Apple for more details.

## Licence

[GNU General Public Licence 3.0](LICENSE)
