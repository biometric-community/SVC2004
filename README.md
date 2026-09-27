# SVC2004

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FSVC2004-181717?logo=github)](https://github.com/biometric-community/SVC2004)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](http://www.cse.ust.hk/svc2004/)

**SVC2004** — tbiom catalog packaging for `svc2004` (signature; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/SVC2004
- **Upstream source**: http://www.cse.ust.hk/svc2004/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `svc2004` |
| Category | `signature` |
| Access | `register` |
| Upstream homepage | http://www.cse.ust.hk/svc2004/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: First International Signature Verification Competition.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/SVC2004.git
cd SVC2004
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_svc2004.sh
```

Place licensed archives under `projects/datasets/svc2004/` (gitignored).

## Dataset structure

```text
SVC2004/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: http://www.cse.ust.hk/svc2004/
- Packaging: https://github.com/biometric-community/SVC2004/issues
