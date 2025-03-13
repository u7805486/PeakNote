### **Personas**

#### **Persona 1: Corporate Team Manager**

- **Name**: Zheng
- **Age**: 38
- **Occupation**: Project Manager
- **Needs**: Efficiently record meeting content and quickly assign tasks to team members.
- **Pain Points**: Manually taking meeting minutes is time-consuming, task assignments are prone to omissions, and tracking task progress after meetings is difficult.
- **SkyNote Value**: Automatically generates task lists after meetings, improving team execution efficiency.

#### **Persona 2: Startup Founder**

- **Name**: Wang
- **Age**: 32
- **Occupation**: CEO of a Startup
- **Needs**: Quickly capture key information from multiple meetings and avoid missing critical decisions.
- **Pain Points**: Frequent meetings make it hard to manually organize discussion points, and efficient collaboration is essential.
- **SkyNote Value**: Provides automated meeting summaries to help review key takeaways and prevent information loss.

#### **Persona 3: Remote Team Member**

- **Name**: Lucy
- **Age**: 28
- **Occupation**: Remote Product Manager
- **Needs**: Stay updated on meetings, even if unable to attend due to time zone differences.
- **Pain Points**: Different time zones make it difficult to join all meetings in real-time, and meeting notes are often inconsistent in quality.
- **SkyNote Value**: Offers comprehensive and structured meeting minutes, ensuring no crucial information is missed.

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
