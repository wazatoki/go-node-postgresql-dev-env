.PHONY: clean
clean:
	@echo "clean build dir"

.PHONY: migrateUP
migrateUP:
	migrate -path migrations -database postgres://tmp_project_name:tmp_project_name@tmp_project_name_db:5432/tmp_project_namedb?sslmode=disable up

.PHONY: migrateDOWN
migrateDOWN:
	migrate -path migrations -database postgres://tmp_project_name:tmp_project_name@tmp_project_name_db:5432/tmp_project_namedb?sslmode=disable down

.PHONY: migrateCreate
migrateCreate:
	ARG=""
	migrate create -ext sql -dir migrations -seq ${ARG}