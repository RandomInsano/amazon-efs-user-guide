# Managing Amazon EFS file systems<a name="managing"></a>

File system management tasks refer to creating and deleting file systems, managing tags, managing file system backups, managing access, and managing network accessibility with mount targets of existing file system\.

You can perform these file system management tasks using the AWS Management Console, or programmatically using the AWS Command Line Interface \(AWS CLI\) or API, as discussed in the following sections\.

**Topics**
+ [Managing file system network accessibility](manage-fs-access.md)
+ [Managing file system tags](manage-fs-tags.md)
+ [EFS storage classes](storage-classes.md)
+ [EFS lifecycle management](lifecycle-management-efs.md)
+ [Metering: How Amazon EFS reports file system and object sizes](metered-sizes.md)
+ [Managing Amazon EFS file system costs using AWS Budgets](use-aws-budgets-efs-cost.md)
+ [Managing access to encrypted file systems](managing-encrypt.md)

If you are new to Amazon EFS, we recommend that you try the following exercises that provide you with first\-hand end\-to\-end experience using an Amazon EFS file system:
+ [Getting Started](getting-started.md) – This exercise provides a console\-based, end\-to\-end setup in which you create a file system, mount it on an Amazon EC2 instance, and test the setup\. The console takes care of many things for you and thus helps you quickly set up the end\-to\-end experience\.
+ [Walkthrough: Create an Amazon EFS File System and Mount It on an Amazon EC2 Instance Using the AWS CLI](wt1-getting-started.md) – This walkthrough is similar to the Getting Started exercise, but it uses the AWS CLI to perform most of the tasks\. Because the CLI commands closely map to the Amazon EFS API, the walkthrough can help you familiarize yourself with the Amazon EFS API\. 