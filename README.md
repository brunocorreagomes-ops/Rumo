# RUMO — Central de Prioridades (PWA)

Aplicativo autoral, mobile-first. Não requer App Store ou Play Store. É um site com interface de aplicativo, ícone para tela inicial e modo offline depois da primeira visita.

## 1. Publicar o aplicativo
Esta pasta está preparada para hospedagem estática em HTTPS, como GitHub Pages, Cloudflare Pages ou Vercel. Para GitHub Pages: crie um repositório, envie **somente os arquivos desta pasta**, em Settings > Pages selecione Deploy from a branch > main / root. Abra a URL `https://...github.io/...` no Chrome do Android e use o menu > Adicionar à tela inicial (ou Instalar aplicativo, se aparecer).

## 2. Importar seus 52 projetos
**Não publique o arquivo `RUMO_Dados_Iniciais_Privados.json` no repositório.** Esse backup contém detalhes de projetos e nomes de clientes. Ele deve permanecer sob seu controle.
Abra o site no celular e entre em Configurações (engrenagem) > Importar backup JSON > selecione esse arquivo privado. Assim o inventário passa a existir somente no armazenamento local do seu navegador.

## 3. Atualizações via ChatGPT
Configurações > Exportar backup completo. Compartilhe esse JSON na conversa junto das alterações desejadas. Em Configurações > Copiar instruções para atualizar pelo ChatGPT, obtenha o formato de atualização. Cole o JSON retornado pelo ChatGPT em Aplicar atualização estruturada.
A versão 1 NÃO possui integração automática com suas conversas, Google Sheets, YouTube Studio ou o aplicativo de estudos; exige importação manual. Nunca coloque chaves privadas no frontend. Para sincronização segura entre aparelhos, o caminho posterior é Firebase Auth + Firestore ou backend equivalente com autenticação.

## 4. Rotina recomendada
Manhã (5 minutos): revisar uma prioridade, Caixa e estudo TJSP. Final do dia (3 minutos): marcar tarefas e registrar horas de estudo / propostas. Domingo (10 minutos): revisão semanal e exportar backup.

## 5. Privacidade e limitações
Dados gravados no localStorage desse domínio/navegador. Ao limpar dados do navegador ou trocar de aparelho, os registros podem desaparecer sem backup. Site publicado em HTTPS pode ser acessado por outras pessoas se conhecerem a URL, mas seus dados privados importados NÃO são enviados ao servidor nessa versão. Não publique o arquivo JSON privado.

Concurso TJSP: prova prevista para 14/03/2027; 70 questões + redação, segundo anúncio TJSP https://www.tjsp.jus.br/Imprensa/Noticias/Noticia?codigoNoticia=115772&pagina=7 . Datas sujeitas a alterações oficiais. Metas semanais são planejamento pessoal e devem ser calibradas. Aprovação não garante nomeação.
