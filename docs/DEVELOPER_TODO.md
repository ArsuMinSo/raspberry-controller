# Raspberry Controller Project: Developer To-Do List

This checklist will guide you step-by-step through building your enterprise-grade Raspberry Controller app.

## Initial Setup

- [X] Set up Python environment (virtualenv or conda)
- [ ] Initialize Git repository and commit initial structure

## Backend Development

### Backend Development

- [ ] Research and select libraries for SSH/SFTP (e.g., paramiko)
  - [ ] Review paramiko documentation and examples
  - [ ] Explore alternatives if needed (asyncssh, fabric)
- [ ] Plan and design database schema for device info
  - [ ] Identify required fields (serial, IP, status, last seen, hostname, etc.)
  - [ ] Create ER diagram or schema draft
- [ ] Set up database integration
  - [ ] Choose database (SQLite for local, PostgreSQL for enterprise)
  - [ ] Implement connection logic and configuration
  - [ ] Create migration or setup scripts
- [ ] Implement device discovery
  - [ ] Research network scanning methods (e.g., nmap, scapy, socket)
  - [ ] Write code to scan local network for Raspberry Pis
  - [ ] Parse and filter results for valid devices
- [ ] Implement SSH/SFTP connection and control
  - [ ] Write reusable functions/classes for SSH connection
  - [ ] Implement SFTP file transfer logic
  - [ ] Add device control commands (reboot, run script, etc.)
- [ ] Integrate backend modules
  - [ ] Connect discovery, database, and SSH logic
  - [ ] Ensure smooth data flow between components
- [ ] Add logging and error handling
  - [ ] Set up logging for all backend modules
  - [ ] Implement robust error handling and reporting
- [ ] Write unit and integration tests for backend
  - [ ] Test device discovery
  - [ ] Test database operations
  - [ ] Test SSH/SFTP connections and commands

## Frontend/GUI Development

- [ ] Decide on GUI type (web: React + Flask/Django, or desktop: PyQt/Electron)
- [ ] Set up frontend project structure
- [ ] Design basic UI for device list and controls
- [ ] Connect frontend to backend (API or direct calls)
- [ ] Implement device management features (add, edit, remove, control)
- [ ] Add authentication (optional, for enterprise)
- [ ] Write tests for frontend components

## DevOps & Documentation

- [ ] Create scripts for setup and deployment
- [ ] Add documentation in `docs/` and update README
- [ ] Set up CI/CD (optional, for enterprise)
- [ ] Review code for best practices and scalability

## Final Steps

- [ ] Test the full application end-to-end
- [ ] Polish UI and UX
- [ ] Prepare for release/deployment
