# force-cmdt-record-insert-ticket
repository for my forcedotcom force:cmdt:record:insert ticket

Having an issue where my force:cmdt:record:insert command only auto-generates an underscore for the first space in a Label which makes it error when I try to deploy

This is the command I'm using in the VS Code terminal:

sfdx force:cmdt:record:insert --filepath "- \CCSCountyCodes_dhEdit_SC_TESTCOPY.csv" --typename County_Code__mdt --namecolumn DeveloperName


Added a test csv that I'm using. And two screenshots, one of the issue inside VS Code.
