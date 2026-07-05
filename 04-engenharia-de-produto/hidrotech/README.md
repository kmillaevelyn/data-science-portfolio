# Hidrotech — Coluna de Ducha Inteligente

Projeto de **Desenvolvimento de Produto do início ao fim** (PDP — UNIFEI): um chuveiro inteligente com controle de temperatura grau a grau, monitoramento de consumo de água em tempo real, cromoterapia LED RGB (9 cores) e áudio Bluetooth integrado — levado da ideação até a especificação completa de fabricação em escala industrial.

## O ciclo completo percorrido

1. **Design Thinking** — imersão, definição do problema e ideação a partir das dores reais do banho: consumo excessivo, regulagem de temperatura, medo de choque elétrico e eletrônicos em ambiente úmido
2. 2. **Jornada do usuário** — mapeamento da experiência da descoberta à fidelização, com dores e oportunidades por etapa
   3. 3. **MVP (Beta 1.0)** — protótipo funcional com ESP32, sensor de fluxo de Efeito Hall, relé térmico de corte automático, LED RGB e aplicativo low-code
      4. 4. **Modelagem funcional e conceitual** — caixa preta (material, energia, informação) e matriz morfológica para seleção das soluções técnicas
         5. 5. **Gestão ágil (Scrum-ban)** — quadro Kanban com WIP limitado integrando hardware e software
            6. 6. **DFMEA** — análise de modos de falha com política de risco: ação obrigatória para NPR > 100 ou Severidade ≥ 9
               7. 7. **DFMA** — transição da impressão 3D (protótipo) para injeção plástica PC/ABS, componentes COTS, encaixes snap-fit e poka-yoke
                  8. 8. **Confiabilidade e homologação** — testes HALT/MTBF, inspeção 100% em segurança elétrica e Cpk ≥ 1,33 nas cotas críticas
                     9. 9. **Especificação de fabricação** — ficha técnica, BOM, tolerâncias, parâmetros de injeção, normas (INMETRO, ANATEL, IEC 60529, NBR NM 60335) e rastreabilidade por número de série vinculado a atualização OTA
                       
                        10. ## Ficha técnica (produto final)
                       
                        11. - Aquecimento elétrico instantâneo: 5.500 W (127 V) / 6.800 W (220 V), controle de 25 °C a 45 °C
                            - - Vazão ajustável de 3 a 12 L/min com medição de consumo em litros no app
                              - - Compartimento eletrônico IP68 com separação física entre zona seca e câmara de água
                                - - ESP32 com Bluetooth 5.0 e Wi-Fi (OTA), painel touch selado e app iOS/Android
                                 
                                  - ## Decisão de engenharia em destaque
                                 
                                  - O maior risco do FMEA foi o travamento do microcontrolador (NPR 120), mitigado com watchdog timer e atualização remota. Já a infiltração na placa lógica, mesmo com NPR moderado, tem Severidade 10 — e por isso recebeu redundância térmica e teste de estanqueidade obrigatório: segurança acima do número.
                                 
                                  - ## Equipe
                                 
                                  - Kamilla Evelyn, Pedro Paulo Machado, Abner Fermino e João Guilherme Cerqueira Magalhães — UNIFEI, 2026.
                                 
                                  - ---

                                  *Parte do portfólio de [Kamilla Evelyn](https://kmillaevelyn.github.io).*
