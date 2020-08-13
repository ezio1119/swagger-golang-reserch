swagger:
	docker run --rm -v $(shell dirname ${PWD})/schema:/schema -v ${PWD}:/app -w /app openapitools/openapi-generator-cli \
	generate -i /schema/openapi-3.0.yml -g go-gin-server --additional-properties=packageName=sample