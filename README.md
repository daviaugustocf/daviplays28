# Loja com Pix

Modelo de vitrine com carrinho e Pix copia e cola. Os produtos e preços são exemplos; não são ofertas reais.

## Configurar para sua loja

1. Abra `index.html` no GitHub e edite `LOJA`: preencha `chavePix`, `recebedor` e `cidade`. Use uma chave cadastrada no banco, o nome do recebedor e a cidade. Atenção: a chave aparece publicamente no código Pix. Prefira chave aleatória para não divulgar CPF ou telefone.
2. Troque os produtos em `PRODUTOS` e use os preços em centavos (exemplo: 2990 = R$ 29,90). Remova o aviso de demonstração só depois de configurar a loja.
3. Teste o código Pix no aplicativo do banco e confirme nome e valor antes de divulgar.
4. Para publicar, abra Settings > Pages e em Build and deployment selecione Deploy from a branch, branch `main`, pasta `/ (root)` e Save.

O Pix é estático e o pagamento não é verificado automaticamente. Confira os recebimentos no seu banco. O site não salva nem envia pedidos; o comprador pode copiar um resumo para compartilhar. Frete, estoque, entrega, vendas e atendimento devem ser combinados separadamente. Nunca compartilhe senha ou código de acesso do banco.
