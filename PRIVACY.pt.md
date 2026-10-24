# Política de privacidade — DPA (Daqui Para Ali)

**Última actualização:** 24 de Outubro de 2026  
**Aplicação:** DPA — Daqui Para Ali (`com.daquiparaali.app`)  
**Contacto:** ldumany@gmail.com

Esta política explica que dados o DPA usa, para quê, e como os pode controlar. O DPA é uma aplicação gratuita de planeamento de viagens de chapa em Maputo. **Não cria conta**: as suas viagens ficam neste telefone.

---

## 1. Resumo

| O quê | Onde | Enviado para fora do telefone? |
|--------|------|--------------------------------|
| Localização (em primeiro plano) | Telefone; enviada só se usar **Perto** | Sim — para o nosso servidor, para mostrar paragens próximas |
| Texto de pesquisa / origem e destino | Telefone e servidor | Sim — para planear rotas e procurar lugares |
| Viagens guardadas e histórico local | Só no telefone | Não |
| Relatórios de erros (opcional) | Firebase Crashlytics | Sim — dados técnicos de falhas, se estiver activo no Perfil |
| Relatórios de problemas (se enviar) | Nosso servidor | Sim — o texto que escrever |

Não vendemos dados. Não temos anúncios. Não usamos o identificador de publicidade.

---

## 2. Localização

O DPA pede localização **apenas em primeiro plano** (enquanto usa a aplicação). Não pedimos localização em segundo plano.

- **Perto:** com a sua autorização, enviamos a latitude e longitude actuais ao nosso servidor (`dpa-backend.fly.dev`) para listar paragens e chapas próximos. Sem permissão, o planeamento de rotas continua a funcionar com nomes de lugares.
- **Em viagem:** a posição no mapa é a do **seu telefone**, não a da viatura; usada no ecrã e não é enviada continuamente como “rastreio”.
- No servidor, as coordenadas em registos e pedidos são tratadas de forma reduzida/redigida onde aplicável. Os registos de pedidos de rota no servidor são **apagados automaticamente ao fim de cerca de 30 dias** (configuração por omissão).

---

## 3. Pesquisas e planeamento de rotas

Quando escreve um lugar ou pede uma rota, o texto (origem/destino ou pesquisa) é enviado por HTTPS ao nosso servidor para devolver resultados. Podemos guardar esse texto em registos técnicos de pedidos de rota, também sujeitos à retenção de cerca de **30 dias**.

---

## 4. Dados só no telefone

Ficam no aparelho (e podem ser apagados nas definições do Android ou na aplicação, conforme o ecrã):

- Viagens guardadas  
- Viagem activa e histórico recente de viagens concluídas  
- Preferências e mapa offline que descarregar  
- Memória local de resultados já vistos (incluindo, por vezes, coordenadas usadas em Perto, para uso offline por um período limitado)

A cópia de segurança do Android / transferência de aparelho, quando activa e cifrada pelo sistema, pode incluir **apenas** as viagens guardadas — não o histórico completo nem a localização.

---

## 5. Relatórios de erros (Crashlytics)

Se mantiver activos os relatórios de erros no **Perfil**, usamos o Firebase Crashlytics para receber dados técnicos sobre falhas, versão da aplicação, sistema Android, modelo do aparelho e identificadores de instalação, para corrigir problemas; **não** acrescentamos pesquisas, localização ou dados das suas viagens, e pode desactivar o envio no Perfil.

Desactivar pede a eliminação de relatórios pendentes no aparelho; não apaga o que já foi enviado. Em compilações de desenvolvimento (debug) estes relatórios não são enviados.

---

## 6. Relatórios de problemas e partilha

Se usar **Reportar** um problema, o texto e o contexto que escolher enviar vão para o nosso servidor para melhorarmos o serviço.  
Se **partilhar** uma viagem pelo menu de partilha do Android, a partilha é iniciada por si e o destino (WhatsApp, etc.) fica sob as regras dessa aplicação.

---

## 7. Pagamentos (M-Pesa)

Quando os pagamentos de tarifas estiverem activos, o número de telefone e dados necessários ao pagamento serão tratados conforme o fornecedor de pagamentos (por exemplo M-Pesa / gateway) e esta política será actualizada. Até lá, a aplicação pode ter fluxos de teste/simulação sem cobrar.

---

## 8. Mapas e alojamento

- O mapa usa serviços de terceiros (por exemplo OpenFreeMap) para estilos e mosaicos; esses pedidos revelam o IP e a zona do mapa que está a ver.  
- O servidor da aplicação está alojado na **Fly.io** (prestador de serviço). Comunicação por **HTTPS**.

---

## 9. Como apagar ou limitar dados

1. Negar ou retirar a permissão de localização nas definições do Android.  
2. Desactivar relatórios de erros no Perfil.  
3. Remover viagens guardadas na aplicação; apagar o mapa offline.  
4. Definições do Android → Aplicações → DPA → Limpar armazenamento / desinstalar.  
5. Para pedidos sobre dados no servidor sem conta ligada a si, escreva para **ldumany@gmail.com** (indique datas aproximadas e o que pretende).

---

## 10. Crianças

O DPA não se destina a crianças com menos de 13 anos e não recolhe dados com o objectivo de os identificar.

---

## 11. Alterações

Podemos actualizar esta política. A data no topo muda. Alterações importantes serão reflectidas na ficha da Play Store e nesta página.

---

## 12. Contacto

Dumany Lombe — Daqui Para Ali  
Email: **ldumany@gmail.com**
