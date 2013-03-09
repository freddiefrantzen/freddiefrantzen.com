Deployment Instructions
===============

Deploy using Phing.

    cd /path/to/code/repoository
    phing deploy

You'll then be prompted to choose which server to deploy to. You might need to run `a2ensite` on the remote server if the target server is anything other than production.
