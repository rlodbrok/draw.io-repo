# draw.io
draw.io libraries, templates and samples

## LibRagnar2.xml
RAW link: https://raw.githubusercontent.com/rlodbrok/draw.io/master/LibRagnar2.xml 

### Sample of shapes
Preferred:
* Diagram style DFD Gane & Sarson;
* Shapes using Archimate symbols;
* Flows include extensive flexibility and annotation.
![DFD sample components](https://github.com/rlodbrok/draw.io/raw/master/DFD%20sample.png)

### Flow details
IMPORTANT: Data Flow Diagrams the arrow represents the direction of the data-flow, NOT the direction for network communication (communication can have multiple steps, go back/forth with different intervals). For network handshake and detailed network communication you use other diagrams like: time-sequence / flow-control.

#### Can contain:
* Arrow direction indicates data flow direction!
* Mid-arrow information provides context: PUSH/PULL, protocol(s), ...
* Arrow ends can contain optional properties: network ports for (S)ource & (D)estination, IP addresses, ...
* Alternative adapter designations (abbreviated): (I)nitiator, (S)erver, (P)rovider, ...

#### Protocol designation examples
Pattern: Network Protocol / Application Protocol / File Formats
* HTTPS / REST / JSON
* HTTP / SOAP / XML
* SAPRFC / ALE / IDOC
