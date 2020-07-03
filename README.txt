How To Try Sample Policy Administrator Client Of WSO2 Identity Server 5.X.X
===========================================================================

1. If you have not built the project yet, Please build the project using Maven

   >mvn clean install 

2. Configure configuration parameters in the load test using config.properties file which can be found in <ROOT>/resources directory

    By default there is no any configuration data in that file. Therefore if you want to override the default setting , you can do this by configuring above file. 

    Please note <ROOT>/resources directory  contains another file i.e, wso2carbon.jks it is the default trust store file 

3. Open client project in a Java IDE. You can set jars in lib directory as dependancy jar files.
