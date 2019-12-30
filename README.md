# Prometheus官方文档中文版，个人翻译学习使用

![](https://github.com/Alrights/pics/raw/master/prometheus/logo.png)   

Prometheus是一个开源系统监控和警报系统。

* [介绍](introductions/README.md)
    - [总览](introductions/Overview.md)
    - [开始](introductions/FirstSteps.md)
    - [对比](introductions/Comparison_to_alternatives.md)
    - [常见问题](introductions/FAQ.md)
    - [路线图](introductions/Roadmap.md)
    - [学习媒介](introductions/Media.md)
    - [词汇](introductions/Glossary.md)
* [概念](concepts/README.md)
    - [数据模型](concepts/Data_model.md)
    - [度量指标类型](concepts/Metric_types.md)
    - [任务与实例](concepts/Jobs_and_instances.md)
* [prometheus](prometheus/README.md)
    - [开始](prometheus/Getting_started.md)
    - [安装](prometheus/Installation.md)
    - [配置](prometheus/configuration/)
        * [配置](prometheus/configuration/configuration.md)
        * [记录规则](prometheus/configuration/Recording_rules.md)
        * [预警规则](prometheus/configuration/Altering_rules.md)
        * [模板例子](prometheus/configuration/Template_examples.md)
        * [模板参考](prometheus/configuration/Template_reference.md)
        * [规则的单元测试](prometheus/configuration/Unit_Testing_for_Rules.md)
    - [查询](prometheus/querying/)
        * [基本概念](prometheus/querying/Basics.md)
        * [操作符](prometheus/querying/Operators.md)
        * [函数](prometheus/querying/Functions.md)
        * [举例](prometheus/querying/Examples.md)
        * [HttpAPI](prometheus/querying/HTTP_API.md)
    - [存储](prometheus/Storage.md)
    - [联邦](prometheus/Federation.md)
    - [管理API](prometheus/Management_API.md)
    - [集成](prometheus/Migration.md)
    - [API稳定性](prometheus/API_Stability.md)
* [可视化](visualization/README.md)
    - [表达式浏览器](visualization/Expression_browser.md)
    - [Grafana](visualization/Grafana.md)
    - [控制模板](visualization/Console_template.md)
* [操作](operating/README.md)
    - [安全](operating/Security.md)
    - [集成](operating/Integrations.md)
* [Instrumenting](instrumenting/README.md)
    - [客户端库](instrumenting/Client_libraries.md)
    - [写客户端库](instrumenting/Writing_client_libaries.md)
    - [推送度量指标](instrumenting/Pushing_metrics.md)
    - [导出与集成](instrumenting/Exporters_and_integrations.md)
    - [写导出器](instrumenting/Writing_exporters.md)
    - [导出格式](instrumenting/Exposition_formats.md)
* [警告](alerting/README.md)
    - [警告概览](alerting/Alerting_overview.md)
    - [警告管理器](alerting/Alertmanager.md)
    - [配置](alerting/Configuration.md)
    - [客户端](alerting/Clients.md)
    - [通知模板参考](alerting/Notification_template_reference.md)
    - [通知模板例子](alerting/Notification_template_example.md)
* [最佳实践](best_practices/README.md)
    - [指标和标签命名](best_practices/Metric_and_label_naming.md)
    - [控制台和面板](best_practices/Consoles_and_dashboards.md)
    - [instrumentation](best_practices/Instrumentation.md)
    - [直方图和summaries](best_practices/Histograms_and_summaries.md)
    - [预警](best_practices/Alerting.md)
    - [录制规则](best_practices/Recording_rules.md)
    - [什么时候使用Pushgateway](best_practices/When_to_use_the_pushgateway.md)
* [教程](guides/README.md)
    - [基本授权](guides/Basic_auth.md)
    - [使用cAdvisor监控Docker容器指标](guides/Monitoring_docker_container_metrics_using_cadvisor.md)
    - [使用基于文件的服务发现抓取指标](guides/Use_file_based_service_discovert_to_discover_scrape_targets.md)
    - [使用Node Exporter监控Linux主机指标](guides/Monitoring_linux_host_metrics_with_the_node_exporter.md)
    - [Go应用指南](guides/Instrumenting_a_go_application.md)
    - [TLS加密](guides/TLS_encryption.md)
