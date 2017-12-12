**Be aware that these bug reports are publicly viewable, so please do not include any sensitive information in your bug report - this includes passwords, access tokens, sensitive data, etc**

Please use this text as a template, filling in the relevant bits and deleting the existing text,

Please search the existing issues to check that your issue hasn't already been reported.
If it has, please comment on the existing issue.

Choose a label for the issue from the "Labels" menu next to this input, to indicate the severity of the problem:
* critical bug: work is blocked, application crash, or loss of data
* major bug: common feature incorrectly/not functioning
* minor bug: other issues


## What happened?

Describe the problem.
Please keep this short and to the point. 
Be as specific as possible. Avoid using "it" as in "it doesn't work".
Only report one problem per issue.

Example:

I received the error message `Error in parse_aws_s3_response(r, Sig, verbose = verbose) : Forbidden (HTTP 403).` when trying to open the "alpha-everyone" bucket from the S3 Explorer widget in RStudio


## Steps to reproduce the problem

Can you reproduce the problem consistently?

Example:

1. In RStudio, enter `s3browser::file_explorer_s3()`
2. In the "Viewer" tab, click on the "File select" button
3. Click on the "alpha-everyone" folder


## Expected behaviour

Describe what was supposed to happen

Example:

I expected to see the contents of the "alpha-everyone" bucket displayed
