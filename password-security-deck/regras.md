# Trabalho: Password Security Deck

## Entrega

Criar um **deck em HTML, CSS e JavaScript**, parecido com PowerPoint, usando cards, animações e componentes visuais.

## Stack sugerida

* **Reveal.js** — para montar os slides em HTML. É um framework de apresentação em HTML.
* **Three.js** — para cenas 3D no navegador.
* **GSAP** — para animações em JavaScript.
* **Anime.js** — alternativa para animações leves em JS.

## Tema

**Password Security: ataques, armazenamento e proteção**

## Slides obrigatórios

### 1. What is a password?

Explicar:

* O que é uma password?
* Para que ela serve?
* Por que password fraca é um risco?

Visual:

* Cards comparando:

  * Weak password
  * Medium password
  * Strong password
  * Passphrase

---

### 2. Authentication

Explicar:

* O que é authentication?
* O que acontece quando alguém faz login?
* Diferença entre username, password e MFA.

Visual:

* Fluxo animado:

```text
User → Login Form → Server → Validation → Access Granted / Denied
```

---

### 3. Password Storage

Explicar:

* Como passwords são armazenadas?
* O que é plaintext password?
* O que é hash?
* O que é salt?

Visual:

* Accordion com:

  * Plaintext
  * Hash
  * Salt
  * Password Database

---

### 4. Password Cracking Process

Explicar:

* O que é password cracking?
* O que é offline cracking?
* Qual é o processo básico?

Visual:

```text
Hash File → Wordlist / Brute Force → Hash Compare → Match Found
```

Animação:

* Cards ou blocos se movendo até formar o fluxo.

---

### 5. Brute Force Attack

Explicar:

* O que é brute force attack?
* Como funciona?
* Por que password curta quebra mais fácil?

Visual obrigatório:

* Usar **Three.js** para representar tentativas.
* Exemplo:

  * cubos = password attempts;
  * cubo errado desaparece;
  * cubo certo acende.

---

### 6. Dictionary Attack

Explicar:

* O que é dictionary attack?
* Diferença entre brute force e dictionary attack.
* O que é wordlist?

Visual:

* Lista animada de palavras passando na tela.

Exemplos visuais:

```text
123456
password
admin123
company2026
football2026
```

---

### 7. Main Attack Types

Pesquisar e explicar:

* Brute Force Attack
* Dictionary Attack
* Password Spraying
* Credential Stuffing
* Phishing
* Keylogger
* Wi-Fi Handshake Attack

Visual:

* Grid de cards.
* Cada card com:

  * nome do ataque;
  * explicação curta;
  * risco;
  * defesa.

---

### 8. Offline Files

Explicar:

* O que são arquivos usados em offline cracking?
* O que é hash file?
* O que é database dump?
* O que é wordlist?
* O que é Wi-Fi handshake file?

Visual:

* Cards de arquivos:

```text
hash.txt
database_dump.sql
wordlist.txt
wifi_handshake.cap
```

---

### 9. Online Systems

Explicar:

* Diferença entre offline cracking e online attack.
* O que é login form attack?
* O que é rate limit?
* O que é account lockout?
* O que é MFA?

Visual:

```text
Attacker → Login Page → Rate Limit → Block / MFA
```

---

### 10. Wi-Fi Passwords

Explicar:

* O que é WPA/WPA2?
* O que é Wi-Fi handshake?
* Por que senhas fracas de Wi-Fi são perigosas?
* Diferença entre atacar Wi-Fi próprio em laboratório e atacar rede de terceiros.

Visual:

* Cena com:

  * Router
  * Client
  * Handshake
  * Password Guessing

---

### 11. Main Tools

Pesquisar ferramentas conhecidas:

* Hashcat
* John the Ripper
* CeWL
* Crunch
* Hydra
* Aircrack-ng
* Have I Been Pwned

Visual:

* Cards linkados.
* Cada card precisa ter:

  * tool name;
  * purpose;
  * offline or online;
  * defensive use;
  * official link.

---

### 12. Defense

Explicar como se proteger:

* Strong password
* Passphrase
* Password manager
* MFA
* Rate limit
* Account lockout
* Salted hash
* Password policy
* Avoid password reuse

Visual:

* Checklist interativo.

---

## Regras

Não usar conta real.
Não atacar site real.
Não testar Wi-Fi de terceiros.
Não baixar vazamento real.
Tudo deve ser simulado, visual e educativo.

## Resultado esperado

Um deck visual, em HTML/JS, com cara de apresentação moderna, explicando:

```text
What is a password?
How passwords are stored?
How password cracking works?
Main attack types
Main tools
Offline files
Online systems
Wi-Fi attacks
How to defend
```
