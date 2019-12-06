# Redmine Edit Issue Author

Redmine plugin that allows to change issue author.


## Installation

Follow standard Redmine plugin installation procedure.

 * Move `redmine_editauthor/` to `$REDMINE/plugins/`.


## Configuration

#### Permissions

This plugin provides 2 permissions:

 * *Edit author* allows to edit author of existing issue.
 * *Set original author* allows to set author when creating new issue.

Authorized users will be able to see author field and change its value in issue
form.
    

#### Possible authors
 
All active users are listed for public projects.
Only project members are listed for private projects.

## Requirements

This plugin has been written with compatibility in mind to keep it
functional across many different versions of Redmine:

  * Redmine (`>= 3.0`)
