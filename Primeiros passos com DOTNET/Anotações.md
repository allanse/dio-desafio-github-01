Aulas:

1. O que é .Net?

   - Conhecendo o framework

     - Anos 70 - Basic;

     - Anos 80 - Parceria com IBM: DOS;

     - 1997 - Visual Studio 97;

     - 1998 - Visual Studio 6;

     - 1999 - Scott Guthrie criador do ASP+ (depois ASP Next)

     - 1999 - Inicio da criação do C# - Acordo com SUN para MS não usar o JAVA;

     - 2000  - .NET 1.0 - Inicialmento chamado Next Gereration Windows Services (NGWS)

     - 2001 - Miguel de Icaza inicia projeto Mono;

     - 2002 - Visual Sutido .NET com C# 1.0;

     - 2003 - .NET 1.1 - CLR 2;

     - 2005 - Visual Studio 2005 - .Net 2.0 e C# 2.0;

     - 2007-2008 - .NET 3.5 - C# 3.0 VS 2008, Silverlight, WPF e WCF.  Time para ASP .NET MVC. Inicio do MS Azure;

     - 2010 - .NET 4 - C# 4.0 - VC 2010 e F#. Lançamento Azure. Anders Hejlsberg começa Typescript;

     - 2011 - Miguel de Icaza inicia o Xamarin;

     - 2012 - NET 4.5 - C# 5.0 - VS 2012 - Lançamento do Typescript;

     - 2013 - .Net 4.5.1 - VS 2013 - Roslyn novo compilador do C# feito em C#;

     - 2013 - Frente JS, ASP .NET MVC, Web API e SignalR;

     - 2014 - Satya Nadella - CEO - Foco em Nuvem. Criada a .NET Foundation;

     - 2014 - Windows Azure vira MS Azure e introdução do ASP .NET vNext , futuro ASP .NET Core;

     - 2015 - .NET 4.6 - C# 6.0 - VS 2015 - Lançamento do VS Code;

     - 2016 - Compra da Xamarin pela MS e add como parte da stack. Lançado VS for Mac;

     - 2016 - Lançamento do .NET Core 1.0 - open source e multi-plataforma;

     - 2017 - .Net Framework 4.7 - C# 7.0 - VS 2017. - .NET Core 2.0 - C# 7.0;

     - 2019 - .Net Framework 4.8 - C# 7.3 - VS 2017. - .NET Core 3.0 - C# 8.0;

     - 2020 - .NET Framework  está pronto e não será evoluído. Lançamento do .NET 5;

       

   - Como e aonde usar o .NET

     - O que é? Infraestrutura para desenv de software made by MS;

     - Roda em : .NET Core, .NET Framework, Mono e UWP (Universal Windows Plataform)

     - Como? .NET Standard Library. Common Infrastructure;

     - Cada implementação usa um ou mais .NET Runtimes:

       - .NET Core: CoreCLR ou CoreRT;
       - .NET Framework: CLR;
       - Mono: Mono Runtime;
       - UWP: .NET Native;

     - Suporta 3 linguagens: C#, F# e VB;

     - Onde?: "Anywhere", Desktop, WEB, Cloud, Mobile, Gaming, IoT e AI

       - Ferramentas: VS, VS for MAC,l VS Code, Command Line Interface;

     - Quem usa .NET: Vidalink, Licks Attorneys, Casas Bahia, Saraiva, Unimed, Azul, Gol, Marabraz, Stack overflow, Microsoft;

     - Links Uteis:

       - Download .NET: https://dotnet.microsoft.com/download
       - Documentação do .NET: https://docs.microsoft.com/en-us/dotnet/
       - .NET Foundation: https://dotnetfoundation.org/
       - Visual Studio: https://visualstudio.microsoft.com/pt-br/vs/
       - Visual Studio for Mac: https://visualstudio.microsoft.com/pt-br/vs/mac/
       - Visual Studio Code: https://code.visualstudio.com/
       - Microsoft Azure: https://azure.microsoft.com/pt-br/
       - Mono Project: https://www.mono-project.com
       - Xamarin: https://dotnet.microsoft.com/apps/xamarin

       

2. Iniciando com .NET

   - Preparando o ambiente:
      - Instalar o SDK do DOTNET na versão corrente (5.0.402 em Nov/21);
      - Instalar o VS Code: https://code.visualstudio.com/
        - ADD plugins C#, C# extensions;

   - Conhecendo o CLI do .NET:

      - dotnet --help: exibe os commandos possíveis de usar com a CLI;
      - explicação breve sobre alguns comandos mais utilizados:
         - add, build, nuget, publish, restore, run, test;
      - dotnet new --help: help do  comando new;

   - Criando uma aplicação console:

      - dotnet new console -n DigitalInnovationOne;
      - cd DigitalInnovationOne;
      - explorer . ;
      - code . ;
      - dotnet restore;
      - dotnet build;
      - Explicação sobre o program.cs;
      - dotnet run;
      - Explicação sobre criação de um novo terminal;
      - Alteração no código do program.cs para ter um laço de repetições;
      - Explicação sobre o DOTNET RUN - Sempre deve ser executado na mesma pasta onde está o csproj;

      

3. Conhecendo o C#

   - O que é e como funciona o C#:

     - O que é: 

       - linguagem desenvolvida no inicio dos anos 1990;
       - elegante, orientada a objeto e fortemente tipada;
       - sintaxe similar a C, C++ ou Java;
       - Suporta conceitos de encapsulamento, herança e polimorfismo (OO);
       - Programas são executados no .NET : CLR e Conjunto unificados de bibliotecas de classes;
       - Compilador é o Roslyn (feito em C# e open source);

     - Como funciona:

       - Codigo-fonte é compilado em uma linguagem intermediária (IL);
       - Os códigos e recursos de IL são armazenados em um executável chamado assembly e geralmente são .exe ou .dll;
       - Ao executar o build esses arquivos em linguagem intermediária são gerados;
       - Quando o programa C# é executado o assembly é carregado na CLR e em seguida é feita a conversão do IL para linguagem de máquina via JIT;
       - Serviços do CLR:
         - Garbage Collector;
         - Exception Handler
         - Resources Manager;
       - Imagem explicando o funcionamento do C# :https://qph.fs.quoracdn.net/main-qimg-9e558bc2d949ec048fcaef8ef458c024;
       - Possuí uma extensa biblioteca de classes que podem ser utilizadas nos projetos;

       

   - Estrutura de programa:

     - organizados em :

       - programas;
       - namespaces;
       - tipos;
       - membros;
       - assemblies;

     - Programas:

     - Exemplo prático;

       

4. Conhecendo variáveis e Instruções:

5. Classes e objetos essenciais em C#:

6. Trabalhando com structs, interfaces e enums:

7. Uma síntese do que é .NET: