# Como instalar o Ruby no MacOS

## Installing Rbenv

- É tãããããão fácil! Dê uma olhada em como fazer essa instalação no [Ubuntu](how_to_install_on_ubuntu.md) e compare!
```bash
$ brew update
$ brew install rbenv
```

## Instalando o Ruby

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
