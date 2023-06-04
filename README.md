# dpy-boilerplate

Opinionated boilerplate configurations for bots written in Python using [discord.py](https://github.com/Rapptz/discord.py).

This project contains 2 boilerplate repositories that you can use to kickstart your Discord bot project(s).

## Choosing between basic and advanced

There are a bunch of distinctions between the 2 configs. The major ones are listed below!

| Feature                 | Basic  | Advanced   |
|-------------------------|:------:|:----------:|
| Cog-based architecture  | ✅     | ✅         |
| Prefix command examples | ✅     | ✅         |
| Slash command examples  | ✅     | ✅         |
| Database                | SQLite | PostgreSQL |
| Logging                 | ❌     | ✅         |
| Client session          | ❌     | ✅         |
| Custom help command     | ❌     | ✅         |
| Dev environment         | ❌     | ✅         |

**TL;DR:** Basic is good for a small scale bot with limited features. Advanced has a lot more options that you'd need when having a bigger feature-set.

Note: If you want to set up basic but want a feature from advanced without its entirity, you can grab it from there with little extra config.

## Setup

The general setup for both the templates will look the same.

1. You get the repository cloned on your system
2. Set the initial configuration
3. Search and complete all the FIXMEs in the code. Optionally the TODOs as well.

<details>
<summary>Installation for basic</summary>

1. Clone the repository. Since we want to truncate the git history, let's get the latest zip. Replace `<new-repo-name>` with any name you like.
    ```sh
    curl -L https://git.sr.ht/~getpsyched/dpy-boilerplate-basic/archive/master.tar.gz | gunzip | tar xv
    mv dpy-boilerplate-basic-master <new-repo-name>
    cd <new-repo-name> && git init
    ```

2. Set the environment variables in the `.env`.

3. Done! Simply eliminate the FIXMEs and TODOs and you're setup with a nice little bot repo.
</details>

<details>
<summary>Installation for advanced</summary>

1. Clone the repository. Since we want to truncate the git history, let's get the latest zip. Replace `<new-repo-name>` with any name you like.
    ```sh
    curl -L https://git.sr.ht/~getpsyched/dpy-boilerplate-advanced/archive/master.tar.gz | gunzip | tar xv
    mv dpy-boilerplate-basic-master <new-repo-name>
    cd <new-repo-name> && git init
    ```

2. Set the environment variables in the `.env`.

3. TODO
</details>
