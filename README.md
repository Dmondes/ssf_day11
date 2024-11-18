# ssf_day11

#Maven compiler commands

In project root folder <br/>

./mvnw clean<br/>  [comment]: clean for mac
mcnw.cmd clean<br/> [comment]: clean for windows

package the complied bytecode classes into jar or war files
./mvnw package <br/>
mvnw.cmd package <br/>

delete target, redownload dependencies, recompile to class files, package to jar/ war <br/>
./mvnw clean pacakge <br/>
mvn.cmd clean package <br/>

run the application in embedded localhost server <br/>
./mvnw spring-boot:run <br/>
mvnw.cmd package <br/>

java -jar pract1-0.0.1-SNAPSHOT.jar --port=8090
