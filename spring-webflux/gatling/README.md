执行压力测试：

    cd gatling-scripts
    mvn gatling:test -Dgatling.simulationClass=test.load.sims.LoadSimulation -Dbase.url=http://localhost:8091/ -Dtest.path=hello/300 -Dsim.users=300
    mvn gatling:test -Dgatling.simulationClass=test.load.sims.LoadSimulation -Dbase.url=http://localhost:8091/ -Dtest.path=user/top/300 -Dsim.users=300

[（6）Spring WebFlux性能测试——响应式Spring的道法术器](https://blog.51cto.com/liukang/2090202)


[（7）Spring WebClient与RestTemplate性能对比——响应式Spring的道法](https://blog.51cto.com/liukang/2090211)
