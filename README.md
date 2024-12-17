To run : 
    0. in Android-Studio, go to open>yap>android-build
    1.clone using https://github.com/B4bySimba/yap.git 
    2. Sync gradle files 
    3. build 
    4. run 
    5. Install firebase CLI: https://github.com/B4bySimba/yap.git 
    6. Confirm installation: firebase --version 
    7. run: firebase login 
    8. login in the opened browser tab using your firebase credentials 
    9. start the emulator: firebase emulators:start --project=demo-friendlychat-android 
    10. You should see something like: 
    
    $ firebase emulators:start --project=demo-friendlychat-android
i  emulators: Starting emulators: auth, database, storage
i  emulators: Detected demo project ID "demo-friendlychat-android", emulated services will use a demo configuration and attempts to access non-emulated services for this project will fail.
i  database: Database Emulator logging to database-debug.log

┌─────────────────────────────────────────────────────────────┐
│ ✔  All emulators ready! It is now safe to connect your app. │
│ i  View Emulator UI at http://127.0.0.1:4000/               │
└─────────────────────────────────────────────────────────────┘

┌────────────────┬────────────────┬────────────────────────────────┐
│ Emulator       │ Host:Port      │ View in Emulator UI            │
├────────────────┼────────────────┼────────────────────────────────┤
│ Authentication │ 127.0.0.1:9099 │ http://127.0.0.1:4000/auth     │
├────────────────┼────────────────┼────────────────────────────────┤
│ Database       │ 127.0.0.1:9000 │ http://127.0.0.1:4000/database │
├────────────────┼────────────────┼────────────────────────────────┤
│ Storage        │ 127.0.0.1:9199 │ http://127.0.0.1:4000/storage  │
└────────────────┴────────────────┴────────────────────────────────┘
  Emulator Hub running at 127.0.0.1:4400
  Other reserved ports: 4500

Issues? Report them at https://github.com/firebase/firebase-tools/issues and attach the *-debug.log files.


    11. Navigate to http://localhost:4000 in your web browser to view the Firebase Emulator Suite UI
    12. leave the terminal open.
    13. Now you can create an account using email and yap
