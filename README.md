# Projetos de Consultoria Tech

Pagina de acesso restrito para material de trabalho em andamento.

O conteudo nao esta neste repositorio em texto claro. O arquivo `v.dat` e um
pacote cifrado em AES-256-GCM; a chave do conteudo e embrulhada por usuario com
uma chave derivada da senha via PBKDF2-SHA256 (250.000 iteracoes). Sem a senha
correta o pacote nao e legivel, nem para quem clonar o repositorio.

- `index.html` - portao de acesso e rotina de decifracao no navegador
- `v.dat` - pacote cifrado
- `vercel.json` - cabecalhos (sem indexacao por buscadores)

Gerado por um script de build local. Para publicar uma nova versao, basta
substituir os dois arquivos e dar push: a Vercel republica sozinha.
