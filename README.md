# PersonalSpark
自己修改过的Spark，编译以后即可运行

编译环境 centos6.5 maven3.5.2
编译：
进入spark目录 
执行 mvn package -Dmaven.test.skip=true  -Dmaven.javadoc.skip=true -Dcheckstyle.skip

打包 
./dev/make-distribution.sh --tgz  -Dmaven.test.skip=true  -Dmaven.javadoc.skip=true -Dcheckstyle.skip
