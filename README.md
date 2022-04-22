# declarative-argocd

![preview.png](preview.png)

ArgoCD를 어떻게 선언적으로 관리해나갈수 있을지에 대한 블로그 포스트 관련 코드입니다.

## getting-started

`ArgoCD`를 `helm`으로 install해보고 ArgoCD Helm Chart의 `additionalApplications` 기능과 `App of App` 패턴을 통해 선언적으로 Application들을 관리합니다.

**관련 포스트: https://umi0410.github.io/blog/devops/declarative-argocd-helm-app-of-app**

## configuring-rbac

rbac 설정을 통해 유저별 권한을 제어합니다. 이런 기능을 선언적으로 설정합니다.