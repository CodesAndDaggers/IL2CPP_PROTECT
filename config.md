
How to Use the IL2CPP Protection Tool

# Prepare the IL2CPP Protection Directory
- Place the "il2cpp protect" directory inside your project's Assets folder.
  Example:
  YourProject/
    Assets/
      il2cpp protect/

# Configure the IL2CPP Protection Settings
. Locate and open the IL2CPP configuration file within the il2cpp protect directory.

# Protection Settings:
. Enable Protection:
	- Turn protection on or off.
 
. Full Obfuscation:
    - Choose whether to obfuscate all IL2CPP classes or only the il2cpp API exports.

. Enable Logging:
    - Turn logging on or off.
    
. Log File:
    - Specify the path where the log should be saved.
    
. Save Obfuscated:
    - Indicate whether you want to save the obfuscated IL2CPP for future builds.
    
. Saved Obfuscated:
    - The path where the obfuscated IL2CPP is stored.


# Android Build Settings
. Keystore Alias:
	- Provide the full path to your keystore file used for signing the APK.
 
. Keystore Alias:
	- Enter the alias name for your keystore.
 
. Save Password:
	- Choose whether to save the keystore password within the configuration.
 
. Run ADB Install:
	- Decide whether to automatically run `adb install` after the build completes.
 
. Minimum SDK Version:
	- Set the minimum SDK version required for your app, especially important for Google Play Store and .aab builds.
 
