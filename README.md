# Residence Inn Work Widgets (Android project)

A starter Android Studio project for a Marriott-inspired red, white, and navy hotel work widget pack. It includes seven home-screen widget types:
- Shift Schedule
- Front Desk Checklist
- Clock & Date
- Daily Reminders
- Housekeeping Room Status
- Notes
- Weather (manual placeholder; no live weather API configured)

## Important
This is **project source code**, not a prebuilt APK. To install it on your Android phone, open the project in Android Studio, let Gradle sync, build an APK, then install it. The project uses standard Android widgets and local preferences. No Marriott systems are connected; do not enter guest names, room numbers tied to guests, payment details, or other confidential hotel information.

## Build
1. Install Android Studio on a computer.
2. Extract this ZIP.
3. In Android Studio choose **Open** and select the `ResidenceInnWorkWidgets` folder.
4. Let Android Studio sync/download the Android Gradle plugin.
5. Choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
6. Install the generated debug APK on your Android phone.
7. On your home screen, long-press an empty area > **Widgets** > **Residence Inn Work Widgets**, then add the widgets you want.

## Notes
- The shift, notes, reminders, and room-status widgets use sample/default text and simple local settings. They are not linked to FOSSE, Marriott systems, or a live hotel PMS.
- The clock/date widget refreshes using Android's widget update mechanism.
- The weather widget is a visual placeholder; edit the text in its widget configuration or source to show your local forecast. Live weather requires a weather provider/API and internet permission.
- Branding is inspired by red/white/navy hotel styling and is not an official Marriott product.


## Optional: build the APK automatically with GitHub Actions
This project includes `.github/workflows/build-apk.yml`. If you upload the project to a GitHub repository, the workflow can build a debug APK in GitHub Actions:
1. Create a repository on GitHub and upload the contents of this folder.
2. Open the repository's **Actions** tab.
3. Run **Build Android APK** (or push to the `main` branch).
4. Open the completed workflow run and download the artifact named `ResidenceInn-Work-Widgets-debug-apk`.

The artifact is an installable debug APK. Android may ask you to allow installation from your browser or file manager. This workflow has not been run from this environment.
