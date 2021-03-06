# Focus Highlight #

* Autor: Takuya Nishimoto
* Baixar [versão estável][2]
* Baixar [versão de desenvolvimento][1]

Ao desenhar um rectângulo colorido, este extra permite que os utilizadores
com deficiência visual, educadores com visão ou desenvolvedores detectem a
localização do objecto do navegador nvda e o objeto / control focado.

As seguintes cores são usadas por este extra:

* Green thin dashed-dotted line rectangle shows NVDA is in browse mode, and
  this is the navigator object.
* Red thin rectangle shows NVDA is in browse mode, and this is the focused
  object/control.
* Red thick rectangle shows NVDA is in browse mode, and this is both the
  navigator object and the focused object which are overlapping.
* Blue thick dotted line rectangle indicates NVDA is in focus mode, i.e.,
  key types are passed to the control.

To disable object tracking, disable or uninstall the addon.

When Focus Highlight category of NVDA Settings dialog is available,
following items can be used.

* Make focus mode the default: This checkbox is enabled by default. When it
  is unchecked, this add-on behaves same as version 5.6 or previous
  versions, i.e., if browse mode is not available for an app, the focus is
  shown using the thick red rectangle.
* Focus in focus mode, Focus in browse mode, Navigator object: Each of these
  groups contains Color, Thickness, and Style.

    * Color: This edit field allows you to type the HTML color code, i.e.,
      six-character hexadecimal number. For example, "ffffff" is white,
      "ff0000" is red, and so on. Note that "000000" can not be used.
    * Thickness: This edit field allows you to type the thickness of the
      box. You can enter a value between 1 and 30.
    * Style: The choices are Solid, Dash, Dot, Dash dot, and Dash dot-dot.

* Restore defaults: This button allows you to reset your settings to their
  original defaults.

## Changes for 6.1 ##

* Traduções novas e outras actualizadas.
* Addresses [the issue](https://github.com/nvdajp/focusHighlight/issues/14)
  with the latest development versions of NVDA.
* Focus Highlight category of NVDA Settings dialog is now available. Note
  that it works only with NVDA 2018.3 or later.
* [Discussions regarding customizing
  colors](https://github.com/nvdajp/focusHighlight/issues/3)
* [Discussions regarding 'Make focus mode the
  default'](https://github.com/nvdajp/focusHighlight/issues/13)

## Changes for 6.0 ##

* Traduções novas e outras actualizadas.
* Addresses [the issue](https://github.com/nvdajp/focusHighlight/issues/13)
  regarding the browse mode.
* Since this version, if the browse mode of NVDA is not available for an
  application, it is always shown that NVDA is in focus mode for the
  application, rather than using the red thick rectangle.
* The thickness of the line representing the focus mode has been reduced to
  half.

## Alterações para 5.6 ##

* Traduções novas e outras actualizadas.
* Soluciona o problema de compatibilidade com o snapshot do NVDA
  alpha-16682.

## Alterações para 5.5 ##

* Soluciona o problema do NVDA 2018.4 com os navegadores da Web Firefox /
  Chrome.

## Alterações para 5.4 ##

* Traduções novas e outras actualizadas.
* Resolve [o problema](https://github.com/nvdajp/focusHighlight/issues/11)
  respeitante à compatibilidade da versão

## Alterações para 5.3 ##

* Traduções novas e outras actualizadas.
* Resolve [o problema](https://github.com/nvdajp/focusHighlight/issues/10)
  respeitante ao Chrome e à suspensão da aplicação.

## Alterações para 5.2 ##

* Traduções novas e outras actualizadas.

## Alterações para 5.1 ##

* Removida a saída do log de depuração.

## Alterações para 5.0 ##

* Os indicadores do objeto do navegador e do modo de foco foram alterados.
* São suportados vários monitores.
* Agora, usa-se a tecnologia GDI Plus para desenho.

## Alterações para 4.0 ##

* Esconder o rectângulo se o aplicativo actual estiver no modo de suspensão.

## Alterações para 3.0 ##

* Corrigido problema em relação à caixa de combinação expandida.
* Corrigido problema com o gestor de tarefas do Windows.
* Capacidade de indicar o modo de foco.

## Mudanças para 2.1 ##

* Traduções novas e outras actualizadas.

## Mudanças para 2.0 ##

* A ajuda do extra ficou disponível no gestor de extras.

## Alterações para 1.1 ##

* Alterado o rectângulo do objeto do navegador para uma linha irregular.
* Corrigido problema com 'Recarregar plugins'.

## Alterações para 1.0 ##

* No Internet Explorer 10 e no Skype no Windows 8, reparado um problema com
  o objeto do navegador.
* Versão inicial.


[[!tag dev stable]]

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=fh-dev

[2]: https://addons.nvda-project.org/files/get.php?file=fh
