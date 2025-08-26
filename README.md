mkdir scraping-GMN
cd scraping-GMN
# 3. Inicia o repositório Git
git init
# 4. Adiciona o README ao commit
git add README.md
# 5. Faz o primeiro commit
git commit -m "primeiro commit"
# 6. Renomeia a branch para 'main' (padrão atual)
git branch -M main
# 7. Conecta ao repositório remoto no GitHub
git remote add origin https://github.com/wbarradas/scraping-GMN.git
# 8. Envia o código para o GitHub
git push -u origin main
