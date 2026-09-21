# Painel Conamore · Marketing e Vendas

Painel de acompanhamento publicado no GitHub Pages, atualizado todo dia com
dados ate o dia anterior.

- `dados.enc` guarda a pagina inteira cifrada (AES-GCM 256, chave derivada do
  PIN de acesso por PBKDF2-SHA256, 310000 iteracoes). Sem o PIN o conteudo e
  ilegivel.
- `index.html` contem so a tela de acesso; o painel e decifrado no navegador.
- Gerado e publicado automaticamente pelo gerador da Communitas.

Feito pela Communitas.
