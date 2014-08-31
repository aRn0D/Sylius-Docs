CurrencyContextInterface
========================

The ``CurrencyContext`` allows you to manage the currently used currency, it needs to implement the ``CurrencyContextInterface``.

+-------------------------+-------------------------------------+-------------------+
| Method                  | Description                         | Returned value    |
+=========================+=====================================+===================+
| getDefaultCurrency()    | Get the default currency            | string            |
+-------------------------+-------------------------------------+-------------------+
| getCurrency()           | Get the currently active currency   | string            |
+-------------------------+-------------------------------------+-------------------+
| setCurrency($currency)  | Set the currently active currency   | Void              |
+-------------------------+-------------------------------------+-------------------+
