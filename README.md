# BW-documentation-sso-protocol-update

# This directory (project-tests) will be used as a test bed for the Boilerplate-Server-Node

## Creating bwtc-devops-sandbox profile to run this in our sandbox account

Make sure you have setup SSO via the console. If not reachout to devops@bitwiseindustries.com to have an SSO account created for you before you proceed

1. Run `aws configure sso --profile bwtc-devops-sandbox`
2. SSO session name (Recommended): hit enter to skip unless you have an existing session
3. SSO start URL : terminal should automatically open URL, if not open the link below
  In order to access SSO, use this https://bitwiseindustries.awsapps.com/start
  
4. SSO region : `us-west-2`
5. SSO Accounts Available to you: (Select Desired account, and enter)
6. SSO there are multiple roles available to you: (Select Desired roles, and enter)
7. CLI default client Region : `us-west-2`
8. CLI default output format : `json`

After following the steps you are ready to use terraform. Make sure you change your profile to match that of the `--profile bwtc-devops-sandbox` you did in step 1.

If terraform does not work for any reason, you can get it running by re authenticating again by running the following:
 `aws sso login --profile bwtc-devops-sandbox`


# Link to project assignment https://github.com/orgs/Shift3/projects/122?pane=issue&itemId=25025566

