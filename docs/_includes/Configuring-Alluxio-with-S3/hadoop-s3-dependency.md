```xml
<dependency>
  <groupId>org.alluxio.alluxio</groupId>
  <artifactId>alluxio-client</artifactId>
  <version>{{site.ALLUXIO_RELEASED_VERSION}}</version>
  <exclusions>
    <exclusion>
      <groupId>org.alluxio.alluxio</groupId>
      <artifactId>alluxio-underfs-s3</artifactId>
    </exclusion>
  </exclusions>
</dependency>
```