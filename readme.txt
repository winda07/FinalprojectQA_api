reqres : https://reqres.in/

API METHOD
1. GET
2. POST
3. PUT
4. DELETE
5. PATCH

In reqres have some response
	1.1 201 for post create
	1.2 200 for success
	1.3 204 no contenct
	1.4 404 not found.

1.GET https://reqres.in/api/users
Get all user data

2.GET https://reqres.in/api/users/<id>
Get user data by ID

3.GET https://reqres.in/api/users?page=1
Get user data in page 1

4.GET https://reqres.in/api/users?page=2
Get user data in page 2

5.GET https://reqres.in/api/users?delay=3
Get user data within delay in seconds(3)

6.POST https://reqres.in/api/users
Create user

7.POST https://reqres.in/api/login
Login user, will return access token

8.POST https://reqres.in/api/register
Register user, will return access token

9.PUT https://reqres.in/api/users/2
Update data by ID

10.DELETE https://reqres.in/api/users/2
Delete data by ID

11.PATCH https://reqres.in/api/users/2
Update data by ID

test case connect to jira -> AP -2 Winda- TC - post login successful.tc
