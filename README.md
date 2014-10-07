mongoBatis Configuration
==============================
1. mongoBatis / mongoBastis_Project / src / main / webapp / WEB-INF / spring / appServlet / servlet-context.xml
 
2. write property value.(noSqlConfig.xml)
<beans:bean id="configFile" class="ga.mongobatis.parse.MainParse">
<beans:property name="mongoBatis" value="C:/Work/workspace/mongoBastis_Project/noSqlConfig.xml" />
</beans:bean>

3. Run.
