# Android-NoteCheatSheet
1. Scroll the screen up when keyboard open
- Add attribute <b>android:windowSoftInputMode = "adjustResize"</b> in <activity/> card in AndroidManifest.xml
2. Kotlin ? vs !!
- var s:String?=null //init variable is null
- s?.toUpperCase() //run if s is not equal null
- s!! //send the s variable not null
