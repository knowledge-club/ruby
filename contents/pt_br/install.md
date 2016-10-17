# Como instalar o Ruby

Escolha seu sistema operacional
- [MacOS](#macos)
- [Ubuntu](#ubuntu)
- [Windows](#windows)

## Como instalar o Ruby no MacOS <a name="macos"></a>

### Instalando Rbenv

- Instalando o Rbenv
```bash
$ brew update
$ brew install rbenv
```

### Instalando o Ruby

- Lista todas as versões disponíveis do Ruby:
```bash
$ rbenv install -l
```

- Instala a versão especificada (em 10-11-2016 o Ruby está na versão 2.3.1):
```bash
$ rbenv install 2.3.1
```

- Boa! E agora, digite `irb` (é de `interactive ruby shell`) no seu console e SINTA A MÁGICA!
```bash
$ irb
irb(main):001:0> _
```

E agora você pode seguir para o seu [primeiro comando](404_pt-br.md) no irb ou [voltar](../../README_pt-br.md) para o README!

## Como instalar o Ruby no Ubuntu <a name="ubuntu"></a>

### Instalando o Rbenv

Pode não parecer, mas a melhor maneira de instalar o ruby no seu computador é com um gerenciador de versões. Para fazer isso, vamos usar o Rbenv porque ele é muito fácil de usar

Apenas siga as instruções! To dos os comandos abaixo devem ser digitados no seu Console

- Clone o rbenv na pasta ~/.rbenv.
```bash
$ git clone https://github.com/rbenv/rbenv.git ~/.rbenv
```

- Adicione ~/.rbenv/bin ao seu $PATH para acessar o rbenv da linha de comando.
```bash
$ echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
```
- Reinicie seu terminal para que as configurações feitas no PATH sejam aplicadas
```bash
source ~/.bashrc
```
- Agora veja se o Rbenv foi instalado corretamente
```bash
$ type rbenv
#=> "rbenv is a function..."
```

### Instalando o Ruby

- Lista todas as versões disponíveis do Ruby:
```bash
$ rbenv install -l
```

- Instala a versão especificada (em 10-11-2016 o Ruby está na versão 2.3.1):
```bash
$ rbenv install 2.3.1
```

- Digite `irb` (é de `interactive ruby shell`) no seu console e estará funcionando
```bash
$ irb
irb(main):001:0> _
```

E agora você pode seguir para o seu [primeiro comando](404_pt-br.md) no irb ou [voltar](../../README_pt-br.md) para o README!

# Como instalar o Ruby no Windows <a name="windows"></a>

- Vamos a página de [downloads](http://rubyinstaller.org/downloads/) do [RubyInstaller](http://rubyinstaller.org)

- Na sessão *RubyInstallers*, baixe a versão mais recente para o seu computador, respeitando a arquitetura do seu sistema operacional (32 ou 64 bits). No dia de hoje (11/10/2016), as versões mais recentes são as seguintes:

  ![RubyInstaller](../../images/rubyinstaller.png)

- Respectivamente, são as versões para 32 e 64 bits, baixe a correspondente ao seu sistema operacional, ao terminar o download, execute o arquivo

- Faça a instalação normalmente usando o protocolo NNF (Next, Next, Finish) que acompanha todas as versões do Windows

- Na seguinte tela, marque as opções **Add Ruby executables to your PATH** e **Associate .rb and .rbw files with this Ruby installation** e prossiga com a instalação

  ![RubyInstallerSetup](../../images/rubyinstallersetup.png)

- Ao finalizar, no seu menu iniciar, na pasta Ruby, execute o Interactive Ruby e utilize o terminal para testar os PODERES do ruby!

E agora você pode seguir para o seu [primeiro comando](404_pt-br.md) no irb ou [voltar](../../README.md) para o README!
