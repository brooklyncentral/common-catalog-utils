Common Catalog Utils
====================

-   <https://raw.githubusercontent.com/brooklyncentral/common-catalog-utils/master/common/catalog/common/common.bom>
-   <https://raw.githubusercontent.com/brooklyncentral/common-catalog-utils/master/common/tests/common/common.tests.bom>

```YAML
brooklyn.catalog:
  items:
    - https://raw.githubusercontent.com/brooklyncentral/common-catalog-utils/master/common/catalog/common/common.bom
    - https://raw.githubusercontent.com/brooklyncentral/common-catalog-utils/master/common/tests/common/common.tests.bom
```

```YAML
brooklyn.catalog:
  brooklyn.libraries:
    - "https://oss.sonatype.org/service/local/artifact/maven/redirect?r=snapshots&g=io.brooklyn.common&a=common-catalog-utils&v=0.1.0-SNAPSHOT"
  items:
    - classpath://io.brooklyn.common.catalog-utils:common/common.bom
    - classpath://io.brooklyn.common.catalog-utils:tests/common/common.tests.bom
```
