# CBDDFW_JAN_2023
CucumberBDD FW with TestNG and Maven

# How to run the test, paste this in the terminal
mvn verify -Denv=qa -Dbrowser=Chrome -Dcucumber.filter.tags="@test"

mvn verify -Denv=qa -Dbrowser=ff -Dcucumber.filter.tags="@smoke"
mvn verify -Denv=qa -Dbrowser=Chrome -Dcucumber.filter.tags="@smoke"
mvn verify -Denv=stg -Dbrowser=Chrome -Dcucumber.filter.tags="@test"
mvn verify -Denv=qa -Dbrowser=Chrome -Dcucumber.filter.tags="@smoke"
mvn verify -Denv=prod -Dbrowser=ff -Dcucumber.filter.tags="@smoke"





