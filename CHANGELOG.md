# Changelog

## [insiders] (master)

Note: Can be used with `nvuillam/mega-linter@insiders` in your GitHub Action mega-linter.yml file, or with `nvuillam/mega-linter@latest` docker image

- Linter versions upgrades
  - [snakemake](https://snakemake.readthedocs.io/en/stable/) from 6.5.2 to **6.5.3** on 2021-07-07
  - [checkov](https://www.checkov.io/) from 2.0.251 to **2.0.253** on 2021-07-07
  - [php](https://www.php.net) from 7.4.19 to **7.4.21** on 2021-07-07
  - [sql-lint](https://github.com/joereynolds/sql-lint) from 0.0.18 to **0.0.19** on 2021-07-08
  - [checkov](https://www.checkov.io/) from 2.0.253 to **2.0.257** on 2021-07-08
<!-- linter-versions-end -->

## [4.37.0] 2021-06-22

- Downgrade npm to npm@latest-6 to avoid idealTree error when using npm install
- Use pip to install ansible & ansible-lint as alpine apk package ansible disappeared
- Add `--doc` argument to build.sh to generate doc only when requested (manually, or from CI job Auto-Update-Linters)
- Add rust in default installations as it is required for latest pip cryptography package

- Linter versions upgrades
  - [rstfmt](https://github.com/dzhu/rstfmt) from 0.0.0 to **0.0.9** on 2021-06-24
  - [sfdx-scanner-apex](https://forcedotcom.github.io/sfdx-scanner/) from 2.9.1 to **2.9.2** on 2021-06-24
  - [sfdx-scanner-aura](https://forcedotcom.github.io/sfdx-scanner/) from 2.9.1 to **2.9.2** on 2021-06-24
  - [sfdx-scanner-lwc](https://forcedotcom.github.io/sfdx-scanner/) from 2.9.1 to **2.9.2** on 2021-06-24
  - [snakemake](https://snakemake.readthedocs.io/en/stable/) from 6.4.1 to **6.5.0** on 2021-06-24
  - [terraform-fmt](https://www.terraform.io/docs/cli/commands/fmt.html) from Terraform.v1.0.0 to **1.0.0** on 2021-06-24
  - [terragrunt](https://terragrunt.gruntwork.io) from 0.30.7 to **0.31.0** on 2021-06-24
  - [snakemake](https://snakemake.readthedocs.io/en/stable/) from 6.5.0 to **6.5.1** on 2021-06-24
  - [terraform-fmt](https://www.terraform.io/docs/cli/commands/fmt.html) from 1.0.0 to **1.0.1** on 2021-06-24
  - [prettier](https://prettier.io/) from 2.3.1 to **2.3.2** on 2021-06-27
  - [checkstyle](https://checkstyle.sourceforge.io) from 8.43 to **8.44** on 2021-06-28
  - [checkov](https://www.checkov.io/) from 2.0.226 to **2.0.228** on 2021-06-28
  - [checkov](https://www.checkov.io/) from 2.0.228 to **2.0.229** on 2021-06-28
  - [checkov](https://www.checkov.io/) from 2.0.229 to **2.0.230** on 2021-06-28
  - [checkov](https://www.checkov.io/) from 2.0.230 to **2.0.232** on 2021-06-28
  - [cfn-lint](https://github.com/martysweet/cfn-lint) from 0.51.0 to **0.52.0** on 2021-07-05
  - [hadolint](https://github.com/hadolint/hadolint) from 2.5.0 to **2.6.0** on 2021-07-05
  - [eslint](https://eslint.org) from 7.29.0 to **7.30.0** on 2021-07-05
  - [eslint-plugin-jsonc](https://ota-meshi.github.io/eslint-plugin-jsonc/) from 1.3.1 to **1.4.0** on 2021-07-05
  - [phpstan](https://phpstan.org/) from 0.12.90 to **0.12.91** on 2021-07-05
  - [pylint](https://www.pylint.org) from 2.8.3 to **2.9.3** on 2021-07-05
  - [snakemake](https://snakemake.readthedocs.io/en/stable/) from 6.5.1 to **6.5.2** on 2021-07-05
  - [checkov](https://www.checkov.io/) from 2.0.232 to **2.0.250** on 2021-07-05
  - [terrascan](https://www.accurics.com/products/terrascan/) from 1.7.0 to **1.8.0** on 2021-07-05
  - [checkov](https://www.checkov.io/) from 2.0.250 to **2.0.251** on 2021-07-05

## [4.36.0] 2021-06-22

- Fix Phive (php package manager) installation
- Fix dependency error with importlib_metadata before build

- Linter versions upgrades
  - [clj-kondo](https://github.com/borkdude/clj-kondo) from 2021.04.23 to **2021.06.18** on 2021-06-22
  - [cfn-lint](https://github.com/martysweet/cfn-lint) from 0.50.0 to **0.51.0** on 2021-06-22
  - [hadolint](https://github.com/hadolint/hadolint) from 2.4.1 to **2.5.0** on 2021-06-22
  - [dotenv-linter](https://dotenv-linter.github.io/) from 3.0.0 to **3.1.0** on 2021-06-22
  - [golangci-lint](https://golangci-lint.run/) from 1.40.1 to **1.41.1** on 2021-06-22
  - [npm-groovy-lint](https://nvuillam.github.io/npm-groovy-lint/) from 8.1.0 to **8.2.0** on 2021-06-22
  - [htmlhint](https://htmlhint.com/) from 0.14.2 to **0.15.1** on 2021-06-22
  - [eslint](https://eslint.org) from 7.28.0 to **7.29.0** on 2021-06-22
  - [eslint-plugin-jsonc](https://ota-meshi.github.io/eslint-plugin-jsonc/) from 1.2.1 to **1.3.1** on 2021-06-22
  - [phpstan](https://phpstan.org/) from 0.12.88 to **0.12.90** on 2021-06-22
  - [isort](https://pycqa.github.io/isort/) from 5.8.0 to **5.9.1** on 2021-06-22
  - [clippy](https://github.com/rust-lang/rust-clippy) from 0.1.52 to **0.1.53** on 2021-06-22
  - [snakefmt](https://github.com/snakemake/snakefmt) from 0.4.0 to **0.4.1** on 2021-06-22
  - [cspell](https://github.com/streetsidesoftware/cspell/tree/master/packages/cspell) from 5.6.0 to **5.6.6** on 2021-06-22
  - [sqlfluff](https://www.sqlfluff.com/) from 0.5.6 to **0.6.0** on 2021-06-22
  - [terraform-fmt](https://www.terraform.io/docs/cli/commands/fmt.html) from Terraform.v0.15.5 to **Terraform.v1.0.0** on 2021-06-22
  - [terragrunt](https://terragrunt.gruntwork.io) from 0.29.8 to **0.30.7** on 2021-06-22
  - [terrascan](https://www.accurics.com/products/terrascan/) from 1.6.0 to **1.7.0** on 2021-06-22
  - [tflint](https://github.com/terraform-linters/tflint) from 0.29.0 to **0.29.1** on 2021-06-22

## [4.35.0] 2021-06-12

- Fix [#304](https://github.com/nvuillam/mega-linter/issues/304): Display error message when docker is not found when running mega-linter-runner
- Calculate sum of docker pulls for main page counter badge
- Check _RULES_PATH for active_only_if_file_found check ([#418](https://github.com/nvuillam/mega-linter/pull/418), by [Omeed Musavi](https://github.com/omusavi))
- Upgrade clj-kondo 2021.04.23-alpine
- Upgrade to python:3.9.5-alpine
- Partial fix [#481](https://github.com/nvuillam/mega-linter/issues/481): Allow applying fixes on push events ([PR487](https://github.com/nvuillam/mega-linter/pull/487) by [Vít Kučera](https://github.com/vkucera))
- Fix build.sh on windows
- Add trivy security check of all built Mega-Linter docker images

- Linter versions upgrades
  - [terragrunt](https://terragrunt.gruntwork.io) from 0.29.2 to **0.29.3** on 2021-05-16
  - [shfmt](https://github.com/mvdan/sh) from 3.2.4 to **3.3.0** on 2021-05-18
  - [phpstan](https://phpstan.org/) from 0.12.87 to **0.12.88** on 2021-05-18
  - [cfn-lint](https://github.com/martysweet/cfn-lint) from 0.49.1 to **0.49.2** on 2021-05-19
  - [cpplint](https://github.com/cpplint/cpplint) from 1.5.4 to **1.5.5** on 2021-05-21
  - [scalafix](https://scalacenter.github.io/scalafix/) from 0.9.27 to **0.9.28** on 2021-05-21
  - [snakemake](https://snakemake.readthedocs.io/en/stable/) from 6.3.0 to **6.4.0** on 2021-05-21
  - [terraform-fmt](https://www.terraform.io/docs/cli/commands/fmt.html) from Terraform.v0.15.3 to **Terraform.v0.15.4** on 2021-05-21
  - [terragrunt](https://terragrunt.gruntwork.io) from 0.29.3 to **0.29.4** on 2021-05-21
  - [sfdx-scanner-apex](https://forcedotcom.github.io/sfdx-scanner/) from 2.8.0 to **2.9.1** on 2021-05-22
  - [sfdx-scanner-aura](https://forcedotcom.github.io/sfdx-scanner/) from 2.8.0 to **2.9.1** on 2021-05-22
  - [sfdx-scanner-lwc](https://forcedotcom.github.io/sfdx-scanner/) from 2.8.0 to **2.9.1** on 2021-05-22
  - [jscpd](https://github.com/kucherenko/jscpd/tree/master/packages/jscpd) from 3.3.25 to **3.3.26** on 2021-05-24
  - [eslint](https://eslint.org) from 7.26.0 to **7.27.0** on 2021-05-24
  - [clj-kondo](https://github.com/borkdude/clj-kondo) from 2021.02.13 to **2021.04.23** on 2021-05-24
  - [terragrunt](https://terragrunt.gruntwork.io) from 0.29.4 to **0.29.5** on 2021-05-24
  - [snakemake](https://snakemake.readthedocs.io/en/stable/) from 6.4.0 to **6.4.1** on 2021-05-28
  - [terragrunt](https://terragrunt.gruntwork.io) from 0.29.5 to **0.29.6** on 2021-05-28
  - [terragrunt](https://terragrunt.gruntwork.io) from 0.29.6 to **0.29.7** on 2021-05-29
  - [cspell](https://github.com/streetsidesoftware/cspell/tree/master/packages/cspell) from 4.1.3 to **5.5.2** on 2021-05-30
  - [checkstyle](https://checkstyle.sourceforge.io) from 8.42 to **8.43** on 2021-05-30
  - [scalafix](https://scalacenter.github.io/scalafix/) from 0.9.28 to **0.9.29** on 2021-05-30
  - [pylint](https://www.pylint.org) from 2.8.2 to **2.8.3** on 2021-06-01
  - [cfn-lint](https://github.com/martysweet/cfn-lint) from 0.49.2 to **0.50.0** on 2021-06-04
  - [terraform-fmt](https://www.terraform.io/docs/cli/commands/fmt.html) from Terraform.v0.15.4 to **Terraform.v0.15.5** on 2021-06-04
  - [terragrunt](https://terragrunt.gruntwork.io) from 0.29.7 to **0.29.8** on 2021-06-04
  - [eslint](https://eslint.org) from 7.27.0 to **7.28.0** on 2021-06-05
  - [prettier](https://prettier.io/) from 2.3.0 to **2.3.1** on 2021-06-07
  - [protolint](https://github.com/yoheimuta/protolint) from 0.31.0 to **0.32.0** on 2021-06-07
  - [cspell](https://github.com/streetsidesoftware/cspell/tree/master/packages/cspell) from 5.5.2 to **5.6.0** on 2021-06-07
  - [sql-lint](https://github.com/joereynolds/sql-lint) from 0.0.17 to **0.0.18** on 2021-06-07
  - [tflint](https://github.com/terraform-linters/tflint) from 0.28.1 to **0.29.0** on 2021-06-07

## [4.34.0] 2021-04-30

- Fix bug in Mega-Linter plugins installation (related to [#PR403](https://github.com/nvuillam/mega-linter/pull/403))

- Linter versions upgrades
  - [sqlfluff](https://www.sqlfluff.com/) from 0.5.3 to **0.5.5** on 2021-05-14
  - [hadolint](https://github.com/hadolint/hadolint) from 2.4.0 to **2.4.1** on 2021-05-15
  - [golangci-lint](https://golangci-lint.run/) from 1.40.0 to **1.40.1** on 2021-05-15
  - [sqlfluff](https://www.sqlfluff.com/) from 0.5.5 to **0.5.6** on 2021-05-15

## [4.33.0] 2021-04-30

- Split Salesforce sfdx-scanner into pmd, eslint aura and eslint lwc

- Linter versions upgrades
  - [snakemake](https://snakemake.readthedocs.io/en/stable/) from 6.1.1 to **6.1.2** on 2021-04-20
  - [stylelint](https://stylelint.io) from 13.12.0 to **13.13.0** on 2021-04-25
  - [hadolint](https://github.com/hadolint/hadolint) from 2.2.0 to **2.3.0** on 2021-04-25
  - [eslint](https://eslint.org) from 7.24.0 to **7.25.0** on 2021-04-25
  - [pylint](https://www.pylint.org) from 2.7.4 to **2.8.0** on 2021-04-25
  - [snakemake](https://snakemake.readthedocs.io/en/stable/) from 6.1.2 to **6.2.1** on 2021-04-25
  - [terrascan](https://www.accurics.com/products/terrascan/) from 1.4.0 to **1.5.0** on 2021-04-25
  - [checkstyle](https://checkstyle.sourceforge.io) from 8.41.1 to **8.42** on 2021-04-25
  - [pylint](https://www.pylint.org) from 2.8.0 to **2.8.1** on 2021-04-25
  - [tflint](https://github.com/terraform-linters/tflint) from 0.27.0 to **0.28.0** on 2021-04-25
  - [pylint](https://www.pylint.org) from 2.8.1 to **2.8.2** on 2021-04-27
  - [cfn-lint](https://github.com/martysweet/cfn-lint) from 0.48.3 to **0.49.0** on 2021-04-28
  - [phpstan](https://phpstan.org/) from 0.12.84 to **0.12.85** on 2021-04-28
  - [terragrunt](https://terragrunt.gruntwork.io) from 0.28.21 to **0.29.0** on 2021-04-28
  - [snakemake](https://snakemake.readthedocs.io/en/stable/) from 6.2.1 to **6.3.0** on 2021-04-30
  - [terrascan](https://www.accurics.com/products/terrascan/) from 1.5.0 to **1.5.1** on 2021-04-30

## [4.32.0] 2021-04-20

- Fix #376 : Link-title to license
- Add support from prettier as JSON formatter ([#421](https://github.com/nvuillam/mega-linter/pull/421), by [Omeed Musavi](https://github.com/omusavi)

- Linter versions upgrades
  - [phpstan](https://phpstan.org/) from 0.12.82 to **0.12.83** on 2021-04-03
  - [markdown-table-formatter](https://www.npmjs.com/package/markdown-table-formatter) from 1.0.4 to **1.1.0** on 2021-04-05
  - [tflint](https://github.com/terraform-linters/tflint) from 0.25.0 to **0.26.0** on 2021-04-05
  - [sqlfluff](https://www.sqlfluff.com/) from 0.4.1 to **0.5.0** on 2021-04-06
  - [cfn-lint](https://github.com/martysweet/cfn-lint) from 0.48.1 to **0.48.2** on 2021-04-07
  - [yamllint](https://yamllint.readthedocs.io/) from 1.26.0 to **1.26.1** on 2021-04-07
  - [snakemake](https://snakemake.readthedocs.io/en/stable/) from 6.1.0 to **6.1.1** on 2021-04-08
  - [terragrunt](https://terragrunt.gruntwork.io) from 0.28.16 to **0.28.19** on 2021-04-09
  - [phpcs](https://github.com/squizlabs/PHP_CodeSniffer) from 3.5.8 to **3.6.0** on 2021-04-09
  - [eslint](https://eslint.org) from 7.23.0 to **7.24.0** on 2021-04-10
  - [sqlfluff](https://www.sqlfluff.com/) from 0.5.0 to **0.5.1** on 2021-04-10
  - [protolint](https://github.com/yoheimuta/protolint) from 0.30.1 to **0.31.0** on 2021-04-11
  - [sqlfluff](https://www.sqlfluff.com/) from 0.5.1 to **0.5.2** on 2021-04-11
  - [sfdx-scanner](https://forcedotcom.github.io/sfdx-scanner/) from 2.7.0 to **2.8.0** on 2021-04-14
  - [terragrunt](https://terragrunt.gruntwork.io) from 0.28.19 to **0.28.21** on 2021-04-15
  - [cfn-lint](https://github.com/martysweet/cfn-lint) from 0.48.2 to **0.48.3** on 2021-04-17
  - [flake8](https://flake8.pycqa.org) from 3.9.0 to **3.9.1** on 2021-04-17
  - [tflint](https://github.com/terraform-linters/tflint) from 0.26.0 to **0.27.0** on 2021-04-19
  - [hadolint](https://github.com/hadolint/hadolint) from 2.1.0 to **2.2.0** on 2021-04-19
  - [phpstan](https://phpstan.org/) from 0.12.83 to **0.12.84** on 2021-04-19
  - [shellcheck](https://github.com/koalaman/shellcheck) from 0.7.1 to **0.7.2** on 2021-04-19

## [4.31.0] 2021-04-03

- Keep license pre-formatted in docs
- Use Python virtual-environment in dev-dependencies shell example
- Fix #367 : Display editorconfig-checker version
- Fix #379 : New configuration FAIL_IF_MISSING_LINTER_IN_FLAVOR
- Add Reviewdog JSONL Reporter

- Linter versions upgrades
  - [flake8](https://flake8.pycqa.org) from 3.8.4 to **3.9.0** on 2021-03-15
  - [ktlint](https://ktlint.github.io) from 0.40.0 to **0.41.0** on 2021-03-21
  - [phpstan](https://phpstan.org/) from 0.12.81 to **0.12.82** on 2021-03-21
  - [isort](https://pycqa.github.io/isort/) from 5.7.0 to **5.8.0** on 2021-03-21
  - [sfdx-scanner](https://forcedotcom.github.io/sfdx-scanner/) from 2.6.0 to **2.7.0** on 2021-03-21
  - [sql-lint](https://github.com/joereynolds/sql-lint) from 0.0.15 to **0.0.16** on 2021-03-21
  - [swiftlint](https://github.com/realm/SwiftLint) from 0.43.0 to **0.43.1** on 2021-03-21
  - [editorconfig-checker](https://editorconfig-checker.github.io/) from 0.0.0 to **2.3.4** on 2021-03-22
  - [ktlint](https://ktlint.github.io) from 0.41.0 to **0.40.0** on 2021-03-22
  - [cfn-lint](https://github.com/martysweet/cfn-lint) from 0.47.2 to **0.48.1** on 2021-03-30
  - [coffeelint](http://www.coffeelint.org) from 4.1.3 to **4.1.4** on 2021-03-30
  - [hadolint](https://github.com/hadolint/hadolint) from 1.23.0 to **2.0.0** on 2021-03-30
  - [golangci-lint](https://golangci-lint.run/) from 1.38.0 to **1.39.0** on 2021-03-30
  - [checkstyle](https://checkstyle.sourceforge.io) from 8.41 to **8.41.1** on 2021-03-30
  - [eslint](https://eslint.org) from 7.22.0 to **7.23.0** on 2021-03-30
  - [kubeval](https://www.kubeval.com/) from 0.15.0 to **0.16.1** on 2021-03-30
  - [perlcritic](https://metacpan.org/pod/Perl::Critic) from 1.138 to **1.140** on 2021-03-30
  - [pylint](https://www.pylint.org) from 2.7.2 to **2.7.4** on 2021-03-30
  - [clippy](https://github.com/rust-lang/rust-clippy) from 0.0.212 to **0.1.51** on 2021-03-30
  - [scalafix](https://scalacenter.github.io/scalafix/) from 0.9.26 to **0.9.27** on 2021-03-30
  - [terragrunt](https://terragrunt.gruntwork.io) from 0.28.9 to **0.28.16** on 2021-03-30
  - [kubeval](https://www.kubeval.com/) from 0.16.0 to **0.16.1** on 2021-03-30
  - [pylint](https://www.pylint.org) from 2.7.3 to **2.7.4** on 2021-03-30
  - [editorconfig-checker](https://editorconfig-checker.github.io/) from 2.3.4 to **2.3.5** on 2021-03-31
  - [hadolint](https://github.com/hadolint/hadolint) from 2.0.0 to **2.1.0** on 2021-04-02
  - [snakemake](https://snakemake.readthedocs.io/en/stable/) from 6.0.5 to **6.1.0** on 2021-04-02

## [4.30.0] 2021-03-14

- Fix #361 - Not respecting `*_DISABLE_ERRORS: false`
- New variable **FORMATTERS_DISABLE_ERRORS** to force all formatters to be blocking if errors are found
- Add *.svg in .jscpd (copy-paste detector) default ignore paths

- Linter versions upgrades
  - [cfn-lint](https://github.com/martysweet/cfn-lint) from 0.47.1 to **0.47.2** on 2021-03-13
  - [eslint](https://eslint.org) from 7.21.0 to **7.22.0** on 2021-03-13
  - [eslint-plugin-jsonc](https://ota-meshi.github.io/eslint-plugin-jsonc/) from 1.1.0 to **1.2.1** on 2021-03-14

## [4.29.0] 2021-03-12

- Fix regex to list Salesforce errors
- Fix Updated Files Reporter when Mega-Linter is not running on GitHub Action
- Fix #359 - invalid literal with _DISABLE_ERRORS_IF_LESS_THAN

- Linter versions upgrades
  - [clj-kondo](https://github.com/borkdude/clj-kondo) from 2021.01.20 to **2021.02.13** on 2021-03-01
  - [jscpd](https://github.com/kucherenko/jscpd/tree/master/packages/jscpd) from 3.3.24 to **3.3.25** on 2021-03-06
  - [hadolint](https://github.com/hadolint/hadolint) from 1.22.1 to **1.23.0** on 2021-03-06
  - [golangci-lint](https://golangci-lint.run/) from 1.37.1 to **1.38.0** on 2021-03-06
  - [markdownlint](https://github.com/DavidAnson/markdownlint) from 0.26.0 to **0.27.1** on 2021-03-06
  - [snakemake](https://snakemake.readthedocs.io/en/stable/) from 6.0.0 to **6.0.2** on 2021-03-06
  - [sqlfluff](https://www.sqlfluff.com/) from 0.4.0 to **0.4.1** on 2021-03-06
  - [swiftlint](https://github.com/realm/SwiftLint) from 0.42.0 to **0.43.0** on 2021-03-06
  - [terrascan](https://www.accurics.com/products/terrascan/) from 1.3.3 to **1.4.0** on 2021-03-06
  - [stylelint](https://stylelint.io) from 13.11.0 to **13.12.0** on 2021-03-06
  - [tflint](https://github.com/terraform-linters/tflint) from 0.24.1 to **0.25.0** on 2021-03-06
  - [shfmt](https://github.com/mvdan/sh) from 3.2.2 to **3.2.4** on 2021-03-10
  - [cfn-lint](https://github.com/martysweet/cfn-lint) from 0.46.0 to **0.47.0** on 2021-03-10
  - [git_diff](https://git-scm.com) from 2.30.1 to **2.30.2** on 2021-03-10
  - [phpstan](https://phpstan.org/) from 0.12.80 to **0.12.81** on 2021-03-10
  - [protolint](https://github.com/yoheimuta/protolint) from 0.29.0 to **0.30.1** on 2021-03-10
  - [snakefmt](https://github.com/snakemake/snakefmt) from 0.3.1 to **0.4.0** on 2021-03-10
  - [snakemake](https://snakemake.readthedocs.io/en/stable/) from 6.0.2 to **6.0.3** on 2021-03-10
  - [cfn-lint](https://github.com/martysweet/cfn-lint) from 0.47.0 to **0.47.1** on 2021-03-12
  - [powershell](https://github.com/PowerShell/PSScriptAnalyzer) from 7.1.2 to **7.1.3** on 2021-03-12
  - [snakemake](https://snakemake.readthedocs.io/en/stable/) from 6.0.3 to **6.0.5** on 2021-03-12
  - [terragrunt](https://terragrunt.gruntwork.io) from 0.28.6 to **0.28.9** on 2021-03-12

## [4.28.0] 2021-03-01

- Feature: **<LINTER_NAME>_DISABLE_ERRORS_IF_LESS_THAN** : set linter status to warning if maximum allowed errors is not reached
- Add colors in logs

- Linter versions upgrades
  - [pylint](https://www.pylint.org) from 2.6.0 to **2.6.2** on 2021-02-16
  - [golangci-lint](https://golangci-lint.run/) from 1.36.0 to **1.37.0** on 2021-02-19
  - [phpstan](https://phpstan.org/) from 0.12.76 to **0.12.77** on 2021-02-19
  - [sfdx-scanner](https://forcedotcom.github.io/sfdx-scanner/) from 2.5.1 to **2.6.0** on 2021-02-19
  - [terragrunt](https://terragrunt.gruntwork.io) from 0.28.2 to **0.28.6** on 2021-02-19
  - [terrascan](https://www.accurics.com/products/terrascan/) from 1.3.2 to **1.3.3** on 2021-02-19
  - [stylelint](https://stylelint.io) from 13.10.0 to **13.11.0** on 2021-02-21
  - [golangci-lint](https://golangci-lint.run/) from 1.37.0 to **1.37.1** on 2021-02-21
  - [phpstan](https://phpstan.org/) from 0.12.77 to **0.12.78** on 2021-02-21
  - [pylint](https://www.pylint.org) from 2.6.2 to **2.7.0** on 2021-02-22
  - [cfn-lint](https://github.com/martysweet/cfn-lint) from 0.45.0 to **0.46.0** on 2021-02-24
  - [pylint](https://www.pylint.org) from 2.7.0 to **2.7.1** on 2021-02-24
  - [eslint-plugin-jsonc](https://ota-meshi.github.io/eslint-plugin-jsonc/) from 0.9.0 to **1.0.0** on 2021-02-25
  - [phpstan](https://phpstan.org/) from 0.12.78 to **0.12.79** on 2021-02-25
  - [protolint](https://github.com/yoheimuta/protolint) from 0.28.2 to **0.29.0** on 2021-02-25
  - [jscpd](https://github.com/kucherenko/jscpd/tree/master/packages/jscpd) from 3.3.23 to **3.3.24** on 2021-02-28
  - [eslint](https://eslint.org) from 7.20.0 to **7.21.0** on 2021-02-28
  - [scalafix](https://scalacenter.github.io/scalafix/) from 0.9.25 to **0.9.26** on 2021-02-28
  - [snakemake](https://snakemake.readthedocs.io/en/stable/) from 5.32.2 to **6.0.0** on 2021-02-28
  - [checkstyle](https://checkstyle.sourceforge.io) from 8.40 to **8.41** on 2021-03-01
  - [eslint-plugin-jsonc](https://ota-meshi.github.io/eslint-plugin-jsonc/) from 1.0.0 to **1.1.0** on 2021-03-01
  - [phpstan](https://phpstan.org/) from 0.12.79 to **0.12.80** on 2021-03-01
  - [pylint](https://www.pylint.org) from 2.7.1 to **2.7.2** on 2021-03-01
  - [clj-kondo](https://github.com/borkdude/clj-kondo) from 2021.01.20 to **2021.02.13** on 2021-03-01

## [4.27.0] 2021-02-16

- Linters
  - Format YAML with prettier

- Core
  - Lint docker image using [Dockle](https://github.com/goodwithtech/dockle)

- Fixes
  - Fix ansible-lint test cases for new version
  - Update --help expected return code for shfmt ash formatter and revive go linter
  - Add --write to update files fixed by eslint
  - Pimp Mega-Linter sources by adding newLines when missing (manually and from build.py) + fix logger initialization error + call python3 by default ([PR329](https://github.com/nvuillam/mega-linter/pull/329) by [Tom Klingenberg](https://github.com/ktomk))
  - Increase max line length to 500 in yaml-lint default configuration

- Linter versions upgrades
  - [ansible-lint](https://ansible-lint.readthedocs.io/en/latest/) from 4.2.0 to **5.0.0** on 2021-02-09
  - [bash-exec](https://tiswww.case.edu/php/chet/bash/bashtop.html) from 5.0.17 to **5.1.0** on 2021-02-09
  - [cfn-lint](https://github.com/martysweet/cfn-lint) from 0.44.6 to **0.44.7** on 2021-02-09
  - [hadolint](https://github.com/hadolint/hadolint) from 1.21.0 to **1.22.1** on 2021-02-09
  - [git_diff](https://git-scm.com) from 2.26.2 to **2.30.1** on 2021-02-09
  - [php](https://www.php.net) from 7.3.26 to **7.4.15** on 2021-02-09
  - [phpstan](https://phpstan.org/) from 0.12.71 to **0.12.74** on 2021-02-09
  - [protolint](https://github.com/yoheimuta/protolint) from 0.28.0 to **0.28.2** on 2021-02-09
  - [lintr](https://github.com/jimhester/lintr) from 2.0.1.9000 to **0.0.0** on 2021-02-09
  - [snakemake](https://snakemake.readthedocs.io/en/stable/) from 5.32.0 to **5.32.1** on 2021-02-09
  - [terragrunt](https://terragrunt.gruntwork.io) from 0.27.1 to **0.28.2** on 2021-02-09
  - [ansible-lint](https://ansible-lint.readthedocs.io/en/latest/) from 5.0.0 to **0.0.0** on 2021-02-09
  - [dotnet-format](https://github.com/dotnet/format) from 4.1.131201 to **5.0.211103** on 2021-02-12
  - [stylelint](https://stylelint.io) from 13.9.0 to **13.10.0** on 2021-02-12
  - [phpstan](https://phpstan.org/) from 0.12.74 to **0.12.75** on 2021-02-12
  - [powershell](https://github.com/PowerShell/PSScriptAnalyzer) from 7.0.4 to **7.1.2** on 2021-02-12
  - [snakemake](https://snakemake.readthedocs.io/en/stable/) from 5.32.1 to **5.32.2** on 2021-02-12
  - [coffeelint](http://www.coffeelint.org) from 4.1.2 to **4.1.3** on 2021-02-14
  - [eslint](https://eslint.org) from 7.19.0 to **7.20.0** on 2021-02-14
  - [phpstan](https://phpstan.org/) from 0.12.75 to **0.12.76** on 2021-02-14
  - [black](https://black.readthedocs.io/en/stable/) from 19.10 to **20.8** on 2021-02-15
  - [snakefmt](https://github.com/snakemake/snakefmt) from 0.2.6 to **0.3.0** on 2021-02-15
  - [sqlfluff](https://www.sqlfluff.com/) from 0.3.6 to **0.4.0** on 2021-02-15
  - [cfn-lint](https://github.com/martysweet/cfn-lint) from 0.44.7 to **0.45.0** on 2021-02-16
  - [snakefmt](https://github.com/snakemake/snakefmt) from 0.3.0 to **0.3.1** on 2021-02-16

## [4.26.2] 2021-01-29

- Linter versions upgrades
  - [shfmt](https://github.com/mvdan/sh) from 3.2.1 to **3.2.2** on 2021-01-30
  - [yamllint](https://yamllint.readthedocs.io/) from 1.25.0 to **1.26.0** on 2021-01-30
  - [hadolint](https://github.com/hadolint/hadolint) from 1.20.0 to **1.21.0** on 2021-02-02
  - [checkstyle](https://checkstyle.sourceforge.io) from 8.39 to **8.40** on 2021-02-02
  - [eslint](https://eslint.org) from 7.18.0 to **7.19.0** on 2021-02-02
  - [phpstan](https://phpstan.org/) from 0.12.70 to **0.12.71** on 2021-02-02
  - [tflint](https://github.com/terraform-linters/tflint) from 0.23.1 to **0.24.1** on 2021-02-02
  - [cfn-lint](https://github.com/martysweet/cfn-lint) from 0.44.5 to **0.44.6** on 2021-02-03
  - [terrascan](https://www.accurics.com/products/terrascan/) from 1.3.1 to **1.3.2** on 2021-02-04

## [4.26.1] 2021-01-29

- Fixes
  - Prevent `unexpected token` error using mega-linter-runner on old versions of node
  - [#293](https://github.com/nvuillam/mega-linter/issues/293) Fix CI for PR from forked repositories
  - [#295](https://github.com/nvuillam/mega-linter/issues/295) Fix crash when .cspell.json is not parseable (wrong JSON format)
  - [#311](https://github.com/nvuillam/mega-linter/issues/295) Add java in salesforce flavor descriptor because it is used by Apex PMD

- Linter versions upgrades
  - [phpstan](https://phpstan.org/) from 0.12.68 to **0.12.69** on 2021-01-24
  - [cfn-lint](https://github.com/martysweet/cfn-lint) from 0.44.4 to **0.44.5** on 2021-01-25
  - [golangci-lint](https://golangci-lint.run/) from 1.35.2 to **1.36.0** on 2021-01-27
  - [protolint](https://github.com/yoheimuta/protolint) from 0.27.0 to **0.28.0** on 2021-01-27
  - [hadolint](https://github.com/hadolint/hadolint) from 1.19.0 to **1.20.0** on 2021-01-28
  - [phpstan](https://phpstan.org/) from 0.12.69 to **0.12.70** on 2021-01-28
  - [clj-kondo](https://github.com/borkdude/clj-kondo) from 2020.09.09 to **2021.01.20** on 2021-01-28

## [4.26.0] 2021-01-24

- Core architecture
  - Manage remote `mega-linter.yml` configuration files
  - New property **EXTENDS**, allowing to inherit from remote `mega-linter.yml` configuration files
  - Add docker-in-docker management (reuse running docker instance)
  - Allow to skip auto apply fixes with commit or PR if latest commit text contains `skip fix`
  - Provide new issue link to create a new flavor to improve performances

- Linters
  - Add [revive](https://github.com/mgechev/revive) GO linter
  - Add [SwiftLint](https://github.com/realm/SwiftLint) for Swift language
  - New Mega-Linter flavor **swift**
  - Get correct version for eslint-plugin-jsonc

- Linter versions upgrades
  - [snakefmt](https://github.com/snakemake/snakefmt) from 0.2.5 to **0.2.6** on 2021-01-22
  - [terrascan](https://www.accurics.com/products/terrascan/) from 1.3.0 to **1.3.1** on 2021-01-22
  - [eslint-plugin-jsonc](https://ota-meshi.github.io/eslint-plugin-jsonc/) from 6.14.10 to **0.9.0** on 2021-01-24

## [4.25.0] 2021-01-22

- Linters
  - Add SQL linter [sqlfluff](https://github.com/sqlfluff/sqlfluff)

- Fixes
  - [#269](https://github.com/nvuillam/mega-linter/issues/269) eslint: .eslintrc.yml is considered as found whereas it's not located in workspace root

- Linter versions upgrades
  - [stylelint](https://stylelint.io) from 13.8.0 to **13.9.0** on 2021-01-19
  - [markdown-table-formatter](https://www.npmjs.com/package/markdown-table-formatter) from 1.0.1 to **1.0.4** on 2021-01-19
  - [terrascan](https://www.accurics.com/products/terrascan/) from 1.2.0 to **1.3.0** on 2021-01-19
  - [cfn-lint](https://github.com/martysweet/cfn-lint) from 0.44.3 to **0.44.4** on 2021-01-19
  - [powershell](https://github.com/PowerShell/PSScriptAnalyzer) from 7.1.1 to **7.0.4** on 2021-01-19
  - [sfdx-scanner](https://forcedotcom.github.io/sfdx-scanner/) from 2.4.0 to **2.5.1** on 2021-01-21
  - [terragrunt](https://terragrunt.gruntwork.io) from 0.26.7 to **0.27.1** on 2021-01-22

## [4.24.1] 2021-01-19

- mega-linter-runner --install
  - Create .jscpd.json file if copy-paste detection is activated
  - Display ending message

- Fixes
  - [#266](https://github.com/nvuillam/mega-linter/issues/266): shfmt error in python flavor, and reactivate BASH_SHFMT and DOCKERFILE_HADOLINT for own sources linting)

- Linter versions upgrades
  - [powershell](https://github.com/PowerShell/PSScriptAnalyzer) from 7.1.0 to **7.1.1** on 2021-01-15
  - [eslint](https://eslint.org) from 7.17.0 to **7.18.0** on 2021-01-16
  - [eslint-plugin-jsonc](https://ota-meshi.github.io/eslint-plugin-jsonc/) from 7.17.0 to **7.18.0** on 2021-01-16
  - [scalafix](https://scalacenter.github.io/scalafix/) from 0.9.24 to **0.9.25** on 2021-01-16
  - [snakemake](https://snakemake.readthedocs.io/en/stable/) from 5.31.1 to **5.32.0** on 2021-01-16
  - [protolint](https://github.com/yoheimuta/protolint) from 0.26.1 to **0.27.0** on 2021-01-18
  - [phpstan](https://phpstan.org/) from 0.12.67 to **0.12.68** on 2021-01-19

## [4.24.0] 2021-01-14

- Linters
  - Add [markdown-table-formatter](https://github.com/nvuillam/markdown-table-formatter)
  - Fix python error when CSpell found no errors

- Linter versions upgrades
  - [v8r](https://github.com/chris48s/v8r) from 0.4.0 to **0.5.0** on 2021-01-14
  - [phpstan](https://phpstan.org/) from 0.12.66 to **0.12.67** on 2021-01-14
  - [psalm](https://psalm.dev) from 4.3.1 to **Psalm.4.x-dev@** on 2021-01-14

## [4.23.3] 2021-01-14

- Fix `.cspell.json` file updater

- Linter versions upgrades
  - [v8r](https://github.com/chris48s/v8r) from 0.4.0 to **0.5.0** on 2021-01-14

## [4.23.2] 2021-01-14

- mega-linter-runner --install:
  - Fix `.mega-linter.yml` DISABLE property when nothing in it
  - Add default `.cspell.json` if spelling mistakes detector is activated

## [4.23.1] 2021-01-12

- Core
  - Refactor part of Linter & reporters to manage correctly logs when linter cli_lint_mode is `project` or `list_of_files`
    - Generate ConsoleLinter and Text reports based from Linter.files_lint_results instead of at each loop
    - When TAP Reporter active, switch linters with cli_lint_mode == "list_of_files" to "files"
    - Fix linter output when cli_lint_mode == "list_of_files"
  - Decrease number of Dockerfile steps

## [4.23.0] 2021-01-12

- Core
  - If the linter is a formatter, errors are not considered as blocking errors by default

- Linters
  - Add **prettier** to format Javascript and Typescript. **standard** remains default
  - Add **remark-lint** to check and fix Markdown files. **markdownlint** remains default

- Linter versions upgrades
  - [golangci-lint](https://golangci-lint.run/) from 1.35.1 to **1.35.2** on 2021-01-11
    - [golangci-lint](https://golangci-lint.run/) from 1.35.0 to **1.35.1** on 2021-01-11
    - [golangci-lint](https://golangci-lint.run/) from 1.34.1 to **1.35.0** on 2021-01-08
  - [cfn-lint](https://github.com/martysweet/cfn-lint) from 0.44.2 to **0.44.3** on 2021-01-09
  - [tflint](https://github.com/terraform-linters/tflint) from 0.23.0 to **0.23.1** on 2021-01-10
  - [dotenv-linter](https://dotenv-linter.github.io/) from 2.2.1 to **3.0.0** on 2021-01-11
    - Update Mega-Linter to call dotenv-linter v3 with `fix` and not `--fix` anymore
  - [phpstan](https://phpstan.org/) from 0.12.65 to **0.12.66** on 2021-01-11

## [4.22.1] 2021-01-07

- Core
  - Improve `warning` status in logs
  - Remove timestamp at each log line

- Enhance integration with GitLab CI
  - Update configuration generator
  - Update core to clean logs when in GitLab CI context

## [4.22.0] 2021-01-06

- Core
  - Allow user to configure custom scripts in `.mega-linter.yml` to run before and after linting, with variables `PRE_RUN` and `POST_RUN`
  - Fix wrong linter status bug
  - Enhance configuration variables performances
  - Rename XXX_FILE_NAME into XXX_CONFIG_FILE

- Linters
  - Add JSONC (json with comments) linting with eslint-plugin-jsonc

## [4.21.0] 2021-01-03

- Linters
  - Add misspell spell checker
  - Allow to define cli_lint_errors_regex in descriptors to extract number of errors from linter output stdout
  - Call linters CLIs with list of files instead of once by file, to improve performances
    - eslint
    - markdownlint
    - pylint
    - flake8
    - isort

- Core
  - Implement architecture for Mega-Linter plugins
  - Count number of errors in linter logs with regexes (`cli_lint_errors_count` and `cli_lint_errors_regex` in descriptor files)
  - Cleanup unused legacy from Super-Linter

- Reports
  - Better icons for Console, GitHub Comment and Text reporters: ✅ ❌

- Documentation
  - Add Install button for VsCode IDE extensions when available
  - Add Install button for JetBrains IDEs extensions when available
  - Add a new page **All linters** listing all linters and references to Mega-Linter in their documentation
  - Add json-schema documentation generation and references

- CI
  - Use `quick build` and `TEST_KEYWORDS` in commit messages, to improve contributor experience

- Fixes
  - Upgrade .tflint default config to work with new tflint version

## [4.20.0] 2020-12-28

- Flavors
  - Add **ci_light** flavor for only CI config files (Dockerfile,Jenkinsfile,JSON,YAML,XML)
  - Add **salesforce** flavor for Salesforce projects (DX or Metadata)
  - If all required linters are not in the current flavor, just skip them with a warning message

- Core
  - Add Json Schema for descriptors (allows validation and auto-completion from IDEs)
  - Add Json Schema for .mega-linter.yml configuration files

## [4.19.0] 2020-12-27

- Installation
  - Add a yeoman generator in mega-linter-runner to initialize configuration in a repository: `npx mega-linter-runner --install`

- Linters
  - New linter v8r to validate json and yaml files with schemastore.org

## [4.18.0] 2020-12-23

- Core
  - Do not suggest flavors when Mega-Linter validates only the diff files (`VALIDATE_ALL_CODE_BASE: false`)
  - Fix ConsoleReporter active linters table content
  - Check if linter is able to fix before flagging it as a fixing linter during runtime

- Flavors
  - New flavor: **documentation**

- Reporters
  - Support GitHub Enterprise for GitHub Comment Reporter
  - Support GitHub Enterprise for GitHub Status Reporter

- Doc
  - Add docker pulls badge in flavors documentation
  - Generate list of references to Mega-Linter

## [4.17.0] 2020-12-18

- Core
  - Allow to use remote linters configuration files with LINTER_RULES_PATH
  - Add `.jekyll-cache` in the list of ignored folders by default
  - Arrange display of Flavor suggestions (text and order) in reporter logs
- Build
  - Dynamically generate (build.py) the list of flavors in github actions workflows
- Doc
  - Reorganize online documentation menus
- Linters
  - Add new linter git_diff to check for git conflicts markers
  - Fix rakudo installation
  - Fix phpstan installation

## [4.16.0] 2020-12-14

- Flavored Mega-Linters
  - Generate lightweight docker images to improve Mega-Linter performances on some language based projects
  - During Mega-Linter run, suggest user to use a flavor and write it in reporters
  - Update descriptor YML files to define flavours
  - Update build.py to create one Dockerfile by Mega-Linter flavour & flavors documentation
  - New GHA workflows to build all flavoured Mega-Linters when pushing in master

- Fixes
  - Output reporter problems as warnings
  - Do not make Mega-Linter fail in case GitHubStatusReporter fails

- Doc
  - Rename "index" pages into more meaningful labels

## [4.15.0] 2020-12-13

- Add Vue.js linting (eslint-plugin-vue added in dependencies)

- Configuration parameters changes:
  - Change config setting logic: `EXCLUDED_DIRECTORIES` is now replacing original directory list instead of extending it
  - Add config setting: `ADDITIONAL_EXCLUDED_DIRECTORIES` extends `EXCLUDED_DIRECTORIES` directory list
  - Add config setting: `&lt;LINTER_KEY&gt;_FILE_EXTENSIONS` to override corresponding value from linter descriptor file
  - Add config setting: `&lt;LINTER_KEY&gt;_FILE_NAMES_REGEX` to override corresponding value from linter descriptor file

- Descriptor yaml schema changes:
  - Rename `files_names_not_ends_with` to `file_names_not_ends_with`
  - Rename `files_names` to `files_names_regex` and change behavior to expect regular expressions in the list.
    They are applied using full match (i.e. the whole text should match the regular expression)

- Fix error message from Email Reporter when SMTP password is not set
- Fix automerge action yml (skip if secrets.PAT is not set)
- Improve caching of compiled regular expressions
- Override mkdocs theme to make analytics work

- CI
  - Auto update linters and documentation: Create update PR only if linter versions has been updated
  - Build and deploy docker images only when it is relevant (not in case of just documentation update for example)

## [4.14.2] 2020-12-07

- Quick fix Github Comment Reporter
- Reorder linters for reports

## [4.14.1] 2020-12-07

- Fixes
  - Fix python error when File.io does not respond, + harmonize reporter logs

## [4.14.0] 2020-12-07

- Linters
  - Add Salesforce linter: sfdx-scanner

- Core architecture
  - Allow to call extra commands to build help content

## [4.13.0] 2020-12-05

- Major updates in online documentation generation
  - Reorganize TOC
  - Generate individual pages from README sections and update their internal links targets
  - Open external links in a new browser tab

- New configuration parameters
  - Allow disabling printing alpaca image to console using PRINT_ALPACA config parameter
  - Support list of additional excluded directory basenames via EXCLUDED_DIRECTORIES configuration parameter

- New reporters:
  - Email reporter, to send mega-linter reports by mail if smtp server is configured
  - File.io reporter, to access reports with a file.io hyperlink

- Fixes
  - Fix markdown comments generator when build on Windows
  - Fix terrascan unit test case
  - Run some actions/steps only when PR is from same repository
  - Add comments in markdown generated by build.py
  - Fix boolean variables not taken in account in .mega-linter.yml config file

- Performance
  - Change way to install linters in Dockerfile (replace FROM ... COPY) by package or sh installation, to reduce the docker build steps from 93 to 87
    - shellcheck
    - editorconfig-checker
    - dotenv-linter
    - golangci-lint
    - kubeval

## [4.12.0] 2020-11-29

- Performances
  - Update default workflow to get ride of has_updates action (replace by output `has_updated_files` from mega-linter github action)
  - Avoid duplicate runs in mega-linter.yml template and internal workflows, using [skip-duplicate-actions](https://github.com/fkirc/skip-duplicate-actions)
  - Give a proper name to each internal workflow
  - Fix issue about mkdirs failing

## [4.11.0] 2020-11-29

- Manage parallel processing of linters to improve performances

## [4.10.1] 2020-11-28

- Fallback to default behaviours instead of crashes when git not available

- mega-linter-runner
  - Allow to send env parameters to mega-linter-runner cli
  - Add examples in documentation
  - Publish mega-linter-runner beta version when pushing in master branch

## [4.10.0] 2020-11-23

- Add link to linters rules index in documentation
- Remove ANSI color codes from log files
- Add performances by linter in console log
- New option **SHOW_ELAPSED_TIME** , allowing the number of seconds elapsed by linter in reports

- NPM package **Mega-Linter runner**
  - runs Mega-Linter locally, using .mega-linter.yml configuration (requires docker installed on your computer)
  - test cases added in CI

## [4.9.0] 2020-11-23

- Core
  - Allow configuration to be defined in a `.mega-linter.yml` file

- Linters
  - Add Gherkin (Cucumber language) & gherkin-lint
  - Add RST linter : [rst-lint](https://github.com/twolfson/restructuredtext-lint)
  - Add RST linter : [rstcheck](https://github.com/myint/rstcheck)
  - Add RST formatter : [rstfmt](https://github.com/dzhu/rstfmt)
  - Activate formatting for BASH_SHFMT
  - Activate formatting for SNAKEMAKE_SNAKEFMT
  - JsCpd: remove copy-paste HTML folder when no abuse copy-paste has been found

- Logs
  - Store log files as artifacts during test cases
  - Add examples of success and failed linter logs in documentation
  - Remove `/tmp/lint` and `/github/workspace` from log files

- Documentation
  - Add list of supported IDE in each linter documentation
  - Generate GitHub card on linter doc when available
  - Store link preview info during build

## [4.8.0] 2020-11-17

- New reporter: [Updated sources](https://nvuillam.github.io/mega-linter/reporters/UpdatedSourcesReporter/)

## [4.7.1] 2020-11-16

- Activate auto-fix for Groovy

## [4.7.0] 2020-11-16

- Update markdown-link-check default config
- Add tip in documentation about .cspell.json generated by Mega-Linter
- Remove /tmp/lint from logs
- Improve summary table for linters in project mode (all project linted in one call, not one file by one file)
- Add Reporters in documentation, with screenshots
- New Mega-Linter variables to activate/deactivate/configure reporters

## [4.6.0] 2020-11-13

- Automatic build of documentation with mkdocs-material
- Automatic deployment to [https://nvuillam.github.io/mega-linter/](https://nvuillam.github.io/mega-linter/)
- Add [markdown-link-check](https://github.com/tcort/markdown-link-check)

## [4.5.0] 2020-11-11

- Add Visual Basic .NET language & dotnet-format
- Refactor removal of arguments for formatters (from custom class to Linter generic class)
- Perl: lint files with no extension containing Perl shebang
- Add automerge for PR issues from linter versions updates
- Fix ignored root files issue

## [4.4.0] 2020-11-05

- Add Python [iSort](https://pycqa.github.io/isort/)
- Quick fix "PR Comment" reporter (orange light emoji)
- Refresh fork

## [4.3.2] 2020-11-04

- Add spell checker **cspell**
- Add Github Action Workflow to automatically:
  - update linters dependencies
  - rebuild Mega-Linter documentation
  - create a PR with updates

- Apply fixes performed by linters:
  - User configuration (APPLY_FIXES vars)
  - Descriptors configuration: cli_lint_fix_arg_name set on linter in YML when it can format and/or auto-fix issues
  - Provide fixed files info in reports
  - Test cases for all fixable file types: sample_project_fixes
  - Generate README linters table with column "Fix"
  - Provide fix capability in linters docs
  - Update Workflows YMLs to create PR or commit to apply fixes

- Core Archi:
  - All linters now have a name different than descriptor_id
  - replace calls from os.path.exists to os.path.isfile and os.path.isdir

- Other:
  - fix Phive install
  - Upgrade linter versions & help

## [4.0.0] 2020-10-01

- Initial version
