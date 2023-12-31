# About This Repo

- If you are new/unfamilar with AAA servers, read the overview below prior to viewing the other files.
- Essentailly there are two main AAA technologies that will be discussed in this repo:
1. TACACS+
2. RADIUS


# Authentication, Authorization, and Accounting (AAA) Overview

AAA provides three main functions:

- Authentication: Authentication is the process of verifying a user's identity. This is typically done by requiring the user to provide a username and password.
- Authorization: Authorization is the process of determining what resources a user is allowed to access. This is typically done by assigning users roles or permissions.
- Accounting: Accounting is the process of tracking user activity. This information can be used to generate reports, troubleshoot problems, and bill users for network usage.


AAA is typically implemented using a AAA server. The AAA server is responsible for storing user credentials, managing user roles and permissions, and tracking user activity. The AAA server communicates with network devices, such as routers and switches, to authenticate users and authorize access to resources.

## The following is a simplified overview of the AAA process:

1. A user attempts to access a network resource.
2. The network device forwards the user's request to the AAA server.
3. The AAA server authenticates the user and determines the user's permissions.
4. The AAA server sends a response to the network device, indicating whether the user is authorized to access the resource.
5. The network device allows or denies the user access to the resource.

AAA is a critical security mechanism for protecting network resources. By implementing AAA, organizations can help to ensure that only authorized users can access network resources.

[0_x-ZsHs5OD5BXXWnq](https://github.com/paulinoprojects/AAA/assets/111991325/cb1c6c36-0d3c-461e-b3b5-a09e4124b6eb)

## Here are some of the benefits of using AAA:
- Increased security: AAA helps to protect network resources from unauthorized access.
- Granular control: AAA allows for granular control over user access, which can help to prevent unauthorized access to sensitive resources.
- Auditing: AAA can be used to track user activity, which can help to troubleshoot problems and bill users for network usage.
## Here are some of the drawbacks of using AAA:

- Complexity: AAA can be complex to configure and manage.
- Cost: AAA servers can be expensive.
- Not all devices support AAA: Not all network devices support AAA, which can make it difficult to implement AAA in some environments.

Overall, AAA is a valuable security mechanism that can help to protect network resources. However, it is important to weigh the benefits and drawbacks of AAA before deciding whether to implement it.
