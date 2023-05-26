## Complex Timer Privacy Policy
Complex Timer is a simple app, and is designed to do just one thing. To the best of my knowledge the only data that Complex Timer collects and stores is that explicitly created by the user in the form of Settings, Sessions and their backups. This data by its own nature is always available to be reviewed by the user, who can delete it at any time by wiping the app's storage or uninstalling it.

Complex Timer requests some permissions from the OS, some of them are needed for basic functionality and others, deemed more serious by Android, need to be granted (and can be revoked) by the user:

- `android.permission.VIBRATE` Required to vibrate the device, can't be revoked by user.
- `android.permission.WAKE_LOCK` This permission allows the app to run for a long time in the background without being closed by the OS. Can't be revoked by user.
- `android.permission.FOREGROUND_SERVICE` This permission allows the app to show an ongoing notification to control the app when it's in the background and from the lock screen. Can't be revoked by user.
- `android.permission.READ_EXTERNAL_STORAGE` and `android.permission.WRITE_EXTERNAL_STORAGE` These have to be explicitly granted and can be revoked by the user; they are optional, and only needed for saving and restoring backups, and also for importing custom alarms into the app.
