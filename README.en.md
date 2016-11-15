# android_volley_gradle

Tip to generate the jar or aar of volley using gradle

## Step 1

Download Volley Library https://android.googlesource.com/platform/frameworks/volley

"git clone https://android.googlesource.com/platform/frameworks/volley"

## Step 2
Download gradle

http://gradle.org/gradle-download/

## Step 3
Configure path to SDK Android "ANDROID_HOME"

export ANDROID_HOME=/Users/emedinaa/Dev/android/sdk
PATH=${PATH}:$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools


## Step 4
Execute command "gradle build" in the volley folder

/Users/emedinaa/Documents/gradle/gradle-2.5/bin/./gradle build --x test

"BUILD SUCCESSFUL"

## Step 5

The jar and the aar files 

build/intermediates/bundles/release/classes.jar

build/outputs/aar/volley-release.aar

