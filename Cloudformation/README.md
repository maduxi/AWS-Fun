# EMR
Cloudformation template for how to create an EMR cluster with:

- 1 Master instance
- 2 Core instances
- Some Hadoop applications
- Add a bootstrap script to install libraries
- Use an external hive metastore
- Add an autoscaling group
- Install a task runner for data pipeline jobs
- Update a Route53 record