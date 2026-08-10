# sistema-operacional

Páginas de venda do ecossistema de infoprodutos da EmpresAtiva Digital.

**Domínio:** operacao.empresativa.com.br
**Hospedagem sugerida:** Cloudflare Pages conectado a este repositório

## Estrutura

```
/                          hub — bifurcação entre os dois públicos
/operacao-no-controle/     ClickUp para agências · R$197 · Hotmart
/biblioteca/               Biblioteca do Sistema Operacional · R$997/ano
/assets/                   imagens
```

Ainda a migrar do GreatPages: `/lead-qualificado/` e `/operacao-trafego/`.

## Identidade visual

Todas as páginas compartilham o mesmo sistema, definido nas variáveis CSS de cada arquivo.

| | |
|---|---|
| Base | `#0B0D0B` |
| Verde-musgo | `#17351F` |
| Terracota | `#B5653A` |
| Off-white | `#F2EFE9` |
| Display e corpo | Poppins |
| Rótulos e dados | JetBrains Mono |

Estrutura narrativa de toda página de venda: abertura magnética → conflito → virada → prova → convite. Quebra de objeção dentro da virada; preço e garantia dentro do convite; FAQ ao final.

## Rastreamento

Dois públicos, dois conjuntos. O rastreamento é por página, não por domínio.

| Público | GTM | Pixel |
|---|---|---|
| Gestor de tráfego e agência | `GTM-K3FP6MWP` | `1570269951243411` |
| Dono de negócio local | `GTM-TBXGS2R` | `1586064638858561` |

Já instalados no hub e nas páginas de gestor. A página da mentoria, quando migrar, usa o conjunto do público de dono de negócio.

O token da API de Conversões **nunca** entra no código destas páginas — ele é server-side.

## Antes de publicar

- [ ] Preencher todos os `[CONFIRMAR: ...]` — aparecem destacados em terracota nas páginas
- [ ] Substituir os espaços reservados de mídia por imagens reais
- [ ] Link da comunidade no WhatsApp no hub (`data-comunidade`)
- [ ] Link do checkout da Biblioteca (`data-checkout`)
- [ ] Decidir workspace de demonstração ou borrão nas capturas de tela
