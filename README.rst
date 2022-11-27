ligature-pragmatapro.el: PragmataPro support for ligature.el
============================================================

``ligature-pragmatapro.el`` provides pre-baked `ligature.el`_
configuration for the PragmataPro_ programming font.

Support is configured for all programming modes by calling
`ligature-pragmatapro-setup`, then enabling `ligature`:

.. code:: elisp

  (ligature-pragmatapro-setup)
  (global-ligature-mode)

To be more selective, just use mode hooks:

.. code:: elisp

  (ligature-pragmatapro-setup)
  (add-hook 'haskell-mode-hook 'ligature-mode)

For even more advanced custom configuration, all PragmataPro ligatures
are available in `ligature-pragmatapro-ligatures` to be used directly:

.. code:: elisp

  (ligature-set-ligatures 'prog-mode ligature-pragmatapro-ligatures)

This package is fully documented in the source and maintained through MELPA:

https://melpa.org/#/ligature-pragmatapro

.. _ligature.el: https://github.com/mickeynp/ligature.el
.. _PragmataPro: https://fsd.it/shop/fonts/pragmatapro/
