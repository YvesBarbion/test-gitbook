---
authorinformation: null
---

# Cannot push to remote branch

## Condition

When you want to push a commit to a remote branch, you might get a permission and/or access error.

![](../../../../.gitbook/assets/push_error.png)

## Cause

An access token has not been configured for the command tool. This error might appear if:

* You have multiple Git accounts and the command line tool has saved a different Git user name and password.
* You have used a different Git tool for this account.
* ...

## Remedy

1. Open the **Control Panel**.
2. Go to **User Accounts** &gt; **Credential Manager** &gt; **Mange Windows Credentials**.
3. Under Generic Credentials, remove the GitHub keys.
4. Push the commit again.

   A GitHub login window opens.

5. Fill in your user name and password and click **Log in**.

   The push will be completed.

