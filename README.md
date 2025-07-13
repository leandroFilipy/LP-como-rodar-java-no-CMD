☕ Como Criar e Executar um Código Java no Bloco de Notas usando o CMD
Este projeto tem como objetivo demonstrar de forma prática e clara como criar um código Java no Bloco de Notas e executá-lo utilizando o Prompt de Comando (CMD).
Uma excelente introdução para quem está iniciando no mundo da programação com Java! 🚀

📄 Etapas do Processo
🧱 1. Criando o Arquivo .java
Abra o Bloco de Notas no Windows 📝

Escreva o seguinte código Java:

java
Copiar
Editar
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Olá, mundo!");
    }
}
Salve o arquivo com o nome da classe e a extensão .java
👉 Exemplo: HelloWorld.java
❗ Importante: selecione "Todos os arquivos" no tipo de salvamento e não como .txt.

💻 2. Compilando e Executando no CMD
Abra o Prompt de Comando (CMD) 🖥️

Acesse o diretório onde você salvou o arquivo:

bash
Copiar
Editar
cd C:\Users\SeuUsuario\Desktop\ProjetoJava
Compile o código com o comando javac:

bash
Copiar
Editar
javac HelloWorld.java
Execute o programa compilado com:

bash
Copiar
Editar
java HelloWorld
🔎 Se tudo estiver certo, aparecerá no console:

css
Copiar
Editar
Olá, mundo!
✅ Pré-Requisitos
Antes de seguir os passos, verifique se você possui:

☕ Java JDK instalado em sua máquina

🛠️ Variável de ambiente JAVA_HOME configurada

📂 Comandos javac e java funcionando no terminal

📚 Conteúdos Apresentados no Slide
O que é o Bloco de Notas como editor de código

Estrutura básica de uma classe Java

Como salvar e nomear arquivos .java

Como usar o CMD para compilar e executar

Comandos essenciais: javac e java

Principais erros de iniciantes e como evitá-los

👨‍🎓 Autor
Nome	Curso	Foco
Leandro Filipy de Lima (Sigma Boy)	Desenvolvimento de Sistemas 💻	Programação com Java ☕

📄 Licença
Este projeto foi desenvolvido com fins educacionais, sendo livre para uso, estudo e adaptação em outros projetos didáticos ou apresentações.
