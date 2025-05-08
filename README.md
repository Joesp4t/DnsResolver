# DnsResolver

✅ Útil para usar em CTF, para estudantes de programação, redes ou quem quer entender mais sobre como funciona a internet.

👉 Ele funciona da seguinte forma: você digita o site (Exemplo: www.Site.com) e o programa retorna apenas o IP correspondente de uma forma rápida.

🚀 O DnsResolver é um programa simples em C que descobre o endereço IP de qualquer site!
Diferente do comando “ Host ” do Linux, esse script tem o seu tempo de execução muito mais rápido.



---> Processo para compilar o script em C, como o `DnsResolver_v01.c`, siga os passos abaixo:

1. **Verifique se você tem um compilador C instalado**: Para sistemas Unix/Linux, o GCC (GNU Compiler Collection) é uma escolha comum. No Windows, você pode usar MinGW ou o compilador do Visual Studio.

2. **Abra o terminal (ou Prompt de Comando no Windows)**.

4. **Compile o arquivo usando o GCC**. O comando para compilar é o seguinte:
  Bash (Terminal Linux)
   gcc DnsResolver.c -o DnsResolver
   ```
   Aqui, `-o DnsResolver` especifica o nome do executável que será gerado. Você pode escolher qualquer nome que desejar.

5. **Execute o programa**. Após a compilação, você deve ver um novo arquivo chamado `DnsResolver` (ou o nome que você escolheu). Para executar:
   - No Linux ou macOS:
    Bash (Terminal Linux)
    #./DnsResolver
     
   - No Windows:
    cmd (Terminal do Windows)
     #DnsResolver.exe
     ```

Se houver algum erro durante a compilação, você verá mensagens no terminal que podem ajudá-lo a identificar e corrigir problemas no seu código.
