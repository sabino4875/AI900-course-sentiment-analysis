# Curso AI-900 - Análise de sentimentos
## Criação de um recurso para análise de sentimentos no Language Studio

1. Na página inicial do Portal do Azure, em **https://portal.azure.com**, clique sobre o botão **Adicionar Recurso**.

2. Selecione o item de menu à esquerda **IA + Machine Learning**
No item **Análise de texto**, clique em **Criar**.

3. Na primeira tela do assistente, mantenha as configurações selecionadas e pressione o botão **Continuar para criar seu recurso**.

4. Na segunda tela, Crie um novo recurso - Nos testes foi criado o recurso **language-learning-resource**.

5. Nos testes, a região selecionada foi a **East US 2**, por questões de preço

6. Preencha o campo nome - Nos testes foi utilizado o nome  **language-learning-instance**.

7. No campo de preço, selecione **Free F0 (5K Transactions per 30 days)**.

8. Marque a caixa de seleção, **após revisar os termos referentes ao uso responsável da IA**.

9. Mantenha as outras configurações com o seus valores padrão. Clique sobre o botão **Examinar + Criar**.

10. Não havendo nenhum problema na revisão, clique sobre o botão **Criar** e aguarde o término do processo

**Obs.** - Nos testes, demorou 15 minutos para o recurso poder ser utilizado.

## Acesso e uso do recurso no Language Studio

1. Após a criação do recurso, vá até **https://language.cognitive.azure.com/**, faça o login, e na tela inicial, selecione o recurso criado no passo anterior.

2. Após ter selecionado o recurso, clique em **Classify Text**, 
e após em **Analyse sentiment and mine opinions**. 

3. Em **Select text language**, mantenha o idioma inglês

4. Em **Select your Azure resource (Free tier (F0) recommended)**, selecione o recurso criado na etapa anterior

5. Em **Enter your own text, upload a file, or use one of our sample texts**, Informe os comnetários que encontram-se no diretório **inputs**.

6. Concorde com termos informando que haverá custos, e clique no botão **Run**.

7. Aguarde o término da análise.

## Análise dos resultados

Os resultados podem ser visualizados pelo arquivo json que encontra-se no diretório **outputs**.

No resultado, pode-se ver que há uma variação de opiniões entre 
positivo e negativo, aonde gostaram do serviço oferecido, 
ou, não gostaram por alguma informação que não foi passada de antemão.

Outros setores podem utilizar este resultado para melhorarem seus
processos, como por exemplo, o **setor de Marketing**, para a criação de campanhas; ou o **setor de criação de conteúdo**, para melhorar as informaçãoes que são exibidas sobre os produtos.

## Finalização do laboratório

Não se esqueça de remover os recursos que não forem uitlizados,
para deste modo, não gerarem custos adicionais.

## Referência bibliográfica

Os comentários foram extraídos do dataset que encontra-se em **https://nijianmo.github.io/amazon/index.html#subsets**.
