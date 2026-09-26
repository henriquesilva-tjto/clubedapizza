# Sistema de Pedidos — Pizzaria

Primeira versão funcional em um único arquivo (`index.html`).

## Recursos
- Pedido numerado automaticamente por dia.
- Nome do cliente e observação.
- Pizzas P, M e G.
- P aceita 1 sabor; M e G aceitam até 2 sabores.
- Bebidas com quantidade.
- Cálculo automático do total.
- Histórico local dos últimos pedidos.
- Ticket formatado para papel de 58 mm.
- Impressão pelo diálogo do navegador.

## Próxima etapa: Bluetooth JP58H
A JP58H usa Bluetooth + ESC/POS. Em Android, o fabricante/comercializador informa que a impressão móvel requer um aplicativo de impressão compatível e pareamento Bluetooth dentro desse aplicativo. Portanto, a integração direta com o Chrome deve ser tratada como uma etapa separada.

Uma opção de teste é compartilhar um TXT/PDF do ticket para um aplicativo Android compatível com Bluetooth/ESC-POS. Outra opção é desenvolver um pequeno aplicativo Android ponte (WebView + Bluetooth SPP/ESC-POS), deixando o site como interface do sistema.

## Publicar no GitHub Pages
1. Crie um repositório, por exemplo `pizzaria-pedidos`.
2. Envie `index.html`.
3. Ative Settings → Pages → Deploy from branch → `main` / root.
4. O sistema abrirá como um site e poderá ser adicionado à tela inicial do Android.
