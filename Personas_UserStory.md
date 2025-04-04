### **Personas**

#### **Persona 1: Corporate Team Manager**

- **Name**: Zheng
  
- **Age**: 38
  
- **Occupation**: Project Manager
  
- **Needs**: Efficiently record meeting content and quickly assign tasks to team members.
  
- **Pain Points**: Manually taking meeting minutes is time-consuming, task assignments are difficult to achieve, and tracking task progress after meetings is difficult.
  
- **MeetingAssistant Value**: Automatically generates task lists after meetings, improving team execution efficiency. Provides a post-meeting preview interface to review, modify, and confirm the meeting minutes before finalizing them.
  

#### **Persona 2: Startup Founder**

- **Name**: Wang
  
- **Age**: 32
  
- **Occupation**: CEO of a Startup
  
- **Needs**: Quickly capture key information from multiple meetings and avoid missing critical decisions.
  
- **Pain Points**: Frequent meetings make it hard to manually organize discussion points, and efficient collaboration is essential.
  
- **MeetingAssistant Value**: Provides automated meeting summaries to help review key takeaways and prevent information loss. Allows seamless sharing of finalized meeting minutes with Teams colleagues and groups.
  

#### **Persona 3: Executive Assistant**

- Name: Sarah
  
- Age: 35
  
- Occupation: Executive Assistant to C-Suite Leadership
  
- Needs: Efficiently organize and distribute meeting summaries to executives
  
- Pain Points: Manually creating and sending meeting notes to multiple stakeholders is time-consuming and prone to inconsistency
  
- MeetingAssistant Value: Automatically delivers polished meeting summaries directly to executives' Outlook inboxes, saving time and ensuring consistent communication. Users can download meeting summaries in PDF or Word format for formal documentation.
  

#### Persona 4: Sales Manager

- Name: Miguel
  
- Age: 42
  
- Occupation: Regional Sales Manager
  
- Needs: Track customer conversations and commitments across multiple client meetings
  
- Pain Points: Difficult to document all important details from numerous client meetings while maintaining customer relationships
  
- MeetingAssistant Value: Receives comprehensive meeting summaries in Outlook immediately after client meetings, allowing quick follow-up on action items and commitments. Provides the ability to share key meeting takeaways directly to Teams for better coordination.
  

#### Persona 5: HR Director

- Name: Priya
  
- Age: 45
  
- Occupation: Human Resources Director
  
- Needs: Document important details from employee meetings and performance reviews
  
- Pain Points: Struggles to maintain thorough records of sensitive conversations while being fully present during meetings
  
- MeetingAssistant Value: Gets secure, confidential meeting summaries delivered to her Outlook inbox that can be easily filed with employee records. Supports markdown preview of meeting notes before formalizing them.
  

#### Persona 6: IT Administrator

- Name: Derek
  
- Age: 39
  
- Occupation: IT Systems Administrator
  
- Needs: Implement organization-wide meeting solutions that work with existing infrastructure
  
- Pain Points: New software tools often create integration challenges and security concerns
  
- MeetingAssistant Value: MeetingAssistant's seamless Outlook integration works within existing Microsoft ecosystem, minimizing security risks and deployment challenges. Provides options to manage meeting summary file formats and distribution.
  

#### Persona 7: Compliance Officer

- Name: Amara
  
- Age: 41
  
- Occupation: Regulatory Compliance Officer
  
- Needs: Maintain accurate records of compliance meetings and discussions
  
- Pain Points: Missing or incomplete meeting documentation can lead to regulatory issues
  
- MeetingAssistant Value: Receives comprehensive meeting summaries directly in Outlook that can be easily archived for audit purposes and compliance documentation. Ensures regulatory requirements by allowing a structured markdown preview before finalizing records.
  

---

### **User Stories & Scenarios**

#### **User Story 1: Automatic Meeting Summary**

**As a** project manager,  
**I want to** receive an automatically generated meeting summary,  
**so that** I can quickly review key points without going through the entire recording.

**Scenario:**  
Zheng holds a weekly team meeting where important decisions are made. After the meeting, MeetingAssistant generates a concise summary, including action items and major discussions. Zheng can quickly scan the summary to ensure nothing is missed.

#### **User Story 2: Task Assignment Based on Speakers’ Inputs**

**As a** team leader,  
**I want to** have tasks automatically assigned to speakers based on their statements,  
**so that** I can streamline the delegation process and improve accountability.

**Scenario:**  
During a product planning meeting, team members discuss their responsibilities. MeetingAssistant identifies the tasks mentioned and assigns them to the relevant team members, reducing manual effort for the manager.

#### **User Story 3: Post-Meeting Transcription**

**As a** remote team member,  
**I want to** access a transcript of the meeting after it ends,  
**so that** I can review the discussion even if I joined late or missed part of it.

**Scenario:**  
Lucy, working from a different time zone, joins the meeting 15 minutes late. After the meeting ends, MeetingAssistant generates a full transcript, allowing her to catch up on everything that was discussed.

#### **User Story 4: Post-Meeting Summary Preview and Editing**

**As an** executive assistant,  
**I want to** preview the generated meeting minutes in markdown format,  
**so that** I can make necessary modifications before finalizing the summary.

**Scenario:**  
After a high-stakes meeting, Sarah accesses the markdown preview of the generated meeting summary. She quickly edits key points and confirms formatting before finalizing it as a PDF to distribute to executives.

#### **User Story 5: Meeting Summary Export and Sharing**

**As a** sales manager,  
**I want to** download the finalized meeting summary in PDF or Word format or share it with Teams colleagues,  
**so that** I can ensure proper documentation and collaboration.

**Scenario:**  
After an important client meeting, Miguel finalizes the meeting summary and chooses to download a PDF version for documentation. Additionally, he shares it directly with his sales team on Microsoft Teams to keep everyone aligned.

---

### **Requirements Elicitation**

1. **Functional Requirements**
  
  - Automatically generate structured meeting summaries.
    
  - Identify speakers and assign tasks accordingly.
    
  - Provide post-meeting transcription.
    
  - Enable exporting of meeting minutes in different formats (PDF, DOCX, etc.).
    
  - Sensitive words should be avoided when transcribing.
    
  - Seamless integration with Microsoft Teams or other tools to enable effortless usage during meetings.
    
  - Provide a markdown-based preview interface for reviewing and editing meeting summaries before finalization.
    
  - Enable downloading finalized meeting minutes as PDF or Word documents.
    
  - Allow direct sharing of meeting summaries with Teams colleagues or groups.
    
2. **Non-functional Requirements**
  
  - Must have high accuracy in speech recognition and transcription.
    
  - Must be secure, ensuring only authorized users can access meeting data.
    
  - Should have a user-friendly interface with minimal learning curve.
