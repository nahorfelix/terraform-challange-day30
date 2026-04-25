# Fill-in-the-Blank Practice (20 Questions)

Write answers from memory first, then verify.

1. The command to check formatting without changing files is `terraform ___`.
2. The lifecycle meta-argument that blocks destroy is `___ = true`.
3. Current workspace name is referenced with `terraform.___`.
4. S3 backend encryption is enabled with `___ = true`.
5. `for_each` accepts a map or a ___.
6. Remove from state without deleting infrastructure: `terraform state ___`.
7. `~> 2.0` allows versions `>= 2.0` and `< ___`.
8. A data block reads ___ infrastructure; a resource block manages ___ infrastructure.
9. `terraform init -upgrade` refreshes selections in the `___` file.
10. Apply saved plan `myplan.tfplan`: `terraform apply ___`.
11. The command to show resource addresses in state is `terraform state ___`.
12. To select workspace `prod`: `terraform workspace ___ prod`.
13. Preview destroy actions only: `terraform plan ___`.
14. The command that validates configuration syntax is `terraform ___`.
15. Force replacement during apply: `terraform apply -___=resource.type.name`.
16. The file commonly used for local variable values is `terraform.___`.
17. JSON output for automation from plan: `terraform show -json ___`.
18. Visual dependency output command: `terraform ___`.
19. Prevent specific drift tracking with lifecycle `ignore_changes = [___]`.
20. Command to initialize providers and modules: `terraform ___`.

## My Answers

1. fmt
2. prevent_destroy
3. workspace
4. encrypt
5. set
6. rm
7. 3.0
8. existing / managed
9. .terraform.lock.hcl
10. myplan.tfplan
11. list
12. select
13. -destroy
14. validate
15. replace
16. tfvars
17. myplan.tfplan
18. graph
19. attribute names
20. init

## Verification Notes

- Incorrect: 0
- Uncertain: 0
- Quick corrections: None required for first 10; reinforced Q11-Q20 syntax with quick CLI recap.
