# android_volley_gradle
Tip para  generar el jar o aar de volley usando gradle

## Paso 1
Descargar la librería Volley https://android.googlesource.com/platform/frameworks/volley
"git clone https://android.googlesource.com/platform/frameworks/volley"

## Paso 2
Descargar gradle
http://gradle.org/gradle-download/

## Paso 3
Identificar el path del SDK de Android y configurar ANDROID_HOME
export ANDROID_HOME=/Users/emedinaa/Dev/android/sdk
PATH=${PATH}:$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools


## Paso 4
Ejecutar el comando gradle build en la carpeta raiz de Volley

/Users/emedinaa/Documents/gradle/gradle-2.5/bin/./gradle build --x test

"BUILD SUCCESSFUL"