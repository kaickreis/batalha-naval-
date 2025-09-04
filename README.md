# 2.1) Clonar seu repositório vazio
# Troque SEU_USUARIO pelo seu nome de usuário do GitHub


git clone https://github.com/SEU_USUARIO/batalha-naval.git
cd batalha-naval


# 2.2) Criar arquivos básicos
# (você também pode copiar/colar o conteúdo desta página)


echo "# Batalha Naval\n" > README.md


# 2.3) (Opcional) criar e ativar venv
python -m venv .venv
# Windows:
# .venv\\Scripts\\activate
# Linux/macOS:
# source .venv/bin/activate


# 2.4) Criar .gitignore
printf "__pycache__/\n*.pyc\n.venv/\n" > .gitignore


# 2.5) Adicionar arquivos ao Git e enviar ao GitHub
git add .
git commit -m "Projeto Batalha Naval: versão inicial"
git push -u origin main
