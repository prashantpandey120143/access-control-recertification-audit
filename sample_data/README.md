# Sample data (100% synthetic)
Fictitious users at `example.com`. File names must stay exactly as they are; the workflow finds them by name.

| File | Columns | Content |
|---|---|---|
| `UserAccess.csv` | `User, Role` | Current role assignments (includes 2 deliberately messy rows: an exact duplicate and a mixed-case/whitespace variant) |
| `HRTermination.csv` | `User, Status` | `Active` or `Terminated` for 30 users |
| `RBACMatrix.csv` | `Role, Permission` | 9 approved roles and their permissions |

Planted exceptions: 5 terminated users with access, 4 roles missing from the RBAC matrix, 4 SoD conflicts → **13 violations**.
