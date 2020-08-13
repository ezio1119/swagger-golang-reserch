swagger:
	docker run --rm  -v $(shell dirname ${PWD})/schema:/schema -v ${PWD}:/app -w /app swaggerapi/swagger-codegen-cli-v3 \
	generate -i /schema/openapi-3.0.yml -l go-server --additional-properties=packageName=sample