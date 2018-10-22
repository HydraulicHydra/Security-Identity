# Security-Identity
I tried downloading the master-docs folder from the tutorials, but an error kept preventing it from properly extracting the files.  I'm not really fond of these new tutorials that don't actually walk us through how to build these files ourselves.

1. One of the biggest vulnerabilities is SQL Injection.  SQL Injection occurs when a user inputs certain strings into input fields that forces an interpreter to take SQL Commands and reveal or affect database information in typically malicious ways.  There are multiple ways to prevent SQL Injection, the most critical being input sanitization, which essentially prevents certain characters or strings from being input or interpreted in the input fields.

2. ASP.NET Core uses either an SQL Database or Azure Table Storage to store passwords.  Various cipher algorithms can be implemented, matching with cryptographic agility's premise of being able to expand beyond the original cipher capabilities of the system.

3. IdentityRole: Represents a role in the identity system.
    IdentityUserRole: Represents the link between the user and their role.
    IdentityUserClaim: Represents a claim that a user possesses.
    IdentityUserLogin: Represents a login and its associated provider for a user.
    IdentityUserToken: Represents an authentification token for a user.
    IdentityRoleClaim: Represents a claim granted to all users within a role.
