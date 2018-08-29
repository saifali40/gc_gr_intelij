# appengine-cloud-sdk-gradle
Download the appengine cloud sdk form https://cloud.google.com/sdk/docs/ and extract

update the path in build.gradle.
appengine.tools.cloudSdkHome="/Users/saif/Downloads/google-cloud-sdk/"

install glcoud ( cloudSdkHome/install.sh ) or install glcoud ( cloudSdkHome/install.bat )
then initialize your app

cloudSdkHome/google-cloud-sdk/bin/gcloud init 
Login to your account and choose the project as per your wish ( however the appengin-web.xml will decide where to deploy).
