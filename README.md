# k8s-yaml-sanitizer
Removes unnecessary fields from a Kubernetes YAML file


Specific inputYamlFile to the locaion of your input:
```yaml
  test: 
    runs-on: ubuntu-latest
    steps:
    - uses: touchground/k8s-yaml-sanitizer@main
      with:
        inputYamlFile: 'path/to/the/YAML/file.yaml'
```
outputYamlFile is optional, default is same as input.