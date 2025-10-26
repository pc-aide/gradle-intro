# v6.3

---

## version
````ps1
gradle -version
````
<img src="https://i.imgur.com/xJV2kT1.png">

---

## build
* build.gradle.kts
````ps1
task("hello") {
    doLast {
        println("hello from doLast")
    }
}
````

* build

````ps1
gradle build
````

<img src="https://i.imgur.com/aaRmNyl.png">

* syntax : gradle <taskName>
* eg : `gradle hello`

<img src="https://i.imgur.com/Kdzqpo9.png">

---

## task
````ps1
gradle tasks 
````
<img src="https://i.imgur.com/EbFRhWR.png">
