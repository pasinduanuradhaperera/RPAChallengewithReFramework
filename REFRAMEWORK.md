go back to [README.md](README.md)

**REFramework** (Robotic Enterprise Framework) is the official UiPath template for building **production-grade**, robust, scalable automations.

#### Why REFramework is Awesome (Good Things)

| Benefit                        | Explanation                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| Transactional processing      | Handles items one by one with retry logic                                   |
| Built-in retry mechanism      | Automatically retries failed items (configurable)                          |
| Exception handling            | Separates Business Rule Exceptions vs Application Exceptions               |
| Logging & Reporting           | Full integration with Orchestrator Queues, Assets, Logging                 |
| Config file                   | All selectors, URLs, credentials stored in Config.xlsx / Orchestrator Assets |
| State Machine structure       | Clear states: Initialization → Get Transaction → Process Transaction→ End Process     |
| Easy to maintain & extend     | Perfect template for real enterprise projects                               |

Even for a simple challenge like rpachallenge.com, using REFramework teaches you **best practices from day one**.

---

### Project Structure (Standard REFramework)
```
├── Data
│   ├── Input
│   │   └── challenge.xlsx           ← Downloaded Excel (10 rows)
│   └── Output (optional)
|   └── Config.xlsx                  ← All settings (input_File, Sheet_Name, WebsiteURL, etc.)
├── Framework
│   ├── InitAllApplications.xaml
│   ├── GetTransactionData.xaml
│   ├── Process.xaml
│   ├── SetTransactionStatus.xaml
│   └── ... (standard files)
├── Main.xaml                        ← Entry point (State Machine)
├── Project.json
└── README.md (this file)
```

