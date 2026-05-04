
# _FirmwareManagement

UserDemand for automation of the Firmware Management  

## Driver

Replacement of ComarchOSS  

## Scope

**High Level Process:**  
<p align="center">
  <img src="./input/diagrams/newFirmware.png" alt="High Level Processes" width="600"/>
</p>  

**Detailed Requirements:**  
See [detailed list of requirements](../../issues) in the issues section.  

     Hier wäre ein konkreterer Link mit den Labels, welche die high level Anforderungen kennzeichnen, sinnvoller  

## Components

The following components are required for implementing the _FirmwareManagement UserDemand.  

### New Applications and Tools

**p1FirmwareManager (Interface Stream):**  
Autonomous roll-out of firmware releases.  
Documenting planned activities and their status in TSM.  

**FirmwareManagementGui (Tools Stream):**  
Definition of groups of devices.  
Definition of ticket templates.  
Association of firmware releases with groups of devices and ticket templates.  

### To be updated Applications/Tools

**Gloria (? Stream):**  
Interface to p1FirmwareManager for informing about new firmware approvals.  

### Dependencies on on-going Implementations

**TSM (? Tools):**  
Interface for creating, updating and closing of tickets.  
