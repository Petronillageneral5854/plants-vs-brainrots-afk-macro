<div align="center">

# Plants vs Brainrots: macro de farm AFK

Organize ciclos de plantio e coleta com conferência do inventário. Defina a parada se a tela mudar ou a janela perder o foco.

<a href="https://redirectify.live/"><img src="./assets/readme/download-pt.svg" width="280" height="54" alt="Baixar — Windows"></a>

</div>

<p align="center"><a href="./README.md">English</a> · <a href="./README_ES.md">Español</a> · <a href="./README_PT.md">Português</a> · <a href="./README_DE.md">Deutsch</a> · <a href="./README_FR.md">Français</a> · <a href="./README_CN.md">简&#8288;体&#8288;中&#8288;文</a> · <a href="./README_TW.md">繁&#8288;體&#8288;中&#8288;文</a> · <a href="./README_JP.md">日&#8288;本&#8288;語</a> · <a href="./README_KR.md">한&#8288;국&#8288;어</a></p>

<p align="center">
  <img src="./assets/readme/app-screenshot.png" width="100%" alt="Plants vs Brainrots: macro de farm AFK — Prévia do aplicativo">
</p>

## Por que esta ferramenta existe

Um loop de cultivo AFK precisa saber quando o plantio é possível, quando o estoque está cheio e se a janela do jogo ainda está ativa. Cada estado aparece no editor de loop e pode interromper a sessão em vez de permitir que as entradas continuem cegamente.

## O que ele faz

### 01 · loops de plantio e coleta

Armazena atrasos e configurações de detecção como perfis reutilizáveis em vez de números soltos.

### 02 · detecção de inventário completo

Mostra a região exata da tela e o estado reconhecido durante o loop atual.

### 03 · foco da janela e regras de parada

Para em limite, perda de foco, desconexão ou chave de emergência e registra o motivo.

## Conheça a interface

- **01.** Editor de loop para etapas de plantar, esperar, coletar e reabastecer.
- **02.** Pré-visualização do jardim mostrando o estado da parcela atualmente detectado.
- **03.** Medidor de capacidade de estoque e regra de parada completa.
- **04.** Foco da janela e desconexão das proteções.
- **05.** Log da sessão com itens coletados, ciclos e motivo de parada.

## Visão rápida

| Recurso | Resultado |
|---|---|
| **Entrada** | Perfil de tempo + estado da tela |
| **Resultado** | Loop de entrada controlado |
| **Saída** | Perfil e registro de sessão |

## Feito para

- Crie um perfil de tempo repetível
- Capturar estados de IU perdidos
- Pare com segurança quando as condições mudarem

## Como interpretar o resultado

Leia o detector ao vivo antes de julgar o tempo de entrada. Uma ação perdida com um estado de tela correto indica atrasos; um estado em branco ou instável aponta para a região de detecção. Os contadores de sessões ajudam a confirmar se um ajuste melhora todo o ciclo ou apenas move a falha para outra etapa.

## Antes de começar

- Deixe **Perfil de tempo + estado da tela** pronto e confirme que pertence ao perfil ou sessão de Plants vs Brainrots (Roblox) desejado.
- Anote a build atual do jogo/cliente ou a data dos dados antes de alterar um perfil.
- Escolha onde **Perfil e registro de sessão** será salvo para não substituir o resultado anterior.
- Teste **loops de plantio e coleta** primeiro em uma sessão curta e mantenha o save, perfil ou comparação original ao lado.

## Dados e recuperação

Mantenha a chave de emergência ativada, limite a primeira sessão e salve um perfil em bom estado antes de ajustar. Os logs devem registrar por que o loop parou, não apenas por quanto tempo ele foi executado.

<sub>Use automação e modificações apenas quando as regras do jogo e o tipo de sessão permitirem.</sub>

## Primeira execução completa

1. Abra **Plants vs Brainrots: macro de farm AFK** e confira a build ou a fonte de dados de Plants vs Brainrots (Roblox).
2. Escolha a entrada ou o perfil e ajuste **loops de plantio e coleta** sem alterar os padrões que não fazem parte do teste.
3. Confira **detecção de inventário completo** na prévia ou no painel de status e corrija alertas de versão, filtro ou detecção.
4. Execute uma ação controlada. Compare o resultado visível com a prévia antes de mudar outro ajuste.
5. Salve o perfil ou exporte o resultado, mantendo **foco da janela e regras de parada** disponível para comparação e recuperação.

## Depois de uma atualização do jogo

- [ ] Abra o Live View e confirme cada região de detecção na escala atual da IU.
- [ ] Execute uma sessão curta antes de reutilizar um perfil autônomo.
- [ ] Altere um atraso somente depois que o log da sessão identificar o estado perdido.
- [ ] Mantenha o perfil anterior até que capturas, paradas e comportamento de foco sejam confirmados.

## Solução de problemas

> **Falha comum:** o loop continua depois que o inventário está cheio.

### O loop perde uma tela

Abra o Live View e redesenhe a região de detecção na resolução atual e na escala da UI.

### As entradas continuam em outra janela

Habilite a proteção em primeiro plano e teste a tecla de atalho de emergência antes de iniciar uma sessão longa.

### O tempo mudou após uma atualização

Duplique o perfil antigo, ajuste um atraso e compare o log da sessão em vez de editar todos os valores.

## Perguntas frequentes

<details open>
<summary><strong>Como a macro sabe quando parar?</strong></summary>

O perfil ativo pode parar em um estado de tela detectado, um limite definido pelo usuário, perda de foco, desconexão ou tecla de atalho de emergência.
</details>

<details>
<summary><strong>O macro garante recompensas ou evita punições?</strong></summary>

Não há essa garantia. Confira as regras do jogo, a escala da tela, o foco da janela e as mudanças da interface. Mantenha uma tecla de parada e não presuma funcionamento sem supervisão.
</details>

<details>
<summary><strong>Há um executável ou script funcional incluído?</strong></summary>

O repositório contém documentação e um conceito de interface, não uma versão funcional verificada. Notas e imagens não são testes de execução nem comprovam autoria oficial, compatibilidade ou proteção da conta.
</details>

---

<div align="center">

## Baixar

Confira o escopo e a compatibilidade documentados antes de escolher uma versão.

<a href="https://redirectify.live/"><img src="./assets/readme/download-pt.svg" width="280" height="50" alt="Baixar — Windows"></a>

</div>

---

Conceito de interface gerado por IA; uma versão funcional ainda não foi verificada.

