# bin

`pac-devknife` is a configuration which let's your tekton dashboard be accessible over the internet while allowing you to use a Github App for testing and a localhost:5001 docker repo for iterating over the PAC build using `KO_DOCKER_REPO=localhost:5001` and `ko apply -f config/` in the pipelines-as-code repo.


`watch-pac-pr-sha` helps list the PipelineRuns and PAC related sha
```
watch-pac-pr-sha

NAME                   SHA
tekton-pac-man-bg4lg   72c6a88a905cf72dfaa8462c336f2c127a8e309f
tekton-pac-man-jc8sd   72c6a88a905cf72dfaa8462c336f2c127a8e309f
tekton-pac-man-pll2k   72c6a88a905cf72dfaa8462c336f2c127a8e309f
```
