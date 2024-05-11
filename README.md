# Signed Commit Example

This is the standard commit I adhere to.

<img src="./verified_signature.png" width="480">

This repository contains a mix of unsigned and signed commits.
- Anonymous commit
- Set name commit
- Set email commit
- GPG signed commit, but not add to host
- GPG signed commit, added to host
- Unset email and GPG signed
- GPG signed commit, but set email blank

## Examples
### Anonymous commit

This commit has not set the `user.name` and `user.email` in Git config.
More specifically, **'Anonymous'** is explicitly specified because commits cannot be made without a `user.name`.
Additionally, because the `user.email` is unset, it cannot be linked to a GitHub account, resulting in the commit icon displaying as GitHub's default.

<img src="./anonymous_commit.png" width="480">

<a href="https://github.com/ykws/signed-commit-example/commit/7b53b16316678176e09157309f7a195c1a213c50">7b53b16</a>

### Set name commit

This commit has set the `user.name` in Git config.
The name is displayed as set, but it is not yet linked to a GitHub account.

<img src="./set_name_commit.png" width="480">

<a href="https://github.com/ykws/signed-commit-example/commit/c3022d3c8c482e340e5d17042426205004b53a01">c3022d3</a>

### Set email commit

This commit has set the `user.email` in Git config.
As a result, it is linked to a GitHub account, and the commit displays the GitHub username and icon.

<img src="./set_email_commit.png" width="480">

<a href="https://github.com/ykws/signed-commit-example/commit/81385c7b5b1b6ad2f2779ae3231f7fd48f155c51">81385c7</a>

### GPG signed commit, but not add to host

This commit is a GPG-signed commit, but it has not been added to the host. 
As a result, it is **unverified**.

<img src="./gpg_signed_commit_but_not_add_to_host.png" width="480">

<a href="https://github.com/ykws/signed-commit-example/commit/bb2687467e2587c304287e055edbb14b84d45d6a">bb26874</a>

### GPG signed commit, added to host

This commit is a GPG-signed commit, and it has been added to the host. 
As a result, it is **verified**.

<img src="./gpg_signed_commit_added_to_host.png" width="480">

<a href="https://github.com/ykws/signed-commit-example/commit/8df2e1a139e9adac78cd9579ef3df840a3b36b17">8df2e1a</a>

### Unset email and GPG signed

This commit has not set the `user.email` in Git config and a GPG-signed commit. 
As a result, it is **unverified**.
This results in an outcome similar to a commit where only the `user.name` is set.

<img src="./unset_email_and_gpg_signed.png" width="480">

<a href="https://github.com/ykws/signed-commit-example/commit/b1ef582dfff945ffa1e8b308994ad4ab40eacebc">b1ef582</a>

### GPG signed commit, but set email blank

This commit is a GPG-signed commit, but the email address is not set in the signature. 
As a result, it is **unverified**.

<img src="./gpg_signed_commit_but_set_email_blank.png" width="480">

<a href="https://github.com/ykws/signed-commit-example/commit/20a95e031f2993e197c9a98dd03ca86f804d2eaf">20a95e0</a>
