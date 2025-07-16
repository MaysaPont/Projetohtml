# Projetohtml
projeto aprendendo HTML
<!DOCTYPE html>

<html>
    <head>
        <title>Quiz</title>
        <meta name="description" content="Um quiz interativo para testar seus conhecimentos">
    </head>
    <body>
        <header>
            <h1>Quiz interativo</h1>
            <p>teste seus conhecimentos em programação e veja qual pontuação você consegue fazer!</p>
        </header>
        <main> 
            <!--introdução-->
            <section>
                <h2>Sobre esse quiz</h2>
                <p><strong>Este quiz</strong> foi desenvolvido para testar seus conhecimentos em programação, como <em>linguagens de programação</em>, conceitos básicos e mais</p>
                <p>Você encontrará diferentes tipos de perguntas, incluindo mútipla escolha, texto e perguntas de data. <br>Desafie-se com este quiz!</p>
                <p>Você poderá encontrar alguns acrônimos como <abbr title="hyperText Markup Language">HTML</abbr> e <abbr title="Cascading Style Sheets">CSS</abbr>, que são comumente usados em questões relacionadas ao desenvolvimento web</p>
            </section>
            <!--pergunta 1: múltipla escolha-->
            <section>
                <h2>Pergunta 1: Qual linguagem é usada para estruturar páginas web? </h2>
                <form>
                    <input type="radio" value="Python" id="p1a" name="pergunta1">
                    <label for="p1a">Python</label><br>
                     <input type="radio" value="HTML" id="p1b" name="pergunta1">
                    <label for="p1b">HTML</label><br>
                     <input type="radio" value="JavaScript" id="p1c" name="pergunta1">
                    <label for="p1c">JavaScript</label><br>
                     <input type="radio" value="Ruby" id="p1d" name="pergunta1">
                    <label for="p1d">Ruby</label>

                </form>
            </section> 
            <!--pergunta 2: texto -->
            <section>
                <h2> Pergunta 2: Na URL https://www.google.com o trecho "google.com" é o ____ </h2>
                <form>
                    <input type="text" id="p2" name="pergunta2" placeholder="Digite sua resposta...">
                </form>

            </section>
            <!--pergunta 3: senha-->
            <section>
                <h2>Pergunta 3: Escreva um exemplo de senha forte</h2>
                <form>
                    <input type="passaword" id="p3" name="pergunta3" placeholder="Digite uma senha...">
                </form>
            </section>
            <!--pergunta 4: data-->
            <section>
                <h2>Pergunta 4: Em que ano o HTML lançou sua primeira versão?</h2>
                <form>
                    <input type="date" id="p4" name:pergunta4">
                </form>
            </section>
            <!--pergunta 5: seleção múltipla-->
            <section>
                <h2>Pergunta 5: Quais dessas tecnologias são consideras linguagens de programação</h2>
                <form>
                    <input type="checkbox" id="p5a"
                    name="pergunta5" value="JavaScript">
                    <label for="p5a">JavaScript</label>
                     <input type="checkbox" id="p5b"
                    name="pergunta5" value="Java">
                    <label for="p5a">Java</label>
                     <input type="checkbox" id="p5c"
                    name="pergunta5" value="HTML">
                    <label for="p5a">HTML</label>
                     <input type="checkbox" id="p5d"
                    name="pergunta5" value="CSS">
                    <label for="p5a">CSS</label>
                
                </form>
            </section>
            <!--pergunta 6: upload de arquivo -->
            <section>
                <h2>Pergunta 6: Faça o upload de um arquivo contendo código HTML</h2>
                 <form>
                    <input type="file" id="p6" name="pergunta6">
                 </form>
            </section>
            <!--pergunta 7: menu suspenso-->
            <section>
                <h2>Pergunta 7: Selecione o atributo do input que define o seu tipo:</h2>
                <form>
                    <select name="pergunta7" id="p7">
                        <option value="id">id</option>
                        <option value="type">type</option>
                        <option value="placeholder">placeholder</option>
                    </select>
                </form>
            </section>
            <!--pergunta 8: imagem-->
            <section>
                <h2>Pergunta 8: Qual linguagem de programação é representada pelo logotipo abaixo?</h2>
                <figure>
                <img src="./assets/python.jpeg" alt="logotipo de uma linguagem de programação"><br>
                <figcaption>Figura 1: Logotipo de uma linguagem de programação</figcaption>
                 </figure>
                <input type="text" id="p8" name="pergunta8" placeholder="Digite sua resposta...">
            </section>
            <!--tabela de pontuação-->
            <section>
                <h2>Tabela de pontuação</h2>
                <table border ="1">
                    <thead>
                        <th>Pontuação</th>
                        <th>Avaliação</th>
                    </thead>
                    <tbody>
                  
                    <tr>
                        <td>0-2</td>
                        <td>0-2 Não desista! Cada tentativa é uma oportunidade de aprender mais</td>
                    </tr>
                    <tr>
                        <td>3-4</td>
                        <td>3-4 Você ainda precisa melhorar. Que tal estudar mais sobre programação</td>
                    </tr>
                     <tr>
                        <td>5-7</td>
                        <td>5-7 Bom seu conhecimento em programação está satisfatorio</td>
                    </tr>
                       <tr>
                        <td>8</td>
                        <td>8 Perfeito! Você está muito bem informado sobre programação!</td>
                    </tr>
                    </tbody>
                    <tfoot>
                        <tr>
                            <td colspan="2">Boa Sorte na proxima! Estude mas para melhorar</td>
                        </tr>
                    </tfoot>
                </table>
            </section>
            <!--listas de respostas-->
            <section>
                <h2>Verifique suas respostas</h2>
                <details> 
                    <summary>Clique aqui para ver as respostas do quiz</summary>
                <ol>
                    <li>HTML</li>
                    <li>Domínio</li>
                    <li>@Solnascente23</li>
                    <li>1991</li>
                    <li>Javascript, Java</li>
                    <li>Arquivo deve ter extensão HTML </li>
                    <li>type</li>
                    <li>Python</li>
                </ol>
                </details>
            </section>
            <!--formulario de feedback-->
            <h2>Nós dê seu feedback</h2>
            <form>
                <fieldset>
                    <legend>Informações de contato</legend>
                <label for="nome:">Nome:</label>
                <input type="text" id="nome" name="nome"><br>
                <label for="email">Email:</label>
                <input type="text" id="email" name="email"><br>
                <label for="comentarios">Comentarios:</label>
                <textarea  id="comentarios" name="comentarios" rows="4" cols="50" placeholder="Digite seus comentários aqui"></textarea>
                </fieldset>
               </form>
            </sectio>
        </main>
        <footer>
            <p>&copy Quiz de programadores. Todos os direitos reservados!</p>
        </footer>
    </body>

</html>
