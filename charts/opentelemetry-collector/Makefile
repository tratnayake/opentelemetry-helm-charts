command:
	helm upgrade --install -n sales-dev  -f values.yaml --set "access_token=$LS_ACCESS_TOKEN,scenario_file=scenario1,extraVolumes[0].configMap.name=scenario1,extraEnvs[0].value=scenario1" scenario1 ./

command-template:
	helm template  -f values.yaml --set "access_token=$LS_ACCESS_TOKEN,scenario_file=scenario1,extraVolumes[0].configMap.name=scenario1,extraEnvs[0].value=scenario1" scenario1 ./


command-2:
	helm upgrade --install -n sales-dev  -f values.yaml --set "access_token=$LS_ACCESS_TOKEN,scenario_file=scenario1" scenario1 ./

command-template-2:
	helm template  -f values.yaml --set "access_token=$LS_ACCESS_TOKEN" scenario1 ./

command-template-2-debug:
	helm template --debug  -f values.yaml --set "access_token=$LS_ACCESS_TOKEN,scenario_file=scenario1" scenario1 ./

