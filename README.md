# Add commit message template with prefixed branch/task

## Rules
https://chris.beams.io/posts/git-commit/

# Steps
  1. mv .prepare-commit-msg ./git/hooks/prepare-commit-msg
  2. chmod +x ./git/hooks/prepare-commit-msg
  3. git config --global commit.template ~/.gitmessage
  4. git commit
