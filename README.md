# Branch Exists Action

<!-- markdownlint-disable MD013 -->
[![Action test on Ubuntu](https://github.com/GuillaumeFalourd/branch-exists/actions/workflows/ubuntu_action_test.yml/badge.svg)](https://github.com/GuillaumeFalourd/branch-exists/actions/workflows/ubuntu_action_test.yml) [![Action test on MacOS](https://github.com/GuillaumeFalourd/branch-exists/actions/workflows/macos_action_test.yml/badge.svg)](https://github.com/GuillaumeFalourd/branch-exists/actions/workflows/macos_action_test.yml) [![Action test on Windows](https://github.com/GuillaumeFalourd/branch-exists/actions/workflows/windows_action_test.yml/badge.svg)](https://github.com/GuillaumeFalourd/branch-exists/actions/workflows/windows_action_test.yml)
<!-- markdownlint-enable MD013 -->

☞ GitHub Action to check if a branch exists in the current repo :octocat:

## 📚 Usage

```yaml
- id: check-branch-exists
  uses: GuillaumeFalourd/branch-exists@v1.1
  with:
    branch: <BRANCH_NAME>

- if: steps.check-branch-exists.outputs.exists == 'true'
  run: echo '<BRANCH_NAME> Branch exists'

- if: steps.check-branch-exists.outputs.exists == 'false'
  run: echo '<BRANCH_NAME> Branch NOT FOUND'
```

## 🤝 Contributing

☞ If you're interested in contributing to this repository, please follow the [guidelines](https://github.com/GuillaumeFalourd/branch-exists/blob/main/CONTRIBUTING.md)

## 🏅 Licensed

☞ This repository uses the [Apache License 2.0](https://github.com/GuillaumeFalourd/branch-exists/blob/main/LICENSE)

<!-- ### Contribuidores

<a href="https://github.com/GuillaumeFalourd/branch-exists/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=GuillaumeFalourd/branch-exists" />
</a>

(Criado com [contributors-img](https://contrib.rocks)) -->
