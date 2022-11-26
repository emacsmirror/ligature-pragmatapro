ligature-pragmatapro.el: PragmataPro support for ligature.el
============================================================

``ligature-pragmatapro.el`` provides pre-baked `ligature.el`_
configuration for the PragmataPro_ programming font.

Support is configured for all programming modes, but not enabled by
default. In the simplest configuration, simply enable
`global-ligature-mode`:

.. code:: elisp

  (require 'ligature-pragmatapro)
  (global-ligature-mode)

To be more selective, just use mode hooks:

.. code:: elisp

  (add-hook 'haskell-mode-hook 'ligature-mode)

For even more advanced custom configuration, the full list of RX
ligatures is available in `ligature-pragmatapro-ligatures`.

This package is fully documented in the source and maintained through MELPA:

https://melpa.org/#/ligature-pragmatapro

.. _ligature.el: https://github.com/mickeynp/ligature.el
.. _PragmataPro: https://fsd.it/shop/fonts/pragmatapro/
