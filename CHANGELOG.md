## **1.2.8**&emsp;<sub><sup>2025-11-26 (15339fc45529f0ad22ae339e5cad460b4451ffed...15339fc45529f0ad22ae339e5cad460b4451ffed)</sup></sub>

*no relevant changes*
<br>

## **1.2.6**&emsp;<sub><sup>2025-11-26 (0066df37badddc6889e916622cfeab333a8d6667...133d13411a4f2770e36bd691c2057d2fd4c97847)</sup></sub>

*no relevant changes*
<br>

## **1.2.6**&emsp;<sub><sup>2025-11-26 (0066df37badddc6889e916622cfeab333a8d6667...b48e2745d55fd956c89482fb15ffd0727ed6ab1e)</sup></sub>

*no relevant changes*
<br>

## **1.2.6**&emsp;<sub><sup>2025-11-25 (0066df37badddc6889e916622cfeab333a8d6667...84035b97aac4f90c9edcfd2e5d8eeee7b29a5fa6)</sup></sub>

*no relevant changes*
<br>

## **1.2.7**&emsp;<sub><sup>2025-11-25 (f903c8f0f8156ebfeb82a7c1638e5d94d085e47b...b9d3de98d3c657b77309e0e5ba61ead0d7b2e61e)</sup></sub>

### Features

- add retry mechanism for OneAgent installer download (79658309a21dff5f54d3758131643485a0623ac6)
- Remove unintended config feature from the collection (5cb5d4e8f19b78ac717485b0a708e6d1b9b2bb56)
- Add check for latest OneAgent version before download (3c7670931c7d274f365e16f1ee837acaea324009)

### Bug Fixes

- fix broken conditionals \(\#105\) (7cd6ee37f063e34740678455a8fcadee9cf16f54)

<br>

## **1.2.6**&emsp;<sub><sup>2025-11-25 (f903c8f0f8156ebfeb82a7c1638e5d94d085e47b...d7cc2180ef00c8caf5a50bc6bb51a9a8be5ca9ad)</sup></sub>

### Features

- add retry mechanism for OneAgent installer download (79658309a21dff5f54d3758131643485a0623ac6)
- Remove unintended config feature from the collection (5cb5d4e8f19b78ac717485b0a708e6d1b9b2bb56)
- Add check for latest OneAgent version before download (3c7670931c7d274f365e16f1ee837acaea324009)

### Bug Fixes

- fix broken conditionals \(\#105\) (7cd6ee37f063e34740678455a8fcadee9cf16f54)

<br>

## **1.2.5**&emsp;<sub><sup>2025-11-21 (f903c8f0f8156ebfeb82a7c1638e5d94d085e47b...ab81691af95dae02a1f7cfbf644404b40edcaac6)</sup></sub>

### Features

- add retry mechanism for OneAgent installer download (79658309a21dff5f54d3758131643485a0623ac6)
- Remove unintended config feature from the collection (5cb5d4e8f19b78ac717485b0a708e6d1b9b2bb56)
- Add check for latest OneAgent version before download (3c7670931c7d274f365e16f1ee837acaea324009)

### Bug Fixes

- fix broken conditionals \(\#105\) (7cd6ee37f063e34740678455a8fcadee9cf16f54)

<br>

## [1.2.4] - 2025-04-30
- Added parameter `oneagent_no_log` controlling Ansible no_log attribute

## [1.2.3] - 2025-02-03
- Fixed issue with skipping CA certificate transfer task

## [1.2.2] - 2025-10-1
- Fixed linters issues

## [1.2.1] - 2024-12-19
- Fixed problem with installer signature verification on AIX
- Added LICENSE file

## [1.2.0] - 2024-11-29

- Added parameter `--restart-service` parameter, once OneAgent configuration is performed
- Fixed problem with `Invalid version string` during collection install
- Added parameter `oneagent_verify_signature` controlling signature verification step
- Removed `oneagent_validate_certs` parameter
- Fixed problem with `dt-root.cert.pem` not being copied to the target host
- Added ability for downloading installer's certificate if the certificate is not embedded in the collection

## [1.1.0] - 2021-10-06

- Fixed malformation of `--restart-service` parameter, passed to `oneagentctl`.
- Fixed problem with installation for higher versions of Ansible.
- Improved `oneagentctl` configuration mechanism.

## [1.0.0] - 2021-08-13

- Added capability of creating download directory structure during deployment.
- Added `oneagent_validate_certs` parameter.
- Added capability of cleaning up downloaded artifacts in case of deployment's failure.

## [0.4.0] - 2021-06-25

- Removed `oneagent_remove_signature` parameter.
- Added ability to configure installation using `oneagentctl`.
- Removed the need to provide the required parameters in case of uninstallation.
- Added node restart option.

## [0.3.0] - 2021-02-12

- Fixed role's idempotence.

## [0.2.1] - 2020-12-28

- Fixed minor problems with example playbooks and inventory files.

## [0.2.0] - 2020-11-18

- Added new parameter `oneagent_platform_install_args` allowing to specify platform-specific installer arguments.
- Changed `oneagent_local_installer` parameter to pass only single path to local installer.

## [0.1.0] - 2020-09-25

- Initial [Preview](https://www.dynatrace.com/support/help/shortlink/preview-and-early-adopter-releases) release.
