# mit

Quick script to create an MIT license in the current directory.

## What is the MIT license?

As per [choosealicense.com](https://choosealicense.com/licenses/mit/):

> A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code. 

## Usage

`mit [copyright holder]`

Run the script to create a LICENSE file in the current directory detailing the MIT license. It uses wrapped lines for readability.

If a copyright holder isn't specified then the default will be used. You can configure a default copyright holder by modifying `DEFAULT_HOLDER` in the script's header.

## Installation

Copy the script anywhere in your path (like `/usr/local/bin`) and give the script execute permissions.

