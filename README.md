# Android-ViewBinding
 View binding is a feature that allows you to more easily write code that interacts with views. Once view binding is enabled in a module, it generates a binding class for each XML layout file present in that module. An instance of a binding class contains direct references to all views that have an ID in the corresponding layout.  In most cases, view binding replaces findViewById
 
Okay. Let's Check How to Implement ?🛠

✏ Open your build.gradle(Module) and write this code: buildFeatures{viewBinding = true}

✏ Then go to your Activity page; and before OnCreate method define binding feature as; lateinit var binding: ActivityMainBinding

✏ In OnCreate method define your binding as; binding = ActivityMainBinding.inflate(layoutInflater)

✏ Last Call your layout as; setContentView(binding.root)

That's All 😊😊
