## Git Hook

```shell
git config --global init.templatedir '~/.git-templates'

mkdir -p ~/.git-templates/hooks
```

### post-checkout

```shell
touch ~/.git-templates/hooks/post-checkout

chmod 755 ~/.git-templates/hooks/post-checkout

# Change ~/.gitconfig
# [git.eng.example.com]
#     name = Ming Xu
#     email = mingx@example.com
# [gitlab.eng.example.com]
#     name = Ming Xu
#     email = mingx@example.com
#
# Define username, email for special domain git repo
```