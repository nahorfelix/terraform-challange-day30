# Final Readiness Check (No Notes)

Answer each question cold.

1. What does `terraform init` do to `.terraform/`?
2. Difference between `terraform.tfstate` and `terraform.tfstate.backup`?
3. Why should `terraform.tfstate` never be committed?
4. What does `depends_on` do and when should it be used?
5. Difference between `variable` blocks and `locals`?
6. What happens if state changed after your plan and before apply?
7. What does `terraform graph` output and why use it?
8. What is Terraform Registry and what three things are published there?
9. Difference between Terraform Cloud and Terraform Enterprise?
10. What problem does module `configuration_aliases` solve?

## My Answers

1. `terraform init` prepares `.terraform/` by downloading required providers and modules.
2. `terraform.tfstate` is the active state file; `terraform.tfstate.backup` is the previous snapshot.
3. State should not be committed because it can contain secrets and causes dangerous merge conflicts.
4. `depends_on` adds explicit ordering when Terraform cannot infer dependencies from references.
5. Variables are external inputs; locals are internal computed values used within the configuration.
6. If state changed after plan, apply re-checks current state and locking prevents unsafe concurrent changes.
7. `terraform graph` outputs a DOT dependency graph used to visualize resource relationships.
8. Terraform Registry publishes providers, modules, and policy libraries.
9. Terraform Cloud is HashiCorp SaaS; Terraform Enterprise is self-hosted.
10. `configuration_aliases` allows modules to accept multiple aliased provider configurations from callers.

## Confidence Check

- Confident answers: 10/10
- Needs quick review: None
