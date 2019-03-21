Config.cs kann in einem Projekt bunutzt werden um 
eine Konfigurationsdatei z.B. Config.xml per XmlSerializer
die Werte in lokale Variable ein.

Beispiel:
  Config config = Config.GetInstance("Config.xml");

  _connectionString = config.ConnectionString;
  _caption = config.Caption;
    