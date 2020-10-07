Simple bash script that connects to a mysql db, creates a backup file and uploads it to AWS s3 using AWS CLI.
Credentials are hidden as Secret Text in Jenkins.

Jenkins connects to a remote user via ssh using ssh plugin.
