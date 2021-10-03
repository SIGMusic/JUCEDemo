# JUCEDemo

Creating a basic Audio/MIDI plugin

## Install JUCE

[Download JUCE](https://juce.com/get-juce/download)

On MacOS I recommend extracting this to `/Applications`. Otherwise just extract this to your home folder and maybe add a shortcut to the Projucer.

## For Windows

Install VisualStudio (the full IDE)

[Download VisualStudio](https://visualstudio.microsoft.com/)

## For MacOS

Install XCode from the Mac app store and run the following in a terminal to get the developer tools:

`xcode-select install`

[Get XCode](https://apps.apple.com/us/app/xcode/id497799835?mt=12)

## For Linux

Install Code::Blocks (You can also just use a makefile if that suits your fancy)

[Download Code::Blocks](https://www.codeblocks.org/downloads/)

Once those are all installed, in wherever you extracted the JUCE folder go to `JUCE/examples/DemoRunner/` and open the file `DemoRunner.jucer` in the Projucer. After that opens, export it to your IDE using the button at the top and build the executable. This will let you run your plugins in a demo environment.
