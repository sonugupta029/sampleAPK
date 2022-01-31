# Sample Apk Hello World
This repo contains sample apk hello world for using with appium espresso

# Sample capabilities to run appium espresso:
{
  "platformName": "Android",
  "automationName": "Espresso",
  "showGradleLog": true,
  "forceEspressoRebuild": true,
  "espressoBuildConfig": "{ \"additionalAppDependencies\": [ \"com.google.android.material:material:1.0.0\", \"androidx.lifecycle:lifecycle-extensions:2.1.0\" , \"org.reduxkotlin:redux-kotlin-jvm:0.5.5\", \"org.reduxkotlin:redux-kotlin-threadsafe-jvm:0.5.5\", \"org.reduxkotlin:redux-kotlin-thunk:0.5.5\"]}",
  "app": "/Users/sonugupta/Documents/Work/Automation/DemoApps/HelloWorld2-with-hilt/app/build/outputs/apk/debug/app-debug.apk",
  "udid": "RFCR30V3YQP",
  "appPackage": "au.com.demo.helloworld2",
  "appActivity": "au.com.demo.helloworld2.MainActivity"
}
