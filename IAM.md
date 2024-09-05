__IAM allows us to manage users and access allowed to those users in a centralized manner.__

	- IAM policy is a JSON file
	- IAM in universal and not region based
	- Root user has full admin access including account delete
	- New user have no access by default and only get access key pair for API and Command line access, not management console
	- Users can only download secret keys once and need to regenerate on loss
## Benefits:
- central control
- shared access
- granular control
- identity federation (external providers)

## We can setup:
- user - actual people and individually allowed access
- groups - group of users with the same access - user can be assigned to groups
- roles - specific role of a user and relevant permission - roles can be assigned to users
- policy - set of permissions - can be attached to user or group or role

## Allows:
- Multifactor auth 
- Temporary access
- Password rotation policies
- AWS service integration
- PCI DSS compliance (for payment apps)

## IAM dashboard:
- Add MFA using 3rd party tools
- Create user, group, role
- Assign policies directly to user, group or role
- Set password policies
- Allow services to access other services without storing credentials directly on them

## Testing IAM:
AWS Policy Simulator allows us to test IAM policies by allowing us to simulate if users can perform actions on AWS services before committing them.




