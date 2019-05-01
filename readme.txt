/lib/terminal

生成sqlServer:
	java -jar mybatis-generator-core-1.3.2.jar -configfile ../sqlServerGeneratorConfig.xml -overwrite
生成mysql:
	java -jar mybatis-generator-core-1.3.2.jar -configfile ../mysqlGeneratorConfig.xml -overwrite