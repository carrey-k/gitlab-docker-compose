
### Docker compose files

#### Community Edition
docker-compose-ce.yaml

#### Enterprise Edition
docker-compose-ee.yaml

#### Install
`docker-compose up -d -f docker-compose-ce.yaml`

#### Initial root password
The root user password can be found in `your_gitlab_folder/config/initial_root_password`, open it and copy the password to login after installation finished.

Remember to change the password after login as the initial password will be delete after 24h of installation.



#### References
1. https://docs.gitlab.com/ee/install/
2. https://docs.gitlab.com/ee/install/docker.html
3. https://about.gitlab.com/install/
4. https://customers.gitlab.com/plans
5. https://about.gitlab.com/pricing/self-managed/feature-comparison/
6. https://about.gitlab.com/handbook/marketing/strategic-marketing/dot-com-vs-self-managed/
