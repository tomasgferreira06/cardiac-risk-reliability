# cardiac-risk-reliability
Assessing the reliability of individual cardiac risk predictions through density-based and local-fit methods.

Atividade Prática 3 da unidade curricular Responsible AI.

## Ambiente de desenvolvimento

Requisitos: [uv](https://docs.astral.sh/uv/getting-started/installation/) e Python 3.12
(o uv pode instalar o Python automaticamente).

Na raiz do repositório:

```sh
uv sync --locked
uv run jupyter lab
```

O `uv sync` cria `.venv` e instala as dependências científicas e de desenvolvimento
nas versões de `uv.lock`. Não é necessário ativar o ambiente manualmente.

No VS Code, instala as extensões Python e Jupyter da Microsoft, abre
`cardiac_risk_reliability.ipynb` e escolhe **Select Kernel → Python Environments**,
selecionando `.venv` (Python 3.12). No Windows, o interpretador encontra-se em
`.venv/Scripts/python.exe`; em Linux/macOS, em `.venv/bin/python`.
No JupyterLab iniciado acima, seleciona o kernel **Python 3 (ipykernel)**.

O ficheiro `cardiac_risk_reliability.ipynb` está atualmente vazio (0 bytes);
é necessário recuperar o notebook original válido antes de o abrir/executar.

Mantém `pyproject.toml`, `uv.lock` e `.python-version` no controlo de versões.
O dataset local `reliabilityRisk2.csv` deve permanecer na raiz e está excluído
do Git, tal como o ambiente, checkpoints, ficheiros temporários e `.env`.
