# Native K8s application

**Overall Goal**: Proof of Concept. Develop a blueprint for the app architecture that runs on top of CRDs (and maybe other resources) and document do’s and don’ts along the way.

Stages:

- [x] 1. Create a CRD of a product, backend or API spec. Consume CR data from another pod. (with an image that at least has curl)  
    - Done in [PR #3](https://github.com/3scale/k8sapp-initiative/pull/3)
- [ ] 2. Instead of using an image that has curl, make it have a server and present a page that consumes the CR
    - Partially done in [PR #5](https://github.com/3scale/k8sapp-initiative/pull/5)
    - Related issues [#7](https://github.com/3scale/k8sapp-initiative/issues/7) and [#8](https://github.com/3scale/k8sapp-initiative/issues/8)
- [ ] 3. Instead of this simple page, use Portafly
    - Related issue [#9](https://github.com/3scale/k8sapp-initiative/issues/9) 
- [ ] [Optional] 4. Authorize the calls. We may use Keycloak. We might also explore using only OpenShift RBAC and users.

## Instructions

**Step 1** (create CR/CRD, consume from other pod...) follow the instructions in [PR description](https://github.com/3scale/k8sapp-initiative/pull/3)


