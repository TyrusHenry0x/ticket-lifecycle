<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo" width="70%" />
</p>

<h1 align="center">osTicket - Ticket Lifecycle: Intake Through Resolution</h1>

<p align="center">
This guide walks you through how a ticket flows from start to finish in osTicket, giving you a clear picture of what happens at every stage of the process—from the moment a customer submits a ticket to when it's resolved and closed.
</p>

<hr>

<h2>Technologies and Tools</h2>
<ul>
  <li>Microsoft Azure (Virtual Machines/Compute)</li>
  <li>Remote Desktop</li>
  <li>Internet Information Services (IIS)</li>
</ul>

<h2>Operating System</h2>
<ul>
  <li>Windows 10 Pro (21H2)</li>
</ul>

<h2>Stages of a Ticket's Journey</h2>
<ul>
  <li>Intake</li>
  <li>Assignment and Communication</li>
  <li>Working the Issue</li>
  <li>Resolution</li>
</ul>
<!--
  <tr>
    <td><code>Assigned</code></td>
    <td>When a ticket is assigned to an agent, team, or department for resolution.</td>
  </tr>
  <tr>
    <td><code>Working the Issue</code></td>
    <td>The process of communicating with the customer and taking steps to resolve the issue.</td>
  </tr>
  <tr>
    <td><code>Resolution</code></td>
    <td>The final step where the issue is resolved, and the ticket is closed.</td>
  </tr>
</table>
-->
<hr>

<h2>The Ticket Lifecycle</h2>

<h3>What the Customer Experiences</h3>
<p>
When a customer submits a ticket to the help desk, they immediately receive a notification that their request has been received. This keeps them in the loop right from the start.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/97c35569-1f22-42d5-8d1f-1d5572a62584" alt="End-User Experience" width="70%" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/dcde6078-4e9e-4c0b-88ec-5d5468743b88" alt="Ticket Confirmation" width="70%" />
</p>

<hr>

<h3>Stage 1: Intake</h3>
<p>
Once an agent or admin logs into the help desk, they can see all incoming tickets. Tickets are sorted by details like ticket number, subject, customer, priority, and assignment status. It's up to the agent or queue manager to assign tickets and set the appropriate priority.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/25ba8562-01de-4e23-8544-8f9769f243f7" width="70%" />
</p>

<hr>

<h3>Stage 2: Working the Issue</h3>
<p>
In this stage, the agent starts addressing the ticket. Let’s say the ticket reports that the "entire mobile online banking system is down." Initially marked as "Normal" priority, the agent recognizes its importance and escalates it to "Emergency." Notes and updates are added to document every action.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/69190fbe-a1c5-4b9c-8fdc-bdab6b1906d4" alt="Changing Ticket Priority" width="70%" />
</p>

<p>
Next, the ticket is reassigned to Jane Doe and moved from the Support Department to the System Administrators Department for more specialized handling. The updates and reassignments are clearly tracked within the ticket.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/11ad36df-26e5-44c9-ab42-1b728f67a863" alt="Ticket Reassignment" width="70%" />
</p>

<p>
The dashboard now reflects the changes: Jane Doe is handling the ticket, and its priority has been escalated to "Emergency."
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ee797041-b788-4a8b-b24a-de9862f2da7e" alt="Updated Ticket Status" width="70%" />
</p>

<hr>

<h3>Stage 3: Resolution</h3>
<p>
The Sys Admin team resolves the issue, and the agent updates the ticket with a resolution comment. The ticket is then moved to the "Closed" column, signifying the end of its lifecycle.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/424a5de7-2f2a-43ac-85a1-8b6113791dfe" alt="Ticket Resolved" width="70%" />
</p>

<p>
Now that the issue is resolved, the ticket appears in the "Closed Tickets" section of the dashboard.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/f58c1a84-fd13-4fcc-a126-a3463580faa8" alt="Ticket Closed" width="70%" />
</p>

<hr>

<h2>Wrapping It Up</h2>
<p>
The osTicket system provides a structured way to handle help desk tickets from start to finish. By following clear steps—intake, assignment, working the issue, and resolution—both customers and agents benefit from streamlined communication and efficient problem-solving.
</p>
