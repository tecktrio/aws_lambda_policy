Aws Lambda Policy
```
{
	"Version": "2012-10-17",
	"Statement": [
		{
			"Sid": "VisualEditor0",
			"Effect": "Allow",
			"Action": [
				"lambda:*",
				"s3:*",
				"events:*",
				"iam:CreateServiceSpecificCredential",
				"iam:GetRole",
				"iam:CreateRole",
				"iam:PutRolePolicy",
				"iam:PassRole",
				"iam:CreateServiceLinkedRole",
				"apigateway:PUT",
				"apigateway:DELETE",
				"apigateway:PATCH",
				"apigateway:POST",
				"apigateway:GET",
				"logs:DescribeLogStreams",
				"logs:FilterLogEvents",
				"cloudformation:DescribeStackResource",
				"cloudformation:DescribeStacks",
				"cloudformation:CreateStack",
				"cloudformation:DeleteStack",
				"cloudformation:UpdateStack",
				"cloudformation:ListStackResources"
			],
			"Resource": "*"
		}
	]
}
```
