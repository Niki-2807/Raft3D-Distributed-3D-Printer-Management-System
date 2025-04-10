# Raft3D-Distributed-3D-Printer-Management-System

**Raft3D** is a distributed system for managing 3D printers, filaments, and print jobs, powered by the **Raft Consensus Algorithm**. It ensures strong consistency across multiple nodes without relying on an external database.

---

## Key Highlights

- **Raft-based Consensus**: Ensures leader election and state replication.
- **Printer Management**: Register and manage 3D printers.
- **Filament Tracking**: Monitor and update filament inventory.
- **Print Job Scheduling**: Track print job statuses and progress.
- **No External Database**: Uses Raft FSM for durable in-memory state.
- **Fault Tolerant**: Seamlessly handles leader failures and re-elections.
