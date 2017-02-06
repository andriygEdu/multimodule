# multimodule

`
mvn -pl maven_reactor_resolve install 
`

`
mvn -Presolve_reactor validate -am -amd -pl module1 
`

`
 mvn package -am -pl set1/module1,set1/exec1
`


`
mvn org.andriyg76.plugins:maven_reactor_resolve:1.0-SNAPSHOT:touch 
-amd -pl set1/module1
`

`
mvn package -am -pl com.andriyg76.test:module1,com.andriyg76.test:exec1
`

