# Day 30 Final Submission

## Practice Exam 5 Score
Exam 5 score: **55/57 (96%)**

Exam 1 was **47/57 (82%)**, so there is clear improvement and stability. Even when question wording became tricky, I stayed well above the passing threshold, which confirms my preparation is strong.

## Fill-in-the-Blank Results
| Q | My Answer | Correct Answer |
|---|-----------|----------------|
| 1 | fmt | fmt |
| 2 | prevent_destroy | prevent_destroy |
| 3 | workspace | workspace |
| 4 | encrypt | encrypt |
| 5 | set | set |
| 6 | rm | rm |
| 7 | 3.0 | 3.0 |
| 8 | existing / managed | existing / managed |
| 9 | .terraform.lock.hcl | .terraform.lock.hcl |
| 10 | myplan.tfplan | myplan.tfplan |

All 10 were correct. This confirms command precision and syntax recall are exam-ready.

## Final Readiness Check
1. `terraform init` creates/updates `.terraform` and downloads required providers/modules.  
2. `terraform.tfstate` is current state; `terraform.tfstate.backup` is previous backup copy.  
3. Never commit state because it may contain secrets and causes merge conflict risk.  
4. `depends_on` creates explicit ordering when dependencies are not automatically inferred.  
5. Variables are caller inputs; locals are internal computed values.  
6. If state changed before apply, Terraform relies on lock/refresh checks and prevents unsafe concurrent writes.  
7. `terraform graph` outputs a DOT dependency graph for relationship debugging.  
8. Terraform Registry hosts providers, modules, and policy libraries.  
9. Terraform Cloud is SaaS; Terraform Enterprise is self-hosted.  
10. `configuration_aliases` allows modules to accept aliased provider configs from parent modules.

Confidence: **Ready**. I can answer all ten without notes.

## Five-Exam Score Summary
| Exam | Score | % |
|------|-------|---|
| Exam 1 | 47/57 | 82% |
| Exam 2 | 51/57 | 89% |
| Exam 3 | 54/57 | 95% |
| Exam 4 | 55/57 | 96% |
| Exam 5 | 55/57 | 96% |

Average: **52/57 (92%)**  
Trend: Consistently above 70%, peaking at 96%

## 30-Day Reflection
This challenge changed how I think about infrastructure. Before, cloud setup felt manual and fragile. Now I treat infrastructure as code that is versioned, reviewed, validated, and safely updated. I trust plans, state discipline, and repeatable workflows.

I am most proud of getting through the hardest troubleshooting days instead of skipping them. Solving IAM permission blockers, backend/state issues, and multi-region module wiring taught me real engineering patience and confidence.

What comes next is clear: certification exam first, then applying this workflow in real environments using reusable modules, remote state best practices, and CI validation on every infrastructure change.

## Exam Logistics Confirmation
My exam is not booked yet. Plan is to book for next week after one final light review session.

- Online proctored exam
- Morning slot
- Clear desk, tested webcam, government ID ready
- Quick warm-up review before exam start

## Closing Message to the Community
To future participants: stay consistent. You will hit confusing errors and feel stuck, but daily hands-on practice works. Read errors carefully, keep your state safe, and do not skip fundamentals.

Small progress every day adds up. Trust the process, keep shipping, and finish strong.
