Some usefull artefacts in a mvn-repository.

---------------------------------------------------------------------------------
Add this repository to your project:

	<repositories>
		<repository>
			<id>dans-er.mvn.repo</id>
			<url>https://github.com/dans-er/mvn-repo/raw/master</url>
		</repository>
	</repositories> 

---------------------------------------------------------------------------------
dans-prototype has usefull features. Make it the parent of your project:

	<parent>
		<groupId>nl.knaw.dans.platform</groupId>
		<artifactId>dans-prototype</artifactId>
		<version>1.3.1</version>
	</parent>

