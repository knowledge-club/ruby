# Como instalar o Ruby no Ubuntu

## Instalando o Rbenv

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

## Instalado o Ruby

Por favor, preste atenção, altas dificuldades a frente!

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
