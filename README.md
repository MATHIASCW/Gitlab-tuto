# Follow-along Project — GitLab Tutorial (xavki)

Repository tracking the YouTube playlist **"GitLab : tutos et formation"** by [xavki](https://youtube.com/c/xavki-linux) (35 videos), with hands-on practice set up on GitHub.

- Playlist: https://www.youtube.com/playlist?list=PLn6POgpklwWrRoZZXv0xf71mvT4E0QDOF
- Tutorial author: Xavier Pestel (xavki) — SRE / DevOps / Sysadmin
- Related blog: https://xavki.blog/

## Goal

Follow the training from start to finish to build skills in Git/GitLab (versioning, branches, merge requests, CI/CD, runners...) and document my progress in this repo with reproducible examples.

## Prerequisites

- A GitLab.com account (or a self-hosted / Docker GitLab instance)
- Git installed locally (`git --version`)
- A GitHub account (to host this tracking repo)
- Docker (if the videos cover runners / CI in containers)
-  A code editor (VS Code, etc.)

## Repository structure

```
```

## Resources

- YouTube playlist: https://www.youtube.com/playlist?list=PLn6POgpklwWrRoZZXv0xf71mvT4E0QDOF
- Official GitLab documentation: https://docs.gitlab.com/
- xavki's blog: https://xavki.blog/

## Utils

```
docker inspect gitlab
docker logs -f gitlab
docker exec -it gitlab grep 'Password:' /etc/gitlab/initial_root_password
cat ~./ssh/Key
```

## Status

In progress — repo updated as I move through the tutorial.
