# maven.bionicspirit.com

Simple Maven repository where I publish my artifacts (basically whatever I want).

## Usage with Maven

    <repositories>
      <repository>
        <id>BionicSpirit Releases</id>
        <url>http://maven.bionicspirit.com/releases/</url>
      </repository>
	  
      <repository>
        <id>BionicSpirit Snapshots</id>
        <url>http://maven.bionicspirit.com/snapshots/</url>
      </repository>
    </repositories>
    
## Usage with SBT

    resolvers += "BionicSpirit Releases" at "http://maven.bionicspirit.com/releases/"

    resolvers += "BionicSpirit Snapshots at "http://maven.bionicspirit.com/snapshots/"

