# Fintrack — Online Spending Tracker

TY BSc CS mini project built with React Native and Expo.

## Features

- Device-local email/password sign-up and login
- Home, Insights, Transactions, and Profile tabs
- Monthly spending total, budget, and expense entry
- Month-to-date comparison with the same days of the previous month
- Category-by-category spending changes and personalized saving tips
- Import CSV statements with Date, Description, Amount or Debit columns
- Local expense storage; long-press a transaction to delete it

The login is a student-project demo, not an online account system. Credentials are stored on the device, and data does not sync between phones. CSV files are read on-device. PDF statements and bank connections are not supported.

## Install and build

In PowerShell, open this folder and run npm.cmd install to install Expo modules and update package-lock.json. Then sign in with npx.cmd eas-cli@latest login and run npx.cmd eas-cli@latest build --platform android --profile preview. Download the APK from the Expo build page when it finishes.

EAS Build compiles the Android APK in the cloud; Android Studio is not required. Free builds use a low-priority queue, so start time is not guaranteed.
