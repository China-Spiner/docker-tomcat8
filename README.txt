tomcat8+java8的docker化环境。

1、server.xml在原有基础上增加UTF-8的环境设置，避免中文乱码问题。
2、已增加service tomcat 命令，便于维护。
3、不使用apt-get方式来安装tomcat是由于习惯问题，而且此方式也不利于使用JAVA_OPTS参数。
