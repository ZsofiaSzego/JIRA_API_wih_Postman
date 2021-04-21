# JIRA_API_wih_Postman
Basic Jira API tests through REST API requests made in Postman.

The collection saved in json contains the following requests:

- add issue
- add comment
- get issue comment
- edit comment
- delete comment
- delete issue

The addedd issue is referenced with issueId variable and the addedd comment is with commentId.

In authentication the username and password is shown as jiraUname variable and jirapw seperately.

The tests check the response status codes and automatically sets the next request. When editing occured the tests contains a JSON value check in the response body.

Change the 'validpassword' and 'validusername' in variables to your jira username and password.
