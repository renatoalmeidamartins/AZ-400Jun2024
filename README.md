# AZ-400 - Course links

## Day 1 links

- [AZ-400 Learning Paths](https://aka.ms/CourseAZ-400)
- [GitHub repo with the labs](https://microsoftlearning.github.io/AZ400-DesigningandImplementingMicrosoftDevOpsSolutions/)
- [ESI, from where you can register for exams, join the class and prepare for exams](https://esi.microsoft.com)
- [Certification exams poster](https://aka.ms/TrainCertPoster)
- [Lab hosting environment](https://esi.learnondemand.net/)
- [10+ deploys per day at Flickr - Talk that sparked the DevOps movement](https://www.youtube.com/watch?v=LdOe18KhtT4)
- [DevOps handbook](https://www.amazon.com/DevOps-Handbook-Second-World-Class-Organizations/dp/B09L56CT6N)
- [The Phoenix project](https://www.amazon.com/The-Phoenix-Project-audiobook/dp/B00VATFAMI)
- [The unicorn project](https://www.amazon.com/dp/B0812C82T9?plink=NwPSkdwySXbn2OIL)
- [There's no place like production, interesting blog post from 2010 hinting into CI/CD](https://imwrightshardcode.com/2010/12/theres-no-place-like-production/)
- [12-factor app](https://12factor.net/)
- [Principles behind the Agile manifesto](https://agilemanifesto.org/principles.html)
- [Measure what matters - excellent book about defining OKRs](https://www.amazon.com/Measure-What-Matters-Google-Foundation/dp/0525536221/)
- [Git book](https://git-scm.com/book/en/v2)
- [Git flow branching strategy](https://nvie.com/posts/a-successful-git-branching-model/)
- [GitHub flow](https://docs.github.com/en/get-started/using-github/github-flow)
- [Conventional commits - a good spec for defining commit messages](https://www.conventionalcommits.org/)
- [Available git hooks](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks)
- Using Large File Storage
  - [On Git docs](https://git-lfs.com/)
  - [On Azure Repos/GitHub](https://learn.microsoft.com/en-us/azure/devops/repos/git/manage-large-files?view=azure-devops)
- [Scalar doc, now part of the git toolset](https://git-scm.com/docs/git)
- [Removing sensitive data from repos](https://docs.github.com/en/enterprise-cloud@latest/authentication/keeping-your-account-and-data-secure/removing-sensitive-data-from-a-repository)
- [Semantic versioning](https://semver.org/)
- [Swagger OpenAPI - excellent way to generate API docs](https://swagger.io/solutions/api-documentation/)
- [Terraform docs generation](https://github.com/terraform-docs/terraform-docs)

## Day 2 links
- [Azure devops with Jenkins](https://learn.microsoft.com/en-us/azure/devops/service-hooks/services/jenkins?view=azure-devops)
- [Azure Pieplines Task reference](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/?view=azure-pipelines)
- [Installing Azure DevOps Server](https://learn.microsoft.com/en-us/azure/devops/server/install/get-started?view=azure-devops-2022)
- [Software installed with each agent image](https://learn.microsoft.com/en-us/azure/devops/pipelines/agents/hosted?view=azure-devops&tabs=yaml)
- [Firewall ports/URLs needed to run a self-hosted agent](https://learn.microsoft.com/en-us/azure/devops/pipelines/agents/linux-agent?view=azure-devops#im-running-a-firewall-and-my-code-is-in-azure-repos-what-urls-does-the-agent-need-to-communicate-with)
- [Network requirements to have MS-hosted agents talking to on-prem resources - hin: VPN or ExpressRoute can't be used](https://learn.microsoft.com/en-us/azure/devops/pipelines/agents/hosted?view=azure-devops&tabs=yaml#networking)
- [Pipeline agent details](https://learn.microsoft.com/en-us/azure/devops/pipelines/agents/agents?view=azure-devops&tabs=yaml%2Cbrowser)
- [GitHub Actions repos](https://github.com/actions)
- [Azure Pipeline Template reference](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/templates?view=azure-devops&pivots=templates-includes)
- [GitHub Actions syntax](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions)
- [GitHub default environment variables](https://docs.github.com/en/actions/learn-github-actions/variables#default-environment-variables)
-[Creating GitHub actions](https://docs.github.com/en/actions/creating-actions)
- [Docker multi-stage build](https://docs.docker.com/build/building/multi-stage/)
- [Azure container instances - container groups](https://learn.microsoft.com/en-us/azure/container-instances/container-instances-container-groups)
- [Compare Azure container hosting options](https://learn.microsoft.com/en-us/azure/container-apps/compare-options)
- [Azure Container apps](https://learn.microsoft.com/en-us/azure/container-apps/overview)
- [Azure DevOps service status](https://status.dev.azure.com/_history)
- [GitOps with Flux](https://learn.microsoft.com/en-us/azure/azure-arc/kubernetes/tutorial-gitops-flux2-ci-cd)
  - [Argocd, a good framweork for GitOps](https://argo-cd.readthedocs.io/en/stable/)
  - [Flux, another good GitOps tool](https://github.com/fluxcd/flux2)
- [Generic job definitions](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/phases?view=azure-devops&tabs=yaml#types-of-jobs)
  [Deployment jobs](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/phases?view=azure-devops&tabs=yaml#types-of-jobs)
- [Auditing Azure DevOps (in preview)](https://learn.microsoft.com/en-us/azure/devops/organizations/audit/azure-devops-auditing?view=azure-devops&tabs=preview-page)
- [Collecting an Audit stream](https://learn.microsoft.com/en-us/azure/devops/organizations/audit/auditing-streaming?view=azure-devops)

## Day 3 links
- Using OIDC to allow GitHub actions to access Azure without secrets or certificates
  - [Azure doc](https://learn.microsoft.com/en-us/azure/developer/github/connect-from-azure?tabs=azure-portal%2Clinux)
  - [GitHub doc](https://docs.github.com/en/actions/deployment/security-hardening-your-deployments/configuring-openid-connect-in-azure)
  - [Default variables in classic pipelines](https://learn.microsoft.com/en-us/azure/devops/pipelines/release/variables?view=azure-devops&tabs=batch)
  - [Predefined variables for YAML pipelines](https://learn.microsoft.com/en-us/azure/devops/pipelines/build/variables?view=azure-devops&tabs=yaml)
  - [Martin Fowler's book "Patterns of Enterprise Application Architecture"](https://martinfowler.com/books/eaa.html)
  - Strangler Fig pattern, a good way to break a monolyth into microservices
    - [Martin Fowler's original definition](https://martinfowler.com/bliki/StranglerFigApplication.html)
    - [Discussion in the Azure Architecture Center](https://learn.microsoft.com/en-us/azure/architecture/patterns/strangler-fig)
  - SSO in GitHub:
    - [With SAML](https://docs.github.com/en/enterprise-cloud@latest/admin/identity-and-access-management/using-saml-for-enterprise-iam/configuring-saml-single-sign-on-for-your-enterprise)
    - [With SCIM](https://docs.github.com/en/enterprise-cloud@latest/organizations/managing-saml-single-sign-on-for-your-organization/about-scim-for-organizations)
  - Permissions, groups and roles in Azure DevOps[](https://learn.microsoft.com/en-us/azure/devops/organizations/security/about-permissions?view=azure-devops&tabs=preview-page)
    - 
  - 
