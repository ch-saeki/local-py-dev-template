DEPLOY_DIR = .local_deploy

.PHONY: run stop cleanup

run:
	docker-compose -f $(DEPLOY_DIR)/docker-compose.yml up

stop:
	docker-compose -f $(DEPLOY_DIR)/docker-compose.yml stop

cleanup:
	docker-compose -f $(DEPLOY_DIR)/docker-compose.yml down --rmi all -v
