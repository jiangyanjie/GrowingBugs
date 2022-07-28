# A bug repository that keeps growing, called ***growingBugs***

Notably, each bug is composed of a buggy version, a fixed version, a ***concise patch*** (bug-fixing changes only), and one or more triggering test cases.

We fork growingBugs from https://github.com/liuhuigmail/GrowingBugRepository on Feb 10 2022.

# Contents of growingBugs
To date, growingBugs contains **`487`** bugs from open-source Java projects. 

|   | Project ID      | Project name               |   SubProject name             |Number of bugs | Bug IDs      | 
|-----------------|-----------------|----------------------------|--------------------------------|-------------:|-------------------|
| 1     | Dbutils         | commons-dbutils            |                          |        2       | 1-2                 |
| 2     | Functor         | commons-functor            |                          |        2       | 1-2                 |
| 3     | Imaging         | commons-imaging            |                          |        10      | 1,3-8,10-11,14  |
| 4     | IO              | commons-io                 |                          |        21       | 1-3,5-6,8-18,</br>22,25,27,29-30                |
| 5     | JXR             | maven-jxr                  |                          |        1       | 1                   |
| 6     | MShade          | maven-shade-plugin         |                          |        6       | 1-4,6-7                 |
| 7     | Tika            | tika                       |                          |        5       | 1-2,5-7               |
| 8     | Validator       | commons-validator          |                          |        21      | 1-2,4,6-9,11,</br>13-25 |
| 9     | Pool            | commons-pool               |                          |        18      | 1-2,5-7,10-14,</br>16,20-21,24,</br>26-27,29-30|
| 10     | Email           | commons-email              |                          |        3       | 3-5                 |
| 11     | Graph           | commons-graph              |                          |        3       | 1-3                 |
| 12     | Net             | commons-net                |                          |        14      | 9,10,12,</br>14-18,20-21,</br>23-26             |
| 13     | Numbers_angle   | commons-numbers-angle            |  commons-numbers-angle         |        2       | 1-2               |
| 14     | MGpg            | maven-gpg-plugin           ||        1       | 1               |
| 15     | Text            | commons-text               ||        4       | 1-2,4-5               |
| 16     | Shiro_core            | shiro-core               |      core      |        9       | 37,40,46,52,98,</br>144,176,181,202               |
| 17     | Jena_core            | jena-core               |    jena-core   |        1       | 2               |
| 18     | Shiro_web            | shiro-web               |        web      |        3       | 1,3,7               |
| 19     | MDeploy            | maven-deploy-plugin               |              |        1       | 1               |
| 20     | Jackrabbit_filevault<br/>_vault_validation | jackrabbit-filevault-vault-validation               |       vault-validation       |        4       | 1-4               |
| 21     | Jackrabbit_oak_core            | oak-core               |       oak-core       |        5       | 1-5               |
| 22     | Doxia_module_apt            | doxia-module-apt               |   doxia-modules/doxia-module-apt       |       2       | 1-2               |
| 23     | Xmlgraphics            | xmlgraphics-commons |       |       2     | 1-2              |
| 24     | Rdf_jena            | commons-rdf-jena               |       commons-rdf-jena       |        1       | 1               |
| 25     | Maven_checkstyle_plugin            | maven-checkstyle-plugin               |             |        1       | 1               |
| 26     | James_project_core            | james-project-core               |       core       |        1       | 1               |
| 27     | Pdfbox_fontbox            | pdfbox-fontbox      |       fontbox      |        5       | 1-5               |
| 28     | AaltoXml            | aalto-xml      |             |        4       | 1-4               |
| 29     | HttpClient5            | httpclient5      |       httpclient5      |        7       | 1-2,4-8               |
| 30     | jackson_modules<br/>_java8_datetime      | jackson-modules-java8-datetime |      datetime  |        5       | 1-5               |
| 31     | Pdfbox_pdfbox         | pdfbox-pdfbox |    pdfbox    |        3      | 1-3               |
| 32     | Storm_client            | storm-client      |       storm-client      |        2       | 1-2              |
| 33     | James_mime4j_core            | James-mime4j-core |      core   |       9     | 1-9              |
| 34     | JacksonDataformatsText<br/>_yaml            | jackson-dataformats-text-yaml |      yaml   |       6     | 1-2,4-7              |
| 35     | JacksonDataformatsText<br/>_properties            | jackson-dataformats-text-properties |      properties   |       2     | 1-2              |
| 36     | JacksonDataformatBinary<br/>_avro            | jackson-dataformats-binary-avro |      avro   |       2     | 1-2              |
| 37     | JacksonDataformatBinary<br/>_cbor            | jackson-dataformats-binary-cbor |      cbor   |       5     | 1-5              |
| 38     | JavaClassmate            | java-classmate |        |       2     | 1-2              |
| 39     | JacksonModuleJsonSchema            | jackson-module-jsonSchema |      |       1     | 1              |
| 40     | JacksonDatatypeJoda            | jackson-datatype-joda |        |       3     | 1-3              |
| 41     | Bcel            | commons-bcel |        |       6     | 1-6              |
| 42     | JacksonDataformatBinary<br/>_protobuf            | jackson-dataformats-binary-protobuf |      protobuf   |       4     | 1-4              |
| 43     | Jackrabbit_filevault<br/>_vault_core            | jackrabbit-filevault-vault-core |      vault-core   |       1     | 1              |
| 44     | JacksonDatatypeJsr310            | jackson-datatype-jsr310 |         |       4     | 1-4              |
| 45     | JacksonDataformatBinary<br/>_smile            | jackson-dataformats-binary-smile |    smile     |       3     | 1-3              |
| 46     | JacksonModuleAfterburner            | jackson-module-afterburner |         |       3     | 1-3              |
| 47     | Woodstox            | woodstox |         |       7     | 1-7              |
| 48     | MetaModel_core            | MetaModel-core | core        |       9     | 1-9              |
| 49     | MetaModel_csv            | MetaModel-csv |  csv       |       1     | 1              |
| 50     | MetaModel_excel            | MetaModel-excel |  excel        |       1     | 1              |
| 51     | MetaModel_jdbc            | MetaModel-jdbc |  jdbc       |       3     | 1-3              |
| 52     | MetaModel_pojo            | MetaModel-pojo |  pojo       |       1     | 1              |
| 53     | MetaModel_salesforce            | MetaModel-salesforce |   salesforce      |       1     | 1              |
| 54     | Wink_common            | wink-common |  wink-common       |       4     | 1-4              |
| 55     | Xbean_naming            | xbean-naming |  xbean-naming       |       1     | 1              |
| 56     | James_project_<br/>server_container_core            | james-project-server-container-core |  server/container/core       |       1     | 1              |
| 57     | Johnzon_core            | johnzon-core |  johnzon-core       |       11     | 1-2,4-12              |
| 58     | Nifi_mock            | nifi-mock |  nifi-mock       |       2     | 1-2              |
| 59     | Rat_core            | apache-rat-core |  apache-rat-core       |       1     | 1              |
| 60     | Rat_plugin            | apache-rat-plugin |  apache-rat-plugin       |       1     | 1              |
| 61     | Tez_common            | tez-common |  tez-common       |       1     | 1              |
| 62     | Tinkerpop_gremlin_core            | gremlin-core |  gremlin-core       |       1     | 1              |
| 63     | Webbeans_web            | webbeans-web |  webbeans-web       |       1     | 1              |
| 64     | Hono_client            | hono-client |  client       |       4     | 1-4              |
| 65     | Httpcomponents_core_h2            | httpcore5-h2 |  httpcore5-h2       |       1     | 1              |
| 66     | Httpcomponents_core<br/>_httpcore5            | httpcore5 |  httpcore5       |       3     | 1-3              |
| 67     | Johnzon_jsonb            | johnzon-jsonb |  johnzon-jsonb       |       6     | 1-6              |
| 68     | Johnzon_jaxrs            | johnzon-jaxrs |  johnzon-jaxrs       |       1     | 1              |
| 69     | Hbase_common      | hbase-common |  hbase-common       |       1     | 1              |
| 70     | Incubator_tamaya_api            | incubator-retired-tamaya-api |  code/api       |       2     | 1-2              |
| 71     | James_project_<br/>mailet_standard            | james-project-mailet-standard |  mailet/standard       |       1     | 1              |
| 72     | Johnzon_jsonschema            | johnzon-jsonschema |  johnzon-jsonschema       |       2     | 1-2              |
| 73     | Johnzon_mapper            | johnzon-mapper |  johnzon-mapper       |       6     | 1-6              |
| 74     | Karaf_main            | karaf-main |  main       |       1     | 1              |
| 75     | Appformer_uberfire_<br/>commons_editor_backend            | uberfire-commons-editor-backend |  uberfire-extensions/uberfire-commons-editor/uberfire-commons-editor-backend       |       1     | 1              |
| 76     | Kie_pmml_commons            | kie-pmml-commons |  kie-pmml-trusty/kie-pmml-commons       |       3     | 1-3              |
| 77     | Kie_memory_compiler            | kie-memory-compiler |  kie-memory-compiler       |       1     | 1              |
| 78     | Jbpm_human<br/>_task_workitems            | jbpm-human-task-workitems |  jbpm-human-task/jbpm-human-task-workitems       |       1     | 1              |
| 79     | Drools_traits            | drools-traits |  drools-traits       |       1     | 1              |
| 80     | Drools_model_compiler            | drools-model-compiler |  drools-model/drools-model-compiler       |       1     | 1              |
| 81     | Appformer_uberfire<br/>_security_management</br>_client            | uberfire-security-management-client | uberfire-extensions/uberfire-security/uberfire-security-management/uberfire-security-management-client  |       1     | 1              |
| 82     | Appformer_uberfire<br/>_workbench_client            | uberfire-workbench-client |  uberfire-workbench/uberfire-workbench-client       |       3     | 1-3              |
| 83     | Deltaspike_api            | deltaspike-core-api |  deltaspike/core/api       |       6     | 1-6              |
| 84     | Flume_ngcore            | flume-ng-core |  flume-ng-core       |       2     | 1-2              |
| 85     | Jandex            | jandex |         |       6     | 1-6              |
| 86     | Ognl            | commons-ognl |         |       1     | 1              |
| 87     | Qpid_client            | qpid-jms-client |  qpid-jms-client       |       8     | 1-8              |
| 88     | Switchyard_admin            | switchyard-admin |  admin       |       1     | 1              |
| 89     | Weld_se_core            | weld-se-core |  environments/se/core       |       1     | 1              |
| 90     | Jboss_modules            | jboss-modules |        |       7     | 1-7              |
| 91     | Jboss_threads            | jboss-threads |        |       1     | 1              |
| 92     | Minaftp_api            | ftpserver-api |  ftplet-api       |       1     | 1              |
| 93     | Sling_validation            | sling-org-apache-sling-validation-core |       |       1     | 1              |
| 94     | Switchyard_config            | switchyard-config |  config       |       1     | 1              |
| 95     | Switchyard_validate            | switchyard-validate |  validate       |       1     | 1              |
| 96     | Vysper_nbxml            | vysper-nbxml |  nbxml       |       2     | 1-2              |
| 97     | Wildfly_naming_client            | wildfly-naming-client |     |       2     | 1-2              |
| 98     | Dosgi_common            | dosgi-common | common    |       2     | 1-2              |
| 99     | Fluo_api            | fluo-api | modules/api     |       4     | 1-4              |
| 100     | Hivemall_core            | core |  core   |       3     | 1-3              |
| 101     | Knox_assertion_common            | gateway-provider-</br>identity-assertion</br>-common |  gateway-provider-</br>identity-assertion</br>-common     |       1     | 1              |
| 102     | Oozie_client            | oozie-client | client |       2     | 1-2              |
| 103     | Qpidjms_client            | qpidjms-client | client  |       3     | 1-3              |
| 104     | Rdf4j_query            | rdf4j-query | core/query    |       4     | 1-4              |
| 105     | Rdf4j_rio_api            | rdf4j-rio-api | core/rio/api  |       2     | 1-2              |
| 106     | Rdf4j_rio_jsonld            | rdf4j-rio-jsonld | core/rio/jsonld  |       2     | 1-2              |
| 107     | Rdf4j_rio_rdfjson            | rdf4j-rio-rdfjson | core/rio/rdfjson |       2     | 1-2              |
| 108     | Rdf4j_rio_rdfxml            | rdf4j-rio-rdfxml | core/rio/rdfxml    |       3     | 1-3              |
| 109     | Rdf4j_rio_turtle            | rdf4j-rio-turtle | core/rio/turtle    |       11    | 1-11              |
| 110     | Sentry_ccommon            | sentry-core-common |  sentry-core/sentry-core-common   |       2     | 1-2              |
| 111     | Sling_apiregions            | sling-apiregions |     |       3     | 1-3              |
| 112     | Sling_cpconverter            | sling-cpconverter |     |       3     | 1-3              |
| 113     | Sling_feature            | sling-feature |     |       3     | 1-3              |
| 114     | Tiles_api            | tiles-api | tiles-api    |       2     | 1-2              |
| 115     | Tiles_core            | tiles-core |  tiles-core   |       3     | 1-3              |
| 116     | Twill_dcore            | twill-discovery-core |  twill-discovery-core   |       1     | 1              |
| 117     | Maven2_artifact            | maven-artifact |  maven-artifact   |       2     | 1-2              |
| 118     | Maven2_project            | maven-project |  maven-project   |       2     | 1-2              |
| 119     | Math            | commons-math               |                          |      35       | 1-35               |
| 120     | Wicket_request            | wicket-request               |     wicket-request                     |      6       | 1-6               |
| 121     | Cayenne_xmpp            | cayenne-xmpp               |    cayenne-xmpp                      |      1       | 1               |
| 122     | Wicket_util            | wicket-util               |     wicket-util                     |     4       | 1-4               |
| 123     | Wicket_spring            | wicket-spring               |        wicket-spring                  |      1       | 1               |
| 124     | Cayenne_jgroups            | cayenne-jgroups               |    cayenne-jgroups                      |      1       | 1               |
| 125     | Cayenne_jms            | cayenne-jms               |     cayenne-jms                     |      1       | 1               |
| 126     | Struts1_core            | struts1-core               |     core                     |      2       | 1-2               |
| 127     | Wicket_cdi            | wicket-cdi               |     wicket-cdi                     |      1       | 1               |
| 128     | Wicket_core            | wicket-core               |     wicket-core                     |      18       | 1-18               |
| 129     | Mshared_archiver            | maven-archiver               |     maven-archiver                     |      1       | 1               |
| 130     | Shindig_common            | shindig-common               |     java/common                     |      1       | 1               |
| 131     | Xbean_reflect            | xbean-reflect               |     xbean-reflect                     |      1       | 1               |
| 132     | Mrunit            | mrunit               |                          |      2       | 1-2               |
| 133     | Rave_core            | rave-core               |          rave-components/rave-core         |      2       | 1-2               |
| 134     | Rave_commons            | rave-commons               |          rave-components/rave-commons         |      1       | 1               |
| 135     | Rave_web            | rave-web               |          rave-components/rave-web         |      1       | 1               |
# Setting up GrowingBugs

## Requirements
 - Java 1.8
 - Git >= 1.9
 - SVN >= 1.8
 - Perl >= 5.0.12
 - Curl
 
## Steps to set up GrowingBugs
1. Clone GrowingBugs:
    - `git clone https://github.com/jiangyanjie/GrowingBugs.git`

2. Initialize GrowingBugs:

    Download the project repositories and external libraries that are not included in the git repository for size purposes and to avoid redundancies. We provide a mechanism to download them automatically as follows:
    
    - `cd GrowingBugs`
    - `cpanm --installdeps .`
    - `./init.sh`
    - `./repos.sh`
    
3. Add GrowingBugs's executables to your PATH:
    - `export PATH=$PATH:"path2growingbugs"/framework/bin`

# Using GrowingBugs
1. Checkout a buggy source code version (If the project doesn't hava subproject, `-s` parameter can be ignored):
    - `defects4j checkout -p project_id -v version_id -w work_dir -s subproject_name` 
    
    Example:
  
    - `defects4j checkout -p Shiro_core -v 37b -w /tmp/Shiro_core_37_buggy -s core`
    - `defects4j checkout -p Dbutils -v 1b -w /tmp/dbutils_1_buggy`

   Notably, **GrowingBugs**  supports sub-projects that are not suported by Defects4J. To this end, yor should specify the sub-project with  `-s` parameter in the `checkout`  command. The preceding example common leverages `-s core` to check out sub-proejct `core` from the enclosing project `Shiro_core`. For the `compile` and `test` commands, you should also switch to the sub-project's folder to compile and test the sub-project.

2. Change to the working directory, compile sources and tests, and run tests:

   - `cd work_dir/subproject_name`
   - `defects4j compile`
   - `defects4j test`
   
   Example1：
   
   - `cd /tmp/Shiro_core_37_buggy/core`
   - `defects4j compile`
   - `defects4j test`

   Example2：
   
   - `cd /tmp/dbutils_1_buggy`
   - `defects4j compile`
   - `defects4j test`

Currently, we resuse all APIs of **Defects4J** (more details at  https://github.com/rjust/defects4j), and thus all applications relying on **Defects4J** could be transferred smoothly to **GrowingBugs**. 
 
## Copyright
Notably, this bug repository is based on the well-known **Defects4J** https://github.com/rjust/defects4j. We reuse its source code as well as the bugs in **Defects4J**. The key difference is that **growingBugs** levearages **BugBuilder**[1] to exclude bug-irrelevarange changes from bug-fixing commmits automatically whereas **Defects4J** requests human experts to accomplish the same task. Consequently, **growingBugs** can keep growing automatically even ***without human intervention***.  

## Citation
If you are exploiting our dataset, please kindly cite the following paper:

**[1] Yanjie Jiang, [Hui Liu](https://liuhuigmail.github.io/), Nan Niu, Lu Zhang, Yamin Hu. Extracting Concise Bug-Fixing Patches from Human-Written Patches in Version Control Systems. The 43rd International Conference on Software Engineering (ICSE), pp. 686-698, May, 2021 https://liuhuigmail.github.io/publishedPappers/ICSE2021.pdf**

`@INPROCEEDINGS {GrowingBugs,
author = {Yanjie Jiang and Hui Liu and Nan Niu and Lu Zhang and Yamin Hu},
booktitle = {IEEE/ACM 43rd International Conference on Software Engineering (ICSE 2021)},
title = {Extracting Concise Bug-Fixing Patches from Human-Written Patches in Version Control Systems},
year = {2021},
pages = {686-698},
doi = {10.1109/ICSE43902.2021.00069},
url = {https://doi.ieeecomputersociety.org/10.1109/ICSE43902.2021.00069},
publisher = {IEEE Computer Society},
address = {Los Alamitos, CA, USA},
month = {may}
}`
