# SkyNote MVP Plan

## Overview
SkyNote MVP is a basic meeting app integration that allows users to upload meeting recordings and receive automatically generated meeting summaries. The focus is on delivering the core functionality of post-meeting summaries without real-time features or integrations.

## Core Features

### 1. Meeting Recording
- Simple interface to record audio/video files of meetings
- Support for common audio formats (MP3, WAV) and video formats (MP4)

### 2. Speech-to-Text Transcription
- Automated transcription of uploaded meeting recordings
- Basic speaker identification (without names)
- Accuracy optimization for business terminology

### 3. Summary Generation
- AI-powered summary creation from transcripts
- Extraction of key discussion points
- Identification of action items and decisions
- Concise format (approximately 10-15% of original meeting length)

### 4. Basic Meeting Management
- List view of all processed meetings
- Ability to name/rename meetings
- Date and time metadata
- Simple folder organization

### 5. Export Functionality
- Export summaries as PDF or text files
- Email sharing option for summaries (Outlook etc.)

## Technical Architecture

### Frontend
- JavaScript for the user interface
- Simple, responsive design
- Core screens:
  - Dashboard (list of meetings)
  - Upload page
  - Summary view page

### Backend
- Node.js or Python-based server
- RESTful API for frontend communication
- Integration with speech-to-text service (e.g., Google Speech-to-Text, AWS Transcribe)
- OpenAI API (or relevant api services) for summary generation

### Database
- MongoDB for storing:
  - User accounts
  - Meeting metadata
  - Transcripts
  - Generated summaries

## User Flow

1. **User Registration/Login**
   - Simple sign-up with email and password
   - Login to access personal dashboard

2. **Meeting Upload**
   - User uploads recorded meeting file
   - System shows upload progress and processing status

3. **Processing**
   - Backend transcribes the audio
   - AI generates summary from transcript
   - User is notified when processing is complete

4. **Summary Access**
   - User views generated summary
   - Can download/share the summary
   - Can access the full transcript if needed

5. **Meeting Management**
   - User can organize meetings into basic folders
   - Search functionality for finding specific meetings

## Development Roadmap

### Phase 1: Core Functionality (by the end of Semester 1)
- Set up project structure and environments
- Create meeting record functionality
- Integrate speech-to-text API
- Develop basic summary generation

### Phase 2: User Interface (by the mid of Semester 2)
- Design and implement dashboard
- Create meeting summary view
- Develop export functionality with Outlook integration

### Phase 3: Testing and Refinement (by the end of Semester 2)
- User testing with small group
- Refinement of summary quality, fine-tuning AI models
- Performance optimization
- Bug fixes

## Success Metrics
- Recording success rate (>95%)
- Transcription accuracy (>85%)
- Summary quality rating from users (>4/5)
