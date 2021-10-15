## Texas Advanced Computing Center
# Django CMS Plugin: Sample (Greet User)

This plugin greets a user by name, and serves as a sample plugin for https://github.com/TACC/Core-CMS.

- __`__dist-name__`__: `taccsite_sample`
- __`__package_name__`__: `taccsite_sample`
- __`__ClassName__`__: `TaccsiteSample`
- __"Plugin Name"__: "Sample (Greet User)"

## Quick Start

1. Follow https://github.com/tacc-wbomar/Core-CMS-Plugin/wiki/Core-CMS-Plugin-Usage-Quick-Start.

## Usage

1. Add instance of plugin to a page.
1. Set the "Guest Name" to any value.
1. See plugin output when logged in and not logged in.

## Features

1. Greets guest user as "Guest", unless configured otherwise.
1. Greets guest user by guest name set via plugin instance.
1. Greets logged in user by name based on available user data:
    - "FirstName LastName"
    - "FirstName"
    - "username"
