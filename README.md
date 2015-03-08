# esqy
Run elasticsearch queries from json file, like in examples folder.

# install

	python setup.py install

# examples

	esqy examples/health.json
	esqy -h localhost:9200 examples/health.json
	esqy -h user:passwd@localhost:9200 examples/health.json
