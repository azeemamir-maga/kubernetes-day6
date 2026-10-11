# Kubernetes Day 6 Progress

## Namespaces
- Created dev and prod namespaces.
- Deployed NGINX into both namespaces.
- Used the same Deployment name in separate namespaces.

## Deployments
- Dev: 2 replicas.
- Prod: 2 replicas.
- All four application Pods reached Running and Ready.

## Labels and Selectors
- Used app, env, and tier labels.
- Filtered Pods using equality-based selectors.
- Practiced a set-based selector.

## Next Practice
- Change the default namespace.
- Add and remove a Pod label.
- Verify all changes.

Author: Azeem Aamir
