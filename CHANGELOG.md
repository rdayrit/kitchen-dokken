# Dokken Changelog

## 2.1.2
- Making a CHANGELOG.md
- Updated gem spec to depend on test-kitchen ~> 1.5

## 2.1.1 
- Fixed busser (serverspec, etc) test data uploading

## 2.0.0
- Uses chef/chef (instead of someara/chef)

- Bind mounts data instead of uploading through kitchen-cache container when
  talking to a local Docker host. (most use cases)  

- Renders a Dockefile and builds dokken/kitchen-cache when taling to a
  remote Docker host. (DOCKER_HOST =~ /^tcp:/)

## 1.0.0
- First stable release. 
- Relied on someara/chef and someara/kitchen-cache from the
  Docker hub.