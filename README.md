# Lab8-Starter

__Name__: Ryan Awal <br>
__Partner__: _None_ <br>

### How are graceful degradation and service workers related?

### Answer
Graceful degradation is about building your app with the best features first, then making sure it still works when those features aren’t available. This strongly correlates to service workers as when the network is up, they let us fetch fresh data and when it’s down, they kick in and serve saved (cached) files instead. In this way, service workers help us degrade gracefully - by automatically falling back to offline resources. This allows recipe viewing even without an internet connection.