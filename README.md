# 🟢 Bora Apps

**Ferramentas simples para o dia a dia brasileiro.**  
Sem cadastro. Sem app para baixar. Abre e usa.

---

## O que é isso?

Uma coleção de calculadoras e utilitários feitos para resolver aquelas situações cotidianas que todo mundo já passou: *"quanto eu cobro de carona?"*, *"como a gente divide a conta agora?"*, *"que horas eu preciso dormir hoje?"*.

Cada ferramenta é uma página HTML estática, funciona 100% no navegador e não envia nenhum dado para servidor nenhum.

Sim, isso é um projeto hobby. Feito nas horas vagas, com carinho, por alguém que se cansou de fazer conta no papel de guardanapo.

---

## Ferramentas disponíveis

### 💰 Finanças e divisão
| App | Descrição | Status |
|-----|-----------|--------|
| [[Bora Junto]] | Calcula o valor justo de carona com base em km, consumo e depreciação do carro | ✅ Disponível |
| [[Bora Lanchar]] | Racha a conta do bar separando quem bebeu álcool de quem não bebeu | ✅ Disponível |
| [[Bora CLT]] | Calculadora de direitos trabalhistas — férias, 13º, rescisão e mais | ✅ Disponível |
| [[Bora Investir]] | Simulador de investimentos com comparativo entre renda fixa e variável | ✅ Disponível |
| [[Bora Financiar]] | Simula financiamento de veículo com juros, entrada e parcelas | ✅ Disponível |
| [[Bora Abastecer]] | Descobre se vale mais abastecer com etanol ou gasolina | ✅ Disponível |

### 🛒 Cotidiano
| App | Descrição | Status |
|-----|-----------|--------|
| [[Bora no Mercado]] | Lista de compras com campo de preço e comparação automática com a última compra de cada item | ✅ Disponível |
| [[Bora Churrasquear]] | Calculadora de churrasco — quantidade por pessoa, carvão e gelo | ✅ Disponível |
| [[Bora Festejar]] | Planejador de festa com estimativa de custos e lista de convidados | ✅ Disponível |

### 🎮 Diversão e jogos
| App | Descrição | Status |
|-----|-----------|--------|
| [[Bora Placar]] | Placar digital para qualquer jogo ou campeonato | ✅ Disponível |
| [[Bora Sortear]] | Sorteador de nomes, números, times e ordem — para pelada, amigo secreto e mais | ✅ Disponível |

### 🎭 Entretenimento
| App | Descrição | Status |
|-----|-----------|--------|
| [[Bora Assistir]] | Monte sua lista de filmes via OMDB, marque os assistidos e sorteie o próximo — perfeito para clubes do filme | ✅ Disponível |
| [[Bora Afinar]] | Afinador online para violão, guitarra, baixo e ukulele — usa o microfone do celular em tempo real | ✅ Disponível |

### 🌿 Saúde e bem-estar
| App | Descrição | Status |
|-----|-----------|--------|
| [[Bora Emagrecer]] | Calculadora de IMC, TMB e planejamento de deficit calórico | ✅ Disponível |
| [[Bora Dormir]] | Calcula os melhores horários para acordar com base nos ciclos de sono recomendados | ✅ Disponível |
| [[Bora Engravidar]] | Calculadora de período fértil e acompanhamento do ciclo | ✅ Disponível |
| [[Bora Mamãe]] | Acompanhamento semanal da gravidez com dicas e marcos do bebê | ✅ Disponível |
| 💧 **Bora Hidratar** | Lembrete e meta diária de água personalizada por peso, idade e nível de atividade | 🔜 Em ajuste |
| 💊 **Bora Remediar** | Controle de horários de medicamentos com alertas configuráveis | 🔜 Em ajuste |

---

## Como funciona tecnicamente

Nada muito sofisticado — e isso é intencional.

- HTML + CSS + JavaScript puro, sem frameworks
- Zero dependências externas (exceto Google Fonts)
- Hospedado via GitHub Pages
- Todo cálculo acontece no navegador do usuário

Se você sabe abrir um arquivo `.html` no VS Code, consegue entender e modificar qualquer coisa aqui.

---

## Estrutura do projeto

```
bora-apps/
├── index.html                # Página inicial
├── faq.html                  # FAQ com schema JSON-LD para SEO
├── sobre.html                # Sobre o projeto
├── privacidade.html          # Política de privacidade
├── manifest.json             # PWA manifest
├── icon.png                  # Ícone do app
│
├── bora-junto.html
├── bora-lanchar.html
├── bora-clt.html
├── bora-investir.html
├── bora-financiar.html
├── bora-abastecer.html
├── bora-no-mercado.html
├── bora-churrasquear.html
├── bora-festejar.html
├── bora-placar.html
├── bora-sortear.html
├── bora-emagrecer.html
├── bora-dormir.html
├── bora-engravidar.html
├── bora-mamae.html
├── bora-assistir.html
└── bora-afinar.html
```

---

## Roadmap

- [ ] Ajustes Bora Afinar: unificar Violão/Guitarra, suavizar medidor
- [ ] Caixa de sugestões (usuários → email)
- [ ] Expandir seção Automóvel: [[Bora Alugar vs Comprar]], [[Bora FIPE]], [[Bora Combustão vs Elétrico]]
- [ ] [[Bora Comprar]] — comparador de preços

---

## Contribuindo

Encontrou um bug? Tem ideia de ferramenta nova? Abre uma issue, manda um PR ou só deixa uma estrela se achou útil. Tudo ajuda.

Não tem processo formal de contribuição porque isso é um hobby, não uma startup. Bom senso é o suficiente.

---

## Privacidade

Nenhum dado digitado nos apps é coletado ou armazenado. Tudo fica no seu dispositivo.  
O site usa Google AdSense e Google Analytics — veja a política de privacidade para detalhes.

---

## Licença

MIT — faz o que quiser, só não tira os créditos.

---

*Feito com ☕ em Jaraguá do Sul, SC.*
