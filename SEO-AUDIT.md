# Auditoria de SEO — Lara Maehata Nail Design
**Objetivo:** ser encontrada por clientes em Elias Fausto (SP) e região, e transformar visitas em agendamentos.
**Data:** 28/07/2026 · **Site auditado:** https://wilquisonf-hub.github.io/lara-maehata-nail-design/

---

## Resumo

O site já tem uma base técnica **muito boa** (rápido, responsivo, textos com palavras‑chave, imagens com descrição, dados estruturados de negócio). Os maiores ganhos de **leads** não estão no código — estão em **presença local no Google** e **avaliações**. Abaixo, o que corrigi agora e o passo a passo do que trará clientes.

**Nota técnica atual:** ~8/10 (era ~6/10 antes das correções abaixo).
**Onde estão os leads:** Perfil da Empresa no Google + Avaliações + Instagram → 80% do jogo para um salão local.

---

## 1. Correções técnicas aplicadas agora (no código)

| # | Problema | Correção |
|---|----------|----------|
| 1 | `canonical` apontava para uma URL **inexistente** (`...vercel.app`) — Google poderia ignorar/indexar errado | Apontado para a URL real do site |
| 2 | **Sem `robots.txt`** (404) | Criado, liberando indexação e apontando o sitemap |
| 3 | **Sem `sitemap.xml`** (404) | Criado — facilita o Google achar/indexar |
| 4 | `og:image` era **relativo** (quebrava a prévia ao compartilhar no WhatsApp/Insta) | Deixado **absoluto** + adicionado `og:url` |
| 5 | Dados estruturados sem **localização geográfica nem cidades atendidas** | Adicionado `geo`, `areaServed` (cidades), `url`, `image`, `logo`, `currenciesAccepted` |
| 6 | `<title>` começava pela marca | Reescrito começando pela **palavra‑chave + cidade**: “Alongamento de Unhas e Nail Design em Elias Fausto‑SP” |
| 7 | Sem espaço para verificação do Search Console | Comentário pronto no `<head>` para colar o código |

> ⚠️ **Ajuste você (no `index.html`):** em `areaServed` do bloco de dados estruturados, deixei Elias Fausto + Capivari + Monte Mor + Indaiatuba como exemplo — **mantenha só as cidades que você realmente atende**. As coordenadas (`geo`) são aproximadas do centro de Elias Fausto; o Google Business Profile é quem manda no mapa.

---

## 2. AÇÃO #1 para leads — Perfil da Empresa no Google (grátis)

Para salão de bairro, **é isso que mais traz cliente**. É o que aparece no Google Maps e no “bloco local” quando alguém busca *“unha em Elias Fausto”*, *“alongamento perto de mim”*.

**Passo a passo:**
1. Acesse **google.com/business** e crie o perfil “Lara Maehata Nail Design”.
2. Categoria principal: **Salão de manicure e pedicure** (secundárias: *Manicure*, *Serviço de alongamento de unhas*).
3. **Área de atendimento:** como é atendimento com hora marcada, defina como *“atendo clientes no meu endereço”* ou *“área de atendimento”* (Elias Fausto + cidades vizinhas).
4. Telefone/WhatsApp: **+55 19 99489‑0873**. Site: a URL do site.
5. **Horários reais** de atendimento (importantíssimo).
6. Suba **10–15 fotos** de qualidade (trabalhos, ambiente, você trabalhando) — reaproveite as do site.
7. Ative **mensagens** e o botão de agendamento (pode direcionar ao WhatsApp).
8. Poste 1x por semana (promoções, novidades) — o Google favorece perfis ativos.

---

## 3. Avaliações (reviews) — o motor de confiança e de ranking

- Peça avaliação no Google **para toda cliente satisfeita** (mande o link direto do seu perfil pelo WhatsApp após o atendimento).
- Meta inicial: **10 avaliações** nas primeiras semanas. Responda todas (educadamente).
- Quando tiver avaliações, dá pra exibir as estrelas no Google (rich snippet) e trocar os depoimentos “exemplo” do site pelos reais.

---

## 4. Domínio próprio (recomendado)

Hoje o endereço é um subcaminho do GitHub (`wilquisonf-hub.github.io/...`). Funciona, mas para um negócio vale muito ter **domínio próprio** (ex.: `laramaehata.com.br`):
- Passa **profissionalismo** e é mais fácil de divulgar/lembrar.
- Melhor para SEO e para o link da bio do Instagram.
- Custo baixo (registro.br) + publicar na **Vercel** (seu plano original) ou manter no GitHub Pages com domínio custom.
- Ao trocar de domínio, atualize: `canonical`, `og:url`, `sitemap.xml`, `robots.txt` e o `url` dos dados estruturados (é só um “localizar e substituir”).

---

## 5. Palavras‑chave locais e conteúdo

Quem busca serviço de unha procura por **serviço + cidade**. Reforce naturalmente nos textos e considere criar seções/páginas:
- “Alongamento de unhas em Elias Fausto”, “Esmaltação em gel em Elias Fausto”, “Blindagem de unhas”, “Banho de gel”.
- A seção **FAQ** já ajuda muito (o Google adora perguntas e respostas). Dá pra adicionar: *“Atende quais cidades?”*, *“Quanto custa o alongamento?”* (faixa de preço), *“Formas de pagamento?”*.
- Ideia de crescimento: um mini‑blog com 3–4 posts (“Como cuidar do alongamento”, “Gel x fibra”, “Tendências de unha 2026”) captura buscas informativas e traz visitas novas.

---

## 6. Instagram → Site (funil de agendamento)

- Coloque o **link do site na bio** (@laraaika_nails). Se quiser, um link com mais opções (site + WhatsApp).
- Padronize **Nome, telefone e cidade** iguais em Instagram, Google e site (o Google cruza esses dados).
- Nos posts/stories, chame para o site/WhatsApp (“link na bio para agendar”).
- Reels de antes/depois costumam trazer muito alcance local.

---

## 7. Diretórios e presença local

Cadastre o negócio (com os mesmos dados) em:
- **Google Business Profile** (prioridade), **Facebook** (página), **Instagram** (feito).
- Plataformas de serviços: **GetNinjas**, e grupos locais de Elias Fausto (Facebook/WhatsApp de bairro).
- Cada citação consistente (nome + telefone + cidade) reforça o SEO local.

---

## 8. Medição — saber o que funciona

1. **Google Search Console** (search.google.com/search-console): adicione o site, verifique (cole o código no espaço que deixei no `<head>`) e **envie o `sitemap.xml`**. Mostra por quais termos você aparece.
2. **Google Analytics 4** (opcional): quantas visitas e de onde vêm.
3. Acompanhe quantas pessoas clicam no botão **“Agendar no WhatsApp”**.

---

## 9. Tráfego pago (opcional — leads rápidos)

Se quiser acelerar enquanto o orgânico cresce:
- **Instagram/Facebook Ads** segmentado por **raio geográfico** (Elias Fausto + X km), mulheres, interesses de beleza. Orçamento pequeno já testa.
- **Google Ads** para buscas como “alongamento de unhas Elias Fausto”.
- Leve todo clique para o **WhatsApp** com mensagem pronta (já configurado no site).

---

## Checklist priorizado

**Esta semana (grátis, maior impacto):**
- [ ] Criar e completar o **Perfil da Empresa no Google** (fotos + horários)
- [ ] Pedir as **primeiras 5–10 avaliações** no Google
- [ ] Verificar o site no **Search Console** e enviar o sitemap
- [ ] Ajustar `areaServed` no código para as cidades reais + revisar o `<title>`
- [ ] Link do site na **bio do Instagram**

**Próximas semanas:**
- [ ] Registrar **domínio próprio** e publicar (Vercel)
- [ ] Adicionar **horários** aos dados estruturados (bloco pronto abaixo)
- [ ] Trocar depoimentos “exemplo” pelos **reais**
- [ ] Cadastrar em diretórios locais

**Contínuo:**
- [ ] Postar no Google/Instagram semanalmente
- [ ] Responder todas as avaliações
- [ ] (Opcional) testar anúncios geolocalizados

---

### Anexo — bloco de horários para os dados estruturados
Quando definir os horários, cole isto dentro do JSON de dados estruturados (ajuste dias/horas):
```json
"openingHoursSpecification": [
  {"@type": "OpeningHoursSpecification", "dayOfWeek": ["Tuesday","Wednesday","Thursday","Friday"], "opens": "09:00", "closes": "19:00"},
  {"@type": "OpeningHoursSpecification", "dayOfWeek": "Saturday", "opens": "09:00", "closes": "16:00"}
]
```
