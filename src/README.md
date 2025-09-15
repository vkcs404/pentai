## Estrutura do Projeto PentAi

Aqui está o “código-mente” do nosso projeto **PentAi**:

```
App/                        # Diretório principal da aplicação
│
├── App.py                  # Arquivo principal ("cérebro": rotas, funções, organização)
│
├── Work/                   # Módulos auxiliares (verificações, "trabalhadores")
│   └── ...                 # Ex.: scan.py, report.py
│
├── Static/                 # Arquivos estáticos
│   ├── css/
│   ├── js/
│   └── img/
│
├── Templates/              # Páginas HTML (renderizadas pelo Flask)
│   └── ...                 # Ex.: index.html, result.html
│
└── requirements.txt        # Dependências do projeto
                            # Instale com: pip install -r requirements.txt
```
