# Realce de Foco #

* Autores: Takuya Nishimoto, Karl-Otto Rosenqvist
* Baixe a [versão estável][2]
* Baixe a [versão de desenvolvimento][1]

Ao desenhar um retângulo colorido, este complemento possibilita usuários de
baixa visão, educadores de visão normal ou desenvolvedores, acompanhar a
localização do objeto de navegação do NVDA e o objeto/controle em foco.

O complemento usa as seguintes cores:

* Retângulo verde de linha fina pontilhada tracejada mostra que o NVDA está
  no modo de navegação, e esse é o objeto de navegação.
* Retângulo fino vermelho mostra que o NVDA está no modo de navegação, e
  esse é o objeto/controle em foco.
* Retângulo grosso vermelho mostra que o NVDA está no modo de navegação, e
  esse tem juntamente o objeto de navegação e o objeto em foco que estão
  sobrepostos.
* Retângulo azul de linha grossa pontilhada indica que o NVDA está no modo
  de foco, ou seja, as teclas digitadas são passadas para o controle.

Para alternar o rastreamento de objetos, pressione NVDA+Alt+P. Você pode
atribuir outros comandos (gestos) usando o diálogo Definir Comandos. Observe
que ele funciona com o NVDA 2018.3 ou posterior. Caso contrário, você deve
desativar ou desinstalar o próprio complemento para desativar o rastreamento
de objetos.

Quando a categoria Realce de Foco do diálogo de Configurações do NVDA
estiver disponível, os seguintes itens podem ser usados.

* Tornar o modo de foco o padrão: Esta caixa de seleção está ativada por
  padrão. Quando está desmarcada, esse complemento se comporta da mesma
  forma que a versão 5.6 ou versões anteriores, ou seja, se o modo de
  navegação não estiver disponível para um aplicativo, o foco será mostrado
  usando o retângulo vermelho grosso.
* Foco no modo de foco, Foco no modo de navegação, Navegador de objeto: Cada
  um desses grupos contém Cor, Espessura e Estilo.

    * Cor: este campo de edição permite digitar o código de cores HTML, ou
      seja, número hexadecimal de seis caracteres. Por exemplo, "ffffff" é
      branco, "ff0000" é vermelho, e assim por diante. Observe que "000000"
      não pode ser usado.
    * Espessura: Este campo de edição permite digitar a espessura da
      caixa. Você pode inserir um valor entre 1 e 30.
    * Estilo: As opções são Sólido, Traço, Ponto, Traço e ponto, e Traço
      ponto ponto.

* Restaurar padrões: Esse botão permite redefinir as configurações para os
  padrões originais.

## Mudanças na 6.3 ##

* Traduções novas e atualizadas.
* Corrigido o problema em que os estilos de traço do foco (no modo de
  navegação) e o navegador de objeto não podem ser alterados.
* Corrigido o problema em que o botão 'Cancelar' do painel de configuração
  não funciona depois que o botão 'Restaurar padrões' é pressionado.

## Mudanças na 6.2 ##

* Traduções novas e atualizadas.
* Agora você pode ativar e desativar o rastreamento de objetos usando o
  NVDA+Alt+P. Karl-Otto Rosenqvist contribuiu para isso.

## Mudanças na 6.1 ##

* Traduções novas e atualizadas.
* Soluciona [o problema](https://github.com/nvdajp/focusHighlight/issues/14)
  com as últimas versões de desenvolvimento do NVDA.
* A categoria Realce de Foco do diálogo de Configurações do NVDA está
  disponível. Observe que ele funciona apenas com o NVDA 2018.3 ou
  posterior.
* [Discussões sobre a personalização de
  cores](https://github.com/nvdajp/focusHighlight/issues/3)
* [Discussões sobre 'Tornar o modo de foco o
  padrão'](https://github.com/nvdajp/focusHighlight/issues/13)

## Mudanças na 6.0 ##

* Traduções novas e atualizadas.
* Soluciona [o problema](https://github.com/nvdajp/focusHighlight/issues/13)
  referente ao modo de navegação.
* Desde esta versão, se o modo de navegação do NVDA não estiver disponível
  para um aplicativo, sempre será mostrado que o NVDA está em modo de foco
  do aplicativo, em vez de usar o retângulo grosso vermelho.
* A espessura da linha que representa o modo de foco foi reduzida para
  metade.

## Mudanças na 5.6 ##

* Traduções novas e atualizadas.
* Soluciona o problema de compatibilidade com o NVDA instantâneo (snapshot)
  alpha-16682.

## Mudanças na 5.5 ##

* Soluciona o problema com o NVDA 2018.4 e os navegadores web
  Firefox/Chrome.

## Mudanças na 5.4 ##

* Traduções novas e atualizadas.
* Soluciona [o problema](https://github.com/nvdajp/focusHighlight/issues/11)
  relacionado à compatibilidade de versão.

## Mudanças na 5.3 ##

* Traduções novas e atualizadas.
* Soluciona [o problema](https://github.com/nvdajp/focusHighlight/issues/10)
  relacionado ao navegador Google Chrome e ao modo de suspensão do
  aplicativo.

## Mudanças na 5.2 ##

* Traduções novas e atualizadas.

## Mudanças na 5.1 ##

* Removida a saída de log de depuração.

## Mudanças na 5.0 ##

* Os indicadores do objeto de navegação e do modo de foco foram alterados.
* Múltiplos monitores são suportados.
* Agora ele usa a tecnologia GDI Plus para desenho.

## Mudanças na 4.0 ##

* Oculta retângulo se o aplicativo atual estiver em modo dormir.

## Mudanças na 3.0 ##

* Corrigido problema em relação à caixa de combinação expandida.
* Consertados problemas com a barra de tarefas do Windows.
* Capacidade de indicar o modo de foco.

## Mudanças na 2.1 ##

* Traduções novas e atualizadas.

## Mudanças na 2.0 ##

* A ajuda do complemento está disponível no gestor de complementos.

## Mudanças na 1.1 ##

* Alterado retângulo do objeto de navegação para uma linha entalhada.
* Concertado problema com "Recarregar plug-ins".

## Mudanças na 1.0 ##

* No Internet Explorer 10 e no Skype para Windows 8, consertado um problema
  com o navegador de objetos.
* Versão inicial.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=fh-dev

[2]: https://addons.nvda-project.org/files/get.php?file=fh
