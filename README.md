# Modern Product Management with AI Documentation

This repository outlines the product management principles employed at Keboola, with a focus on using AI to assist in technical documentation. The documentation was generated using Anthropic's Claude 3.5 Sonnet and covers the following aspects:

- Efficient documentation generation
- Enhanced technical understanding
- Clear visual communication
- Scalable documentation processes

## Overview of Product Documentation

The main document (`streaming-explanation.md`) details the Keboola Streaming service. It serves as an example of how AI can be used to create documentation that includes:

- Detailed descriptions of technical components and principles
- Options for tuning buffers (e.g., caching duration or event counts)
- Explanations of JSON parsing processes
- Detailed visual diagrams (Mermaid flowcharts) showing data flows and system logic

## Product Management Practices at Keboola

This study illustrates several practical approaches:

1. **Efficient Documentation Generation**
   - Use of AI to produce comprehensive technical documentation
   - Reduced time spent on manual documentation maintenance
   - Consistent documentation formats

2. **Technical Understanding**
   - Rapid comprehension of complex systems
   - Translation of technical details for varied audiences
   - Thorough coverage of product architecture and components

3. **Visual Communication**
   - Automated generation of system diagrams
   - Clear visualization of data flows and system interactions
   - Visual aids to support stakeholder understanding

4. **Scalable Documentation Process**
   - Fast updates to documentation as systems change
   - Standardized documentation structure and quality
   - Lower dependency on engineering resources for technical documentation

## AI Generation Process

The documentation was created using the following prompt, demonstrating how AI can be integrated into product management practices:

```
Inspect the internal/pkg/service/stream/ and investigate in more depth to uncover what 
happens to data before they are pushed to Keboola Storage. Create markdown documentation 
for the product manager, describing the Keboola Streaming service, including all components 
and principles. The documentation should cover options for tuning the buffer (e.g., how 
long data are cached—such as 30 seconds or 1,000 events) and the JSON parsing process. 
Additionally, include a detailed visual diagram (Mermaid flowchart) illustrating 
the application's inner logic, with a specific focus on how data flows through 
the components of the Keboola Streaming service. Ensure the diagram is detailed and store 
the result in @streaming-explanation.md 
```

This prompt was designed to:
1. Focus on technical understanding of the streaming service
2. Ensure comprehensive coverage of system components
3. Include practical configuration details
4. Provide clear visual representation
5. Create documentation suitable for both technical and non-technical stakeholders