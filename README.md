# skel
[![Build Status](https://travis-ci.org/ncorrare/skel.svg?branch=master)](https://travis-ci.org/ncorrare/skel)

#### Table of Contents

1. [Overview](#overview)
2. [Setup - The basics of getting started with skel](#setup)
    * [Setup requirements](#setup-requirements)
    * [Beginning with skel](#beginning-with-skel)

## Overview

This is just a boilerplate module that includes testing and automatic deployment to the forge.

## Setup

### Setup Requirements **OPTIONAL**

You need to create (using travis encrypt, from the travis gem) to create the following secure environment variables:

- GITHUB_SECRET_TOKEN
- BLACKSMITH_FORGE_USERNAME
- BLACKSMITH_FORGE_PASSWORD

and set up USENETWORK to true and DEPLOY to true in order for deployment to work.

Remaining information is popuplated from Travis environment variables.
### Beginning with skel

Create a branch, and after doing a PR it will test and merge automatically if tests work. If DEPLOY is set to true it will tag, change metadata.json, commit, push, build and deploy to the forge

