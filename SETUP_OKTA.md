# Instructions for Okta Development account

## A. Setup a Okta developer account

1. Register developer accounts at [developer.okta.com](https://developer.okta.com/)

## B. Create Application in Okta Developer

1. Login to your developer instance.
2. Navigate to `Application` menu.
3. Click on `Add Application` button.
4. Click on `Create New App`.
5. With in the dialog select `Web` as the Platform, `OpenID Connect` for Sign on method and then the Create button.
6. In the `Create OpenID Connection Integration` screen. 

    - Enter Application Name.
    - Enter Login redirect URIs. 

7. Under the `General` tab. 

    - Allowed grant types, confirm Authorization code is selected.
    - Make note of the `Client ID` and `Client Secret`.

8. Under the `Sign On` tab.

    - Make note of the `Issuer` URIs.

## C. Create a Security Group and User

### I. Create a test User

1. Navigate to `Directory` menu.
2. Select `People` option.
3. Click on `Add Person`.

    - Enter First Name.
    - Enter Last Name.
    - Enter Username.
    - Select "`Set by admin`" under Password.
    - Enter Password.
    - Uncheck "`User must change password on first login`".

4. Complete by clicking `Save`.

### II. Create a Security group

1. Navigate to `Directory` menu.
2. Select `Groups` option.
3. Click on `Add Group`.

    - Enter Group Name. (i.e. acmeinc-admins)
    - Enter Group Desciption. (i.e. Adminstrators for Acme Inc.)

4. Complete by clicking on `Add Group`.
5. On the Group screen select the newly created group.
6. Click on `Manage People`.
7. Search the user that you created and add user to `Members` by hovering over the user and clicking the plus icon.
8. Complete by clicking `Save`.

### Additional reading material regarding OpenID Connect

- [OIDC Primer, part 1](https://developer.okta.com/blog/2017/07/25/oidc-primer-part-1)
- [OIDC Primer, part 2](https://developer.okta.com/blog/2017/07/25/oidc-primer-part-2)
- [OIDC Primer, part 3](https://developer.okta.com/blog/2017/07/25/oidc-primer-part-3)
