# IT-Project-5
## Managing the savn.local Domain
### Objective
Begin basic system administration activities on the network. Create basic OUs for the savn.local domain. Also, to create and manipulate user accounts on the servers.

### Description
An organizational unit (OU) offers a way to achieve more flexibility in managing the resources associated with a business unit, department, or division than is possible through domain administration alone.
- An OU is a grouping of related objects within a domain, similar to the idea of having sub-directories within a directory.
- OUs are typically used to reflect the structure of the organization without having to completely restructure the domains with the that structure changes.
- OUs allow the grouping of objects so that they can be administered using the same group policies, such as security.

------------------------------------------------------------------------------------------------------------------------------------------
## Introduction and Requirements

### Steps
1. Set up three OUs: administration, research, and sales.
2. On Carlos-S19-S2 create a local, non-domain oriented account. Name the local user account as: _localuser01_.
3. Create a user account in the savn.local domain. Name the domain user account as: _domainUser01_.
4. Start and run Carlos-W10-C1. Attempt to log in as the new savn.local domain user created (domainUser01).

### Screenshots
1. Created the three new OUs within the savn.local domain.
2. Created a local user account.
3. Created a domain user within the savn.local domain.
4. Moved the domain user account into the Administration OU.
5. Successfully login to the domain on Carlos-S19-S2 using the domain user account.
6. Shut down the domain controller (Carlos-S19-S1) and attempt to login to the domain using the domain user account from Carlos-W10-C1.
   Illustrate that the login attempt was denied as no domain controller was available to handle the request.

------------------------------------------------------------------------------------------------------------------------------------------

## License

    Copyright [2022] [Carlos Fuentes]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
