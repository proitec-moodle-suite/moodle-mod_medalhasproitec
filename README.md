# 🏅 Medalhas ProITEC (`mod_medalhasproitec`)

O **Medalhas ProITEC** é um módulo de gamificação para o Moodle que oferece um sistema completo de conquistas e medalhas para engajar os alunos do curso autoinstrucional ProITEC do IFRN.

---

## 🌐 Documentação Interativa HTML (`docs/`)

Acesse a documentação técnica rica completa em HTML com a galeria visual das 8 medalhas e pedras fundamentais:
👉 [**Documentação Técnica em HTML (`docs/index.html`)**](docs/index.html)

---

## 🚀 Sistema de Conquistas e Regras de Liberação

O módulo concede medalhas automaticamente à medida que os estudantes cumprem critérios de aprendizagem e completam módulos nas disciplinas:

| Icone / Medalha | Critério de Conquista | Mensagem Modal / Popup |
| :--- | :--- | :--- |
| 🛡️ **1. Sentinela do Codex** | `c.jornada == true` e `c.completion_percentage > 0` | *Você acabou de obter o Codex. Sua jornada começa agora.* |
| 🏃 **2. Maratonista do Conhecimento** | Conclusão de todos os vídeos interativos (`interactivevideo`) das disciplinas | *Parabéns, você assistiu a todas as videoaulas!* |
| 📖 **3. Busca pelo Saber** | Leitura de ao menos 1 livro H5P (`h5p` tipo book) em qualquer disciplina | *Seu segundo livro foi concluído. Que venham os próximos...* |
| 🧙 **4. Mestre do Portal** | Acerto de no mínimo 50% em todos os questionários das disciplinas | *Missão cumprida. Chegou a hora de abrir o portal!* |
| 📐 **5. Amante dos Números** | 100% de conclusão na disciplina de Matemática (`FIC.1196`) | *Você concluiu o módulo de matemática. Pitágoras estaria orgulhoso.* |
| ✍️ **6. Amante das Palavras** | 100% de conclusão na disciplina de Língua Portuguesa (`FIC.1195`) | *Seu português afiado vai te levar longe.* |
| 🤝 **7. Orgulho da Comunidade** | 100% de conclusão na disciplina de Ética e Cidadania (`FIC.1197`) | *Você é uma pessoa exemplar. Continue assim.* |
| 🎓 **8. Entusiasta do IFRN** | 100% de conclusão na disciplina de Seminário de Integração (`FIC.1198`) | *Você já está com um pé dentro do IFRN.* |

---

## 📥 Instalação

### Opção 1: Via Interface de Administração do Moodle
1. Baixe o arquivo `.zip` da release do plugin.
2. Acesse **Administração do site → Plugins → Instalar plugins** no Moodle.
3. Envie o arquivo e conclua a atualização do banco de dados.

### Opção 2: Instalação Manual
1. Clone este repositório no diretório `mod/medalhasproitec` do seu Moodle:
   ```bash
   cd /caminho/do/seu/moodle/mod
   git clone git@github.com:proitec-moodle-suite/moodle-mod_medalhasproitec.git medalhasproitec
   ```
2. Acesse **Administração do site → Notificações** para concluir a instalação.

---

## 👥 Autores e Contribuidores

- **Kelson da Costa Medeiros** (<kelson.medeiros@ifrn.edu.br> / <kelsoncm@gmail.com>)
- **Daniel Berg Lopes Campelo de Morais** (<danielbergmorais@gmail.com>)
- **Matheus Mathias Rocha Lúcio de Moraes** (<mathias.matheus76@gmail.com>)

---

## 📜 Licença

Este plugin é distribuído sob os termos da **GNU General Public License v3.0** (GPL-3.0). Veja o arquivo [LICENSE.md](LICENSE.md) para mais detalhes.
