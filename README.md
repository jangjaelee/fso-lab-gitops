# fso-lab-gitops

FSO 실측용 시험 레포입니다. 공개 예제 수준의 중립 매니페스트만 있고, 실측이 끝나면 삭제합니다.

| 경로 | 꼴 |
| --- | --- |
| `apps/plain` | 평 YAML, 다중 문서, 주석 |
| `apps/kustomize` | base + overlays/prod-a 덮어쓰기 |
| `apps/helm` | 로컬 차트 + values.yaml |
| `apps/helmrelease` | Flux HelmRelease inline values |
| `argocd` | Application 4개 |
| `flux` | GitRepository·Kustomization |
| `policy` | 조직 정책 레포 꼴(동결 창 1개) |
