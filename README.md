☕ Criando e Executando um Código Java no Bloco de Notas via CMD
Este projeto/documentação tem como objetivo ensinar de forma simples, prática e direta como criar um programa em Java utilizando o Bloco de Notas (Notepad) e executá-lo pelo Prompt de Comando (CMD) do Windows.

É uma introdução perfeita para quem está começando na linguagem Java e deseja aprender a executar seus primeiros códigos sem IDEs como Eclipse ou IntelliJ.

🧾 Passo a Passo Resumido
1️⃣ Escrevendo o Código Java
Abra o Bloco de Notas (ou qualquer editor de texto simples).

Escreva seu código Java básico, por exemplo:

java
Copiar
Editar
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Olá, mundo!");
    }
}
Salve o arquivo com o nome da classe e extensão .java
➤ Exemplo: HelloWorld.java
⚠️ Atenção: salve como "Todos os Arquivos", não como .txt.

2️⃣ Compilando e Executando no CMD
Abra o CMD (Prompt de Comando).

Navegue até a pasta onde salvou o arquivo:

bash
Copiar
Editar
cd C:\Users\SeuUsuario\Desktop\ProjetosJava
Compile o código com o javac:

bash
Copiar
Editar
javac HelloWorld.java
Execute o programa compilado:

bash
Copiar
Editar
java HelloWorld
💡 O terminal irá exibir: Olá, mundo!

🔧 Pré-requisitos
Ter o Java JDK instalado

Variável de ambiente JAVA_HOME configurada

Comandos javac e java funcionando no terminal

📚 O que foi abordado nos slides
✅ O que é o Bloco de Notas e para que serve no desenvolvimento

✅ Como estruturar a classe Java corretamente

✅ Como salvar e nomear um arquivo .java

✅ Como abrir e usar o terminal (cmd)

✅ Comandos básicos javac e java

✅ Possíveis erros e como evitá-los

👨‍🏫 Autor
Leandro Filipy de Lima (Sigma Boy)
📘 Estudante de Desenvolvimento de Sistemas
💻 Apaixonado por Java e lógica de programação
🎯 Foco em práticas simples e eficientes

📋 Licença
Este conteúdo é de uso educacional e pode ser compartilhado, adaptado e reutilizado para fins de ensino, revisão e orientação de iniciantes.

