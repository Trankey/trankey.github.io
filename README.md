<div align="center">

<img src="public/icon.svg" width="92" height="92" alt="Logo do Trankey" />

# Trankey

**Gratuito · Privado · Offline · Multilíngue (EN · PT · ES)**

Gerencie assinaturas, pagamentos recorrentes e senhas em um só lugar. O cofre usa criptografia local AES-256-GCM e pode ser desbloqueado com a biometria do dispositivo, quando compatível.

[![Hub de aplicativos](https://img.shields.io/badge/hub-meus_aplicativos-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white )](https://saulomgg.github.io/ )
[![Apoiar via Mercado Pago](https://img.shields.io/badge/apoie-mercado_pago-009EE3?style=for-the-badge&logo=mercadopago&logoColor=white )](https://link.mercadopago.com.br/saulomgg )
[![Apoiar via Stripe](https://img.shields.io/badge/apoie-stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white )](https://buy.stripe.com/test_3cI7sN6FT5Er2Xhean2Ji00 )

[![Instagram](https://img.shields.io/badge/Instagram-@saulo__mgg-E4405F?style=flat-square&logo=instagram&logoColor=white )](https://instagram.com/saulo_mgg )
[![YouTube](https://img.shields.io/badge/YouTube-@saulomgg-FF0000?style=flat-square&logo=youtube&logoColor=white )](https://youtube.com/@saulomgg )
[![Licença](https://img.shields.io/badge/licença-direitos_reservados-0F172A?style=flat-square )](./LICENSE)

</div>

---

### `> whoami`

```text
$ cat /dev/trankey
Nome:    Trankey
Autor:   Saulo (saulomgg)
Preço:   gratuito, sem mensalidade ou recursos bloqueados
Foco:    assinaturas · pagamentos · cofre de senhas · biometria
Modo:    PWA instalável · offline · sem cadastro · EN / PT / ES
```

O **Trankey** é um aplicativo web progressivo (PWA), gratuito e independente, para organizar assinaturas, pagamentos recorrentes e senhas em um só lugar. Não é necessário criar uma conta. Os dados e a criptografia do cofre são processados localmente no dispositivo, sem sincronização com um servidor do projeto.

---

### `> ls ./recursos`

| Recurso | Detalhes |
| :--- | :--- |
| 💳 **Pagamentos e assinaturas** | Acompanhe vencimentos, ciclos mensais, anuais, semanais ou únicos, métodos de pagamento e status de pagamento |
| 🔐 **Cofre criptografado** | Guarde logins, senhas, PINs, URLs e notas com criptografia local AES-256-GCM e derivação de chave PBKDF2-SHA256 |
| 👆 **Desbloqueio biométrico** | Use a autenticação do dispositivo via WebAuthn, quando disponível no navegador e no aparelho |
| 🔑 **Gerador e auditoria de senhas** | Crie senhas fortes e verifique a força das senhas, incluindo a identificação de senhas fracas ou repetidas |
| 📊 **Relatórios e meta mensal** | Consulte projeções mensais e anuais, gastos por categoria ou método, histórico de pagamentos e limite mensal |
| 🔔 **Avisos e lembretes** | Receba avisos sobre contas a vencer, senhas vulneráveis e lembretes para fazer backup local |
| 💾 **Backup portátil em JSON** | Exporte e restaure seus dados e o cofre criptografado para transferi-los entre dispositivos |
| 🌐 **Multilíngue (EN · PT · ES)** | Use o app em inglês, português ou espanhol pelo seletor de idioma |
| 📱 **PWA instalável e offline** | Instale no celular ou computador e use o app offline, conforme o suporte do navegador |

---

### `> cat ./privacidade`

```json
{
  "cadastro": false,
  "preco": "gratuito",
  "processamento": "no dispositivo do usuário",
  "sincronizacao_com_servidor_do_projeto": false,
  "offline": true,
  "criptografia_cofre": "AES-256-GCM + PBKDF2-SHA256",
  "biometria": "WebAuthn, quando disponível no dispositivo",
  "armazenamento_local": "localStorage + IndexedDB",
  "rastreamento": false
}
```

- **Sem cadastro:** abra o Trankey pelo hub de aplicativos e comece a usar.
- **Dados locais:** pagamentos, senhas e backups ficam armazenados no dispositivo; o projeto não oferece sincronização própria em nuvem.
- **Cofre criptografado:** os segredos são cifrados localmente com a Web Crypto API antes de serem armazenados.
- **Cuide do seu backup:** limpar os dados do navegador pode apagar as informações locais. Exporte backups JSON periodicamente e guarde seu PIN Mestre em local seguro.

---

### `> ./iniciar`

```text
1. Acesse     https://saulomgg.github.io/ e abra o Trankey no hub de aplicativos
2. Escolha    selecione o idioma no topo (EN · PT · ES)
3. Organize   cadastre assinaturas, vencimentos e metas mensais
4. Proteja    configure seu PIN Mestre e, se disponível, ative o desbloqueio biométrico
5. Instale    use a opção de instalação do navegador para adicionar o app à tela inicial
```

---

### `> ls ./roadmap`

**Já implementado:**

- Controle de assinaturas, pagamentos, metas e histórico.
- Cofre criptografado com AES-256-GCM, PIN Mestre, gerador de senhas e verificação de segurança.
- Desbloqueio biométrico local via WebAuthn, quando compatível com o dispositivo.
- Autopreenchimento configurável nos ajustes e troca de idioma entre inglês, português e espanhol.
- Backup completo em JSON e funcionamento como PWA offline instalável.

**Próximas melhorias:**

- Categorias e lembretes recorrentes personalizáveis.
- Exportação de relatórios financeiros em CSV ou PDF.
- Melhorias contínuas de interface, acessibilidade e estabilidade.

---

### `> ping apoio`

O **Trankey** é gratuito e independente, desenvolvido por **Saulo (saulomgg)**. O apoio da comunidade ajuda a dedicar tempo ao projeto, criar melhorias e desenvolver outros aplicativos gratuitos.

> **Apoiar é voluntário.** A contribuição não libera recursos pagos, não cria mensalidade e não altera a privacidade do aplicativo.

<div align="center">

[![Apoiar pelo Mercado Pago](https://img.shields.io/badge/apoie-via_Mercado_Pago-009EE3?style=for-the-badge&logo=mercadopago&logoColor=white )](https://link.mercadopago.com.br/saulomgg )
[![Apoiar pelo Stripe](https://img.shields.io/badge/apoie-via_Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white )](https://buy.stripe.com/test_3cI7sN6FT5Er2Xhean2Ji00 )

</div>

---

### `> ls ./contato`

| Canal | Finalidade | Acesso |
| :--- | :--- | :--- |
| 🌐 **Hub de aplicativos** | Conheça e acesse os aplicativos | [saulomgg.github.io](https://saulomgg.github.io/ ) |
| 📸 **Instagram** | Novidades, bastidores e contato | [@saulo_mgg](https://instagram.com/saulo_mgg ) |
| ▶️ **YouTube** | Vídeos, demonstrações e atualizações | [@saulomgg](https://youtube.com/@saulomgg ) |

---

### `> cat ./LICENSE`

```text
© 2026 Saulo (saulomgg). Todos os direitos reservados.

O código-fonte, a arquitetura, a identidade visual, a marca, o logotipo,
os textos e os demais ativos do Trankey pertencem ao autor e são protegidos
pela legislação aplicável de direitos autorais e de software, incluindo as
Leis nº 9.610/1998 e nº 9.609/1998 e os tratados internacionais aplicáveis.

Uso permitido: utilização gratuita do aplicativo pelo usuário final para
organizar seus próprios pagamentos e senhas.

Sem autorização prévia e expressa, por escrito, do titular, não é permitido
copiar, redistribuir, vender, revender, sublicenciar, publicar cópias ou
apresentar este projeto, no todo ou em parte, como se fosse de autoria própria.
```

Consulte o texto integral no arquivo [`LICENSE`](./LICENSE).

---

<div align="center">

Desenvolvido por **Saulo ([saulomgg](https://saulomgg.github.io/ ))**

[Hub de aplicativos](https://saulomgg.github.io/ ) · [Instagram](https://instagram.com/saulo_mgg ) · [YouTube](https://youtube.com/@saulomgg )

```text
+--------------------------------------------------------+
| [SYSTEM]  Trankey - Gratuito e independente            |
| [STATUS]  Offline - Sem cadastro - EN / PT / ES         |
| [PRIVACY] Criptografia local - Sem rastreamento        |
+--------------------------------------------------------+
```

</div>
