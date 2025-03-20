### **Personas**

#### **Persona 1: Corporate Team Manager**

- **Name**: Zheng
- **Age**: 38
- **Occupation**: Project Manager
- **Needs**: Efficiently record meeting content and quickly assign tasks to team members.
- **Pain Points**: Manually taking meeting minutes is time-consuming, task assignments are difficult to achieve, and tracking task progress after meetings is difficult.
- **SkyNote Value**: Automatically generates task lists after meetings, improving team execution efficiency.

#### **Persona 2: Startup Founder**

- **Name**: Wang
- **Age**: 32
- **Occupation**: CEO of a Startup
- **Needs**: Quickly capture key information from multiple meetings and avoid missing critical decisions.
- **Pain Points**: Frequent meetings make it hard to manually organize discussion points, and efficient collaboration is essential.
- **SkyNote Value**: Provides automated meeting summaries to help review key takeaways and prevent information loss.

#### **Persona 3: Executive Assistant**

- Name: Sarah
- Age: 35
- Occupation: Executive Assistant to C-Suite Leadership
- Needs: Efficiently organize and distribute meeting summaries to executives
- Pain Points: Manually creating and sending meeting notes to multiple stakeholders is time-consuming and prone to inconsistency
- SkyNote Value: Automatically delivers polished meeting summaries directly to executives' Outlook inboxes, saving time and ensuring consistent communication

#### Persona 4: Sales Manager

- Name: Miguel
- Age: 42
- Occupation: Regional Sales Manager
- Needs: Track customer conversations and commitments across multiple client meetings
- Pain Points: Difficult to document all important details from numerous client meetings while maintaining customer relationships
- SkyNote Value: Receives comprehensive meeting summaries in Outlook immediately after client meetings, allowing quick follow-up on action items and commitments

#### Persona 5: HR Director

- Name: Priya
- Age: 45
- Occupation: Human Resources Director
- Needs: Document important details from employee meetings and performance reviews
- Pain Points: Struggles to maintain thorough records of sensitive conversations while being fully present during meetings
- SkyNote Value: Gets secure, confidential meeting summaries delivered to her Outlook inbox that can be easily filed with employee records

#### Persona 6: IT Administrator

- Name: Derek
- Age: 39
- Occupation: IT Systems Administrator
- Needs: Implement organization-wide meeting solutions that work with existing infrastructure
- Pain Points: New software tools often create integration challenges and security concerns
- SkyNote Value: SkyNote's seamless Outlook integration works within existing Microsoft ecosystem, minimizing security risks and deployment challenges

#### Persona 7: Compliance Officer

- Name: Amara
- Age: 41
- Occupation: Regulatory Compliance Officer
- Needs: Maintain accurate records of compliance meetings and discussions
- Pain Points: Missing or incomplete meeting documentation can lead to regulatory issues
- SkyNote Value: Receives comprehensive meeting summaries directly in Outlook that can be easily archived for audit purposes and compliance documentation

---

### **User Stories & Scenarios**

#### **User Story 1: Automatic Meeting Summary**

**As a** project manager,  
**I want to** receive an automatically generated meeting summary,  
**so that** I can quickly review key points without going through the entire recording.

**Scenario:**  
Zheng holds a weekly team meeting where important decisions are made. After the meeting, SkyNote generates a concise summary, including action items and major discussions. Zheng can quickly scan the summary to ensure nothing is missed.

#### **User Story 2: Task Assignment Based on Speakers’ Inputs**

**As a** team leader,  
**I want to** have tasks automatically assigned to speakers based on their statements,  
**so that** I can streamline the delegation process and improve accountability.

**Scenario:**  
During a product planning meeting, team members discuss their responsibilities. SkyNote identifies the tasks mentioned and assigns them to the relevant team members, reducing manual effort for the manager.

#### **User Story 3: Real-time Meeting Transcription**

**As a** remote team member,  
**I want to** access a real-time transcript of the meeting,  
**so that** I can stay updated even if I join late or miss part of the discussion.

**Scenario:**  
Lucy, working from a different time zone, joins the meeting 15 minutes late. SkyNote provides a live transcript, allowing her to catch up without disrupting the flow of conversation.

#### **User Story 4: Searchable Meeting Archives**

**As a** startup founder,  
**I want to** search past meeting discussions by keywords,  
**so that** I can quickly retrieve important decisions and references.

**Scenario:**  
Wang needs to revisit a decision made two months ago about investor negotiations. He searches for "funding strategy" in SkyNote and finds the relevant meeting discussions within seconds.

#### **User Story 5: Multi-Language Support**

**As a** project manager,  
**I want to** translate the meeting content into multiple language.,  
**so that** every team member can have a clear understanding of meeting content.

**Scenario:**  
During a team meeting, project manager shares important updates in English. To ensure understands, they need a translation of the content for team members whose first language is not English.

#### **User Story 6: Seamless Integration with Skype for Business**

**As an** IT administrator,  
**I want the** AI meeting assistant to integrate seamlessly with Skype for Business,  
**so that** users can utilize its features without additional setup.

**Scenario:**  
During a company-wide meeting, employees use Skype for Business for communication. The IT administrator ensures that the AI meeting assistant is available without requiring manual configuration, allowing users to access transcription and summarization features effortlessly.

---

### **Requirements Elicitation**

1. **Functional Requirements**
   
   - Automatically generate structured meeting summaries.
   - Identify speakers and assign tasks accordingly.
   - Provide real-time transcription during meetings.
   - Store and allow searching of past meeting records.
   - Enable exporting of meeting minutes in different formats (PDF, DOCX, etc.).
   - Sensitive words should be avoided when transcribing.
   - Seamless integration with Skype for Business or other tools to enable effortless usage during meetings.

2. **Non-functional Requirements**
   
   - Must have high accuracy in speech recognition and transcription.
   - Should support multiple languages for global teams.
   - Must be secure, ensuring only authorized users can access meeting data.
   - Should have a user-friendly interface with minimal learning curve.
