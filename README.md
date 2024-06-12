<h1 align="center">🔖 Hchat - Chat Redesign</h1>

### First version which will be modified in the future

**Version 1.0**

**⚠️ - Dependencies**
- [FiveM Chat Default](https://github.com/citizenfx/cfx-server-data/tree/master/resources/%5Bgameplay%5D/chat)

**🛠 - Install**
- Install the script (``Hchat-main``)
- Place it in your FiveM resource folder and delete: -main
- ensure ``Hchat`` anywhere after the default ``chat`` resource in your **server.cfg**.

### Chat FiveM redesign by Hugoo

**Other Information**
the current script does not present any modification impacting the ``chat`` dependency, for the moment my script only allows you to modify the visual interface of the default chat script.
But also, for the moment I have provided a **command** allowing you to clear the chat:
```lua
RegisterCommand('clear', function() -- Simple command clear
 TriggerEvent('chat:clear')
end)
```
In game you just have to do ``/clear`` to clear the chat
