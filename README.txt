Add the following to your POM to use with resource filtering:
<filters>
  <filter>/etc/${project.artifactId}/${project.artifactId}.properties</filter>
</filters>
