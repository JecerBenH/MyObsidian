---
sticker: emoji//270d-fe0f
---
1. **Use Case Diagram**:
    - Identify different actors (LwM2M Client, LwM2M Server, File Server).
    - Outline the interactions between these actors and the functionalities each can perform (e.g., LwM2M Client registering with the Server, requesting firmware updates, etc.).
2. **Class Diagram**:
    
    - Define the classes involved in the infrastructure (e.g., LwM2M Client, LwM2M Server, File Server, Firmware, Update Manager, etc.).
    - Show their relationships, attributes, and methods. For instance, the LwM2M Client might have attributes like `deviceID`, `firmwareVersion`, etc.
3. **Sequence Diagram** (for FOTA update process):
    
    - Illustrate the sequence of messages exchanged between the LwM2M Client, LwM2M Server, and File Server during a firmware update.
    - Detail the steps involved in the update process such as request, authorization, firmware retrieval, and update execution.
4. **Component Diagram**:
    
    - Display the components of the system and their relationships (LwM2M Client, LwM2M Server, File Server).
    - Highlight how these components interact and the interfaces they expose.
5. **Deployment Diagram**:
    
    - Show how the components are deployed across physical nodes (hardware or software) like devices, servers, etc.
    - Illustrate the connections and communication channels between the LwM2M Client, LwM2M Server, and File Server.

When creating these diagrams, consider using UML tools like Lucidchart, draw.io, or Visual Paradigm, which provide templates and symbols specific to UML. Start by outlining the major components and their relationships before delving into the specifics of each interaction.


## Use cases : 
- Device registration to server 
- Device Connection to server
