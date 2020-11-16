# Android-NoteCheatSheet
1. Scroll the screen up when keyboard open
- Add attribute <b>android:windowSoftInputMode = "adjustResize"</b> in <activity/> card in AndroidManifest.xml
2. Kotlin ? vs !!
- var s:String?=null //init variable is null
- s?.toUpperCase() //run if s is not equal null
- s!! //send the s variable not null
3. Lateinit vs Lazy in Kotlin
- Lateinit var chỉ dùng với kiểu var: sẽ được khởi tạo sau.
- Lazy chỉ dùng với kiểu val: được dùng khi ta muốn biến đó chỉ khởi tạo dữ liệu khi được gọi, lần đầu thì sẽ khởi tạo dữ liệu, các lần sau sẽ lấy từ memory ra dùng. VD: val name: String by lazy { “It life” }

