# gocd.io pipelines for some openbakery projects

## Requisite

The gocd-json-config-plugin needs to be installed: see https://github.com/tomzo/gocd-json-config-plugin/


## Server Configuration

```
<config-repos>
  <config-repo plugin="json.config.plugin">
    <git url="git@github.com:openbakery/gocd-config-repo.git" />
  </config-repo>
</config-repos>
```
