# taketwo
Testing how to create two XBlocks in a single repository/egg

## Installation

First install the egg:

`sudo -u edxapp /edx/bin/pip.edxapp install git+https://github.com/ewall/taketwo.git@v0.1#egg=taketwo==0.1`

In edX Studio, open the course where you'd like to use the module, go to Settings -> Advanced Settings, then add the following entries to the "advanced_modules" section:

`"takeone", "taketwo"`
