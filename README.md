# Kubernetes RBAC

Hands-on Kubernetes RBAC practice covering Role, RoleBinding, and AWS authentication configuration.

## Topics
- Role
- RoleBinding
- Namespace-scoped permissions
- AWS/Kubernetes authentication

## Files
- `01-role.yaml`
- `02-rolebinding.yaml`
- `03-aws-auth.yaml`

## Apply
```bash
kubectl apply -f 01-role.yaml
kubectl apply -f 02-rolebinding.yaml
kubectl apply -f 03-aws-auth.yaml
```

## Learning Outcome
Demonstrates how Kubernetes permissions are defined and assigned using RBAC.
