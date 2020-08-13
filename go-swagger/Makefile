swagger:
	docker run --rm -v $(shell dirname ${PWD})/schema:/schema -v ${PWD}:/app -w /app ezio1119/go-swagger \
	generate server -f ./openapi-2.0.yml -A sample --exclude-main