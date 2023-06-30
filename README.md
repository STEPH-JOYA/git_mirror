# git_mirror

Setup of git-mirror onto mirror servers
=======================================

This repository provides a deployment script to update
git-mirror servers for the citools.st.com infrastructure.

It installs the git-mirror tool and configuration on each mirroring
server for the gitolite@codex.cro.st.com git repositories through
the acitlsqa application/linux account.

Optionally modify servers.txt files to point to mirror servers.

Then run: ./deploy_all.sh

This will re-install git-mirror at the revision pointed to by git-mirror-rev.txt

add new version for validation testing
