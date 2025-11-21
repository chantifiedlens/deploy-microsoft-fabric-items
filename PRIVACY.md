# Privacy Policy for Deploy Microsoft Fabric items GitHub Action

This extension is designed for use within GitHub and does not collect or transmit user personal data (PII) as part of its normal operation. This policy describes what (if anything) the extension collects, how it is used, and how to contact the maintainers. Plus, the GitHub repository for this is publicly viewable to show transparency.

## Data the extension collects

- No personal data is stored or transmitted by this extension.

## Telemetry and diagnostics

- This Action does not collect diagnostic telemetry by default. If you add any diagnostic logging or telemetry, it will be made clear in the repository and will include an opt-out instruction. To the best of our knowledge the same is said for the Python libraries we work with.

## Third-party services

- The composite GitHub Action may use PyPI to install `fabric-cicd` and other dependencies during the task. The policy for those services is governed by their respective privacy policies.
- Ensure that your build agents are allowed to access those resources and that your network policies are configured appropriately.

## How we handle credentials

- Do NOT store secrets directly in source control or task inputs. 
- The extension leverages environment variables and secretss; it does not store client secrets or tenant IDs outside the run context.

## Data retention

- The composite GitHub Action does not store data beyond the ephemeral run on the runner.


## Contact & updating this policy

- This privacy policy may be updated; the latest version will be available at the repository link in the extension metadata.

