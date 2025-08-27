## Download Intune Company Portal

Follow these steps to install the Company Portal for Windows using the EXE package. If you need to deploy the client across the organization, you can use the `msiexec` command from the terminal to handle the installation.

1. Download the correct version of the Company Portal installer for your system:

* [Windows 64-bit](*)  *(most common)*
* [Windows 32-bit](*)
* [Windows ARM64](*)

2. Open the installer by double-clicking the downloaded file.

3. On the welcome screen, click **Next**.

4. To accept the license agreement, check the box labeled **I accept the terms in the License Agreement**, then click **Next**.

5. Under Installation Scope, choose one of the following options:

* **Install only for you**: Installs the Company Portal to a user-specific directory, making it available only for your account. No administrator privileges are needed.

* **Install for all users on this machine**: Installs the Company Portal for all users on the device. Administrator privileges are required.

6. Click **Install** to begin the installation process.

7. After the installation is complete, click **Finish**.

8. If the **Launch Company Portal when setup exits** box is checked, the app will open automatically. Otherwise, you can open it manually by searching for **Company Portal** in the Start menu.

Before connecting to your devices or apps on Windows, make sure you meet the following requirements:

* Active Internet connection
* A supported version of Windows:

  * Windows 11
  * Windows 10
  * Windows Server 2022
  * Windows Server 2019
  * Windows Server 2016
* .NET Framework 4.6.2 or higher. Some versions of Windows 10 and Windows Server 2016 might need a manual installation. Visit the .NET Framework download page for the latest version.

### Android

To install Company Portal on Android, use one of these stores:

* [Portal AppStore](*)
* [Google Play](*)
* [Amazon Appstore for Android](*)

If these app stores are unavailable, or your device doesn't support Google Mobile Services, you can [download Microsoft Intune Company Portal for Android](*) and manually install the app. Keep in mind that side-loaded apps will not receive automatic updates or security fixes, so you will need to update them manually.

The Google Play Store is inaccessible in the People's Republic of China. In this case, install the Company Portal app from an approved Chinese app store.

### iOS

To install Company Portal for iOS, download it from the [Apple App Store](*).

### macOS

For macOS, install Company Portal by visiting [Enroll my Mac](*). This link will automatically start the download of the installer package to your device.

## Sign in to app

There are three ways to sign in to the Company Portal app:

* Use your work or school email and password.
* Use certificate-based authentication.
* Sign in from a different device.

For the best experience, follow the sign-in method recommended or required by your organization.

### Sign in with school or work account

1. Open the app and select **Sign In**.
2. Enter your school or work email address and click **Next**.
3. Enter your password and click **Sign In**.
4. Wait while the app verifies your credentials. Once confirmed, you will have access to the app’s features and your organization's resources.

### Sign in with certificate

This option will only appear if your organization supports certificate-based authentication and if you have a certificate available.

1. Open the Company Portal app on your device.
2. Enter the email address associated with your school or work account and click **Next**.
3. Select **Sign in with a certificate**.
4. Tap **Continue** to confirm the certificate.
5. Wait while the app checks the certificate. Once verified, you can access the app’s features and your organization's resources.
