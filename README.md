`Starting Gradle Daemon...`  
`Gradle Daemon started in 1 s 385 ms`  

`22:22:01.001 : main : README.md : INFO : Connect Successful!`  
`22:22:01.012 : main : README.md : INFO : name=yunhoHa`  
`22:22:02.123 : main : README.md : INFO : id=haji9202`  
`22:22:03.003 : main : README.md : INFO : region=southKorea`  
`22:22:04.004 : main : README.md : INFO : email=hayun9202@gmail.com`  
`22:22:06.123 : main : README.md : WARN : Exception in thread "main" java.lang.NullPointerException: GithubProfile is null.
	at MainKt.main(Main.kt:123)
	at MainKt.main(Main.kt)`  
 `22:22:06.321 : main : README.md : DEBUG : profile is null, Reload GithubProfile object`

## haji9202.kt

```kotlin
class haji9202 : GithubProfile {
    val name: String = "yunhoHa"
    val id: String = "haji9202"
    val region: String = "southKorea"
    val email: String = "hayun9202@gmail.com"

    init {
        TechAndLanguage()
    }
}
```

## TechAndLanguage.kt

```kotlin
class TechAndLanguage {
    val techList = ArrayList<String>()
    val languageList = ArrayList<String>()
    val osList = ArrayList<String>()
    val editorList = ArrayList<String>()

    init {
        languageList.add("Kotlin")
        languageList.add("Java")
        languageList.add("Python")
        languageList.add("CSharp")

        techList.add("Git")
        techList.add("Github")
        techList.add("Gradle")
        techList.add("Docker")
        techList.add("AWS")
        techList.add("Cloudflare")
        techList.add("Firebase")
        techList.add("Unity")

        osList.add("Windows")
        osList.add("macOS")
        osList.add("Ubuntu")
        osList.add("Arch")

        editorList.add("IntelliJ")
        editorList.add("Rider")
        editorList.add("PyCharm")
        editorList.add("VSCode")
    }
}
```

`22:22:06.123 : main : README.md : WARN : Exception in thread "main" kotlin.NoKotlinInUseException: try use Kotlin.
	at Everything.main(Everything.kt:5)
	at Everything.main(Everything.kt)`  

 `22:22:06.123 : main : README.md : WARN : Exception in thread "main" Barcode.NoBrainInUseException: hey Barcode use Kotlin.
	at Barcode.main(Barcode.kt:null)
	at Barcode.main(Barcode.kt)`  
 
`Process finished with exit code 123`
