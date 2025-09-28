# terminology

---

## List
|n|name|desc.|e.g.|O/P|
|-|----|-----|----|---|
|1|Gradle|<ins>What is Gradle ?</ins><br/>&ensp;1. Convention based build tool<br/>&ensp;2. DSL to describe the build<br/>&ensp;3. Supports multi-project builds<br/>&ensp;4. Easily customizable<br/>&ensp;5. Builds manay languages<br/>&ensp;6. Supports dependencies
|2|Ant|<ins>XML baased 'Script'</ins><br/>&ensp;- Hard to read<br/>&ensp;- Difficult to maintain||<img src="https://i.imgur.com/vCfibm9.png"><br/>Create the build dir stucture used by compile :<br/><img src="https://i.imgur.com/4apxUn3.png">|
|3|Maven|||<img src="https://i.imgur.com/K8waUL5.png"><br/>dependency maven pom.xml :<br/><img src="https://i.imgur.com/8i3r9lD.png">|
|4|Comparing Ant & Maven|
|5|Installation|<ins>From the web site</ins><br/>&ensp;- All platforms<br/><ins>SDK manager</ins><br/>&ensp;- https://sdkman.io<br/>&ensp;- *nix platforms<br/>&ensp;- Can also install on Cygwin etc...<br/><ins>Homebrew</ins><br/>&ensp;- Mac<br/><br/><ins>Prerequisites</ins><br/>requires only a Java JDK or JRE ver 8 or +<br/>`java -version`||<img src="https://i.imgur.com/Dy5im2R.png"><br/>Install Java 21 -> gradle 6.3 :<br/><img src="https://i.imgur.com/RwnREvx.png"><br/>command gradle default:<br/><img src="https://i.imgur.com/nAsypCa.png">|
|6|SDK manager|Get from https://sdkman.io<br/>Download with<br/>`curl -s "https://get.sdkman.io" \| bash`<br/>Add to path<br/>Install Gradle<br/>&ensp;- sdk install gradle||<img src="https://i.imgur.com/fC9oPVg.png"><br/>sdk install gradle :<br/><img src="https://i.imgur.com/DqYbg2n.png">|
|7|How Is Gradle Used ?|<ins>Greate a build script</ins><br/>&ensp;- Kotlin(extension file : std : `*.kt` & `*.kts` for script) or Groovy DSL<br/><br/><ins>This defines tasks</ins><br/>&ensp;- build, clean, etc...<br/><br/><ins>Run the appropriate task|
