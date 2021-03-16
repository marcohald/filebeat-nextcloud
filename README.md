# filebeat-nextcloud
This is tested against Nextcloud 20 

The parsing is not ideal, but it matched all events in my environment.

If you would like to use this with docker, make sure that all user can read the audit log.

You can do this in the nextcloud Config with:

`'logfilemode' => 0644,`

If you have additions please create a Pull Request

Here is a Issue at the Nextcloud Repo where better logging options are discussed https://github.com/nextcloud/server/issues/26127
