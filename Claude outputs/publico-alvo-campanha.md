# Público-alvo — Campanha Personal Studio
**Uso:** insumo para configurar segmentação/públicos no Meta Ads. Compilado a partir do histórico do projeto (chats anteriores + handoff).

---

## 1. Contexto geral

Dois negócios, dois públicos diferentes, duas campanhas separadas:

| | Presencial | Consultoria (Online + Presencial) |
|---|---|---|
| Onde | Studio físico em **Paranavaí-PR** | Online = nacional/remoto; Presencial (avaliação) = Paranavaí |
| LP | `presencial.html` | `consultoria.html` |
| Pixel | `1095801370061606` | `1103657205336398` |
| Orçamento | R$10/dia (R$300/mês) | R$10/dia (R$300/mês) |

Milton é o rosto das duas marcas. Studio dá a credibilidade institucional; a consultoria é conduzida pessoalmente por ele.

---

## 2. Presencial (studio Paranavaí)

**Perfil:** público local, mais velho, moradores de Paranavaí-PR e região.

**Segmentação geográfica:** raio pequeno em torno do studio (R. Paraíba, 1435, Centro) — tráfego local, não nacional.

**Capacidade real (limita o volume que a campanha pode gerar):**
- Máx. 4 alunos por horário
- Turmas: manhã 7h/8h/12h; tarde/noite 16h30/17h30/18h30
- Ocupação atual: 61 aulas/semana de 90 possíveis
- Meta conservadora da campanha: **1 aluno presencial novo/mês**

**Dor/gancho mais forte:** sensação de estagnação em quem já treina — validado pelo histórico real de clientes do Milton, não pesquisa de mercado genérica.

**Outros ângulos de criativo já roteirizados:**
- Pessoas "perdidas" na academia, sem saber o que fazer
- Frustração de horário de pico (ângulo de humor)
- Mulheres 40-50 anos que se sentem deslocadas em academia tradicional
- Treino adaptado para mulher (séries/abordagem diferente do padrão masculino)

**Preço de referência:** pacote 2x/semana R$379/mês, pacote 3x/semana R$569/mês (disclaimer: preço "a partir de", outras frequências sob consulta).

---

## 3. Consultoria (Online + Presencial)

**Perfil geral:** mais jovem que o público presencial, busca combo **hipertrofia + emagrecimento** ("ganhar massa e derreter gordura" / "trocar gordura por músculo" — evitar o termo técnico "definição").

**Segmentação geográfica:** online = sem restrição geográfica relevante (ajustar depois conforme performance); Paranavaí e Fortaleza-CE são as duas praças que Milton acompanha de perto (Fortaleza = mudança em andamento, bairros Meireles/Aldeota, público premium).

**Nicho mais forte (confirmado pelo histórico de vendas do Milton, não achismo):**
> Quem já treina mas sente que estagnou — vale ser o ângulo principal do criativo/copy.

**Segmentos secundários já roteirizados (testar como públicos/criativos adicionais):**
1. **60+ com sarcopenia/osteopenia** — gancho de conversão indireta: filho(a) decide o treino do pai/mãe. Ângulo de cuidado familiar, não estético.
2. **Usuários de canetas emagrecedoras (GLP-1)** — foco em preservar/ganhar massa magra durante o uso. Compliance: tom consultivo, sem alarmismo (Meta rejeita copy alarmista de saúde).
3. Mulheres 40-50 que não se sentem bem-vindas em academia tradicional (mesmo ângulo do presencial, mas versão online).

**Oferta / esteira (contexto para a copy do anúncio, não pra segmentação):**
- Consultoria 100% online: R$94/mês (confirmado)
- Consultoria presencial (avaliação no studio): R$142/mês
- Treinamento presencial: a partir de R$380
- Protocolo de 90 dias (ticket baixo, isca) — preço/formato ainda em definição

**Meta conservadora da campanha:** 3 alunos de consultoria novos/mês.

---

## 4. Regras de segmentação e integridade de funil

- **Pixels separados por página/negócio** — não misturar sinais de otimização entre presencial e consultoria.
- WhatsApp é reservado só para lead quente vindo de campanha paga (via LP → Quiz → WhatsApp). Tráfego orgânico/institucional não usa esse caminho.
- Compliance: qualquer copy que encoste em saúde (GLP-1, sarcopenia, risco de cirurgia estética) precisa de tom consultivo/suavizado — mensagem central mantida, linguagem alarmista removida, para não ser reprovado no Meta Ads.

---

## 5. Criativos já disponíveis (prontos para subir)

| Pasta | Vídeo | Ângulo | Tamanho |
|---|---|---|---|
| Presencial | 01 — "Você já entrou numa academia e olhou em volta" | Perdido na academia | 476 MB |
| Consultoria | 02 — "Se você se sente perdida na academia" | Mesma dor, versão consultoria | 424 MB |
| Consultoria | 03 — "Se você já teve vontade de meter o louco na academia cheia" | Frustração/humor | 444 MB |
| Consultoria | 04 — "Esquece treinar glúteo segunda, posterior na terça" | Método/organização de treino | 241 MB |

Local: `D:\OneDrive\Perosnal Studio\Gravações Campanha\Finalizados` (com `.srt` pareado).

Também existem na conta de anúncios (`1141609870618198`) dois criativos antigos reaproveitáveis para o presencial: "2024.04.09 Institucional [Vídeo]" e "Ad 3".

---

## 6. Estrutura de conta confirmada

- Conta de anúncios oficial: **`1141609870618198`** (dentro do Business Manager "Personal Studio - BM2", `2110540215653964`)
- Forma de pagamento: MasterCard •••• 0870
- Página vinculada: "Milton Gasparotto Jr - Personal Trainer - Paranavaí"
- WhatsApp de destino (ambas campanhas): `https://wa.me/5544991723451`

---

## 7. O que falta decidir na configuração das campanhas

- Definir estrutura no Ads Manager: 1 campanha por negócio (Presencial / Consultoria), quantos conjuntos de anúncios por público/ângulo dentro de cada uma
- Testar públicos por segmento (broad vs. interesses vs. segmentos específicos como 60+/GLP-1) ou começar amplo e deixar o algoritmo otimizar
- Definir posicionamentos (Feed, Stories, Reels — automático vs. manual)
- Confirmar se sobe com orçamento de teste (R$10/dia cada) por quanto tempo antes de revisar CPL
