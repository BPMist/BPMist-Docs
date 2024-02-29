BPMist Dictionary

We strive for specificity in our documentation by clearly distinguishing between the design/implementation phase and the execution/run-time phase. Therefore, except in marketing materials, we avoid using the term 'workflow' in isolation.

Workflow Definition: A workflow definition is the result of design, development, and implementation activities. It specifies the sequence of tasks and the governing rules for those tasks.

Example: In the workflow definition for processing an expense request, it specifies that the requester must provide a receipt and the purpose of the expense. Based on the amount, it either auto-approves requests under $100 or routes requests over $100 to a manager for review. If a receipt is missing, the workflow automatically requests one from the employee, illustrating how the process adapts based on the input provided. 

Workflow Instance: A workflow instance refers to a single occurrence of "a workflow in action", possessing a unique lifecycle. It behaves and interacts according to the guidelines and rules established by its workflow definition.

Example: When Emily submits an expense request for $150 on October 5th for a business lunch with a client, including a receipt and the purpose of the expense, this submission creates a unique workflow instance. This instance follows the predefined rules: since the amount exceeds $100, the system automatically routes her request to her manager, John, for approval. The instance will continue to evolve, tracking actions such as John's review and decision, until the expense request process is completed. This specific occurrence, with its own set of data and progression through the established process, exemplifies a workflow instance in action. Simultaneously, there could be other instances initiated by Emily or any individual within the organization, each following its unique path through the workflow as dictated by the same set of rules but with their distinct data and lifecycle


- Workflow diagram: a visual that shows all tasks, and gateways ...

- Workflow execution
- Task Sequencing Logic
- Task (task instance / executing task)
- Task definition
- Automated Task
- User task
- Gateways
- 
