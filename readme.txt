/lib/terminal

����sqlServer:
	java -jar mybatis-generator-core-1.3.2.jar -configfile ../sqlServerGeneratorConfig.xml -overwrite
����mysql:
	java -jar mybatis-generator-core-1.3.2.jar -configfile ../mysqlGeneratorConfig.xml -overwrite