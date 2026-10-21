# Karthik Kumar Reddy V

Senior SRE at Visa in Bengaluru. Previously Myntra and Airbus.

I work on Kubernetes, AWS, Terraform, and reliability.

[Site](https://karthikvkreddy.github.io) · [LinkedIn](https://www.linkedin.com/in/karthik-kumar-reddy-v) · [Hugging Face](https://huggingface.co/karthikreddyv)

---

## Work

### ChangeRadar

Paste a Kubernetes or Helm change. Rank lookalike incidents. Run it in the [browser](https://huggingface.co/spaces/karthikreddyv/changeradar) or as a local CLI.

```bash
helm diff upgrade checkout ./chart -f values-prod.yaml \
  | python -m changeradar score-diff
```

| What it is | What it is not |
| --- | --- |
| MiniLM embeddings + cosine ranking | An outage probability |
| `helm diff` / `kubectl diff` parser | A replacement for review |
| BYO incident JSONL (no training) | Fine-tuned on your org |
| Public seed: 1,513 labeled cases | Production incident dumps |

[Live demo](https://huggingface.co/spaces/karthikreddyv/changeradar) · [Dataset](https://huggingface.co/datasets/karthikreddyv/changeradar-incidents) · [Code](https://github.com/karthikvkreddy/changeradar)

---

## Stack I actually use

`Kubernetes` `Helm` `AWS EKS` `Terraform` `Python` `Prometheus` `Grafana` `CI/CD`

CKA · AWS Certified Developer Associate

---

## Elsewhere

- Hugging Face: [karthikreddyv](https://huggingface.co/karthikreddyv)
- Notes: [CKA](https://github.com/karthikvkreddy/Kubernetes_CKA) · [CKAD](https://github.com/karthikvkreddy/Kubernetes_CKAD)
