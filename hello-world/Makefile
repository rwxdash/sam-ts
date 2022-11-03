build-HelloWorldFunction:
	npm install
	npm run build
	cp package.json "$(ARTIFACTS_DIR)/"
	npm --prefix "$(ARTIFACTS_DIR)/" install --production
	cp -r dist "$(ARTIFACTS_DIR)/"
