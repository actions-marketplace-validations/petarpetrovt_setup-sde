# setup-sde

<p align="left">
    <a href="https://github.com/petarpetrovt/setup-sde/actions/workflows/build.yml" alt="Build">
        <img alt="Build" src="https://github.com/petarpetrovt/setup-sde/actions/workflows/build.yml/badge.svg" />
    </a>
    <a href="https://github.com/petarpetrovt/setup-sde/actions/workflows/codeql-analysis.yml" alt="CodeQL">
        <img alt="CodeQL" src="https://github.com/petarpetrovt/setup-sde/actions/workflows/codeql-analysis.yml/badge.svg" />
    </a>
    <a href="https://github.com/petarpetrovt/setup-sde/graphs/contributors" alt="Contributors">
        <img alt="Contributors" src="https://img.shields.io/github/contributors/petarpetrovt/setup-sde?label=Contributors">
    </a>
</p>

This action sets up Intel's SDE binaries for use in actions by:

* Downloading and extracting SDE binaries
* Providing environment variable

## Usage

See [action.yml](action.yml)

```YML
- name: Setup SDE binaries
  uses: petarpetrovt/setup-sde@v1.2
```

```YML
- name: Setup SDE binaries
  uses: petarpetrovt/setup-sde@v1.2
  with:
    environmentVariableName: MY_CUSTOM_NAME # default value is `SDE_PATH`
    sdeVersion: 8.63.0-2021-01-18 # default value is `8.69.1-2021-07-18`
```

## Authors

* **Petar Petrov**

See also the list of [contributors](https://github.com/SharpPTP/setup-sde/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
