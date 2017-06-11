# Ansible Management of Development Machine

Update the server just by running `debops` on `athena` or `localhost`:

    debops -l <host>

Update the personal development enviroment (e.g. .vimrc) by:

    debops ansible/playbooks/athena_dev.yml -l <host>

**NOTE** The IP address of `athena` is configured through the SSH config and
is not stored in this repo.

For DebOps information see [my blog post][blog-post].


[blog-post]: http://iamqasimk.com/2017/03/01/setting-up-a-server-with-debops/
