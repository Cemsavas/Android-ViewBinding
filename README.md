# Android-ViewBinding
 View binding is a feature that allows you to more easily write code that interacts with views. Once view binding is enabled in a module, it generates a binding class for each XML layout file present in that module. An instance of a binding class contains direct references to all views that have an ID in the corresponding layout. 
 
In most cases, view binding replaces findViewById
 
Okay. Let's Check How to Implement ?🛠

✏ Open your build.gradle(Module) and write this code: buildFeatures{viewBinding = true}

<img width="960" alt="1" src="https://user-images.githubusercontent.com/88722745/186423044-61458855-aa95-4f8e-a932-cc3ab8c8bd3d.png">


✏ Then go to your Activity page; and before OnCreate method define binding feature as; lateinit var binding: ActivityMainBinding

<img width="960" alt="2" src="https://user-images.githubusercontent.com/88722745/186423272-b2aa4706-9933-456a-aa74-323e4b54baf8.png">


✏ In OnCreate method define your binding as; binding = ActivityMainBinding.inflate(layoutInflater)

✏ Last Call your layout as; setContentView(binding.root)

That's All 😊😊
