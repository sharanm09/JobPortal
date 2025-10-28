# Job Portal - Complete Project Flow Document

## Complete Project Flow Overview

The following diagram illustrates the end-to-end flow of the Job Portal system, showing how recruiters and candidates move through each phase from job creation to final hiring decisions.

```mermaid
flowchart TD
    %% ---------------- Phase 1: Job Posting ----------------
    A[Recruiter Login] --> B[Create Job Post]
    B --> C[Job Validation & Storage]
    C --> D[Automatic Distribution to Platforms]
    
    D --> E[Social Media Platforms]
    D --> F[Job Portals]
    
    E --> G[LinkedIn]
    E --> H[X/Twitter]
    E --> I[Facebook]
    E --> J[Instagram]
    
    F --> K[Naukri]
    F --> L[Indeed]
    F --> M[LinkedIn Jobs]
    
    %% ---------------- Phase 2: Candidate Applications ----------------
    G --> N[Candidate Applications]
    H --> N
    I --> N
    J --> N
    K --> N
    L --> N
    M --> N
    
    N --> O[Resume Collection & Storage]
    O --> P[Resume Parsing & AI Scoring]
    P --> Q[Candidate Pool Management]
    
    %% ---------------- Phase 3: Candidate Sourcing & Screening ----------------
    Q --> R[Automated Screening]
    R --> S[Experience & CTC Verification]
    R --> T[Notice Period & Communication Assessment]
    
    S --> U[Screening Results]
    T --> U
    
    %% ---------------- Phase 4: Assessment Test ----------------
    U --> V[QwikHire Assessment Assignment]
    V --> W[General Round]
    V --> X[Position Round]
    V --> Y[Aptitude Round (Optional)]
    V --> Z[Coding Round (Optional)]
    
    W --> AA[AI Evaluation & Scoring]
    X --> AA
    Y --> AA
    Z --> AA
    
    %% ---------------- Phase 5: Document Collection ----------------
    AA --> BB[Document Collection]
    BB --> CC[Identity Proof]
    BB --> DD[Education Certificates]
    BB --> EE[Experience Letters]
    BB --> FF[Salary Slips]
    BB --> GG[Address Proof]
    
    CC --> HH[Document Verification]
    DD --> HH
    EE --> HH
    FF --> HH
    GG --> HH
    
    %% ---------------- Phase 6: Interview ----------------
    HH --> II[Interview Process]
    II --> JJ[Technical Round]
    II --> KK[Functional Round]
    II --> LL[Managerial Round]
    II --> MM[HR Round]
    II --> NN[Client Round (Optional)]
    
    JJ --> OO[Interview Feedback]
    KK --> OO
    LL --> OO
    MM --> OO
    NN --> OO
    
    %% ---------------- Phase 7: Final Decision & Notification ----------------
    OO --> PP[Final Evaluation & Aggregate Reports]
    PP --> QQ[Final Decision: Selected / Not Selected]
    
    QQ --> RR[Selected Candidates → Offer Management]
    QQ --> SS[Not Selected Candidates → Rejection Notification]
    
    RR --> TT[Salary Negotiation & Offer Letter]
    RR --> UU[Terms Finalization & Onboarding]
    
    SS --> VV[Thank You Email]
    
    TT --> WW[Hiring Complete]
    UU --> WW
    VV --> WW
    
    %% ---------------- Color Styling ----------------
    style A fill:#e1f5fe,stroke:#0288d1,color:#000
    style B fill:#e1f5fe,stroke:#0288d1,color:#000
    style C fill:#e1f5fe,stroke:#0288d1,color:#000
    style D fill:#fff3e0,stroke:#fb8c00,color:#000
    style E fill:#fff3e0,stroke:#fb8c00,color:#000
    style F fill:#fff3e0,stroke:#fb8c00,color:#000
    style G fill:#fffde7,stroke:#fbc02d,color:#000
    style H fill:#fffde7,stroke:#fbc02d,color:#000
    style I fill:#fffde7,stroke:#fbc02d,color:#000
    style J fill:#fffde7,stroke:#fbc02d,color:#000
    style K fill:#fffde7,stroke:#fbc02d,color:#000
    style L fill:#fffde7,stroke:#fbc02d,color:#000
    style M fill:#fffde7,stroke:#fbc02d,color:#000
    style N fill:#f3e5f5,stroke:#7b1fa2,color:#000
    style O fill:#f3e5f5,stroke:#7b1fa2,color:#000
    style P fill:#f3e5f5,stroke:#7b1fa2,color:#000
    style Q fill:#f3e5f5,stroke:#7b1fa2,color:#000
    style R fill:#e8f5e8,stroke:#2e7d32,color:#000
    style S fill:#e8f5e8,stroke:#2e7d32,color:#000
    style T fill:#e8f5e8,stroke:#2e7d32,color:#000
    style U fill:#c8e6c9,stroke:#1b5e20,color:#000
    style V fill:#fff8e1,stroke:#f57f17,color:#000
    style W fill:#fff8e1,stroke:#f57f17,color:#000
    style X fill:#fff8e1,stroke:#f57f17,color:#000
    style Y fill:#fff8e1,stroke:#f57f17,color:#000
    style Z fill:#fff8e1,stroke:#f57f17,color:#000
    style AA fill:#fff8e1,stroke:#f57f17,color:#000
    style BB fill:#fce4ec,stroke:#d81b60,color:#000
    style CC fill:#fce4ec,stroke:#d81b60,color:#000
    style DD fill:#fce4ec,stroke:#d81b60,color:#000
    style EE fill:#fce4ec,stroke:#d81b60,color:#000
    style FF fill:#fce4ec,stroke:#d81b60,color:#000
    style GG fill:#fce4ec,stroke:#d81b60,color:#000
    style HH fill:#f8bbd0,stroke:#880e4f,color:#000
    style II fill:#e0f2f1,stroke:#00695c,color:#000
    style JJ fill:#e0f2f1,stroke:#00695c,color:#000
    style KK fill:#e0f2f1,stroke:#00695c,color:#000
    style LL fill:#e0f2f1,stroke:#00695c,color:#000
    style MM fill:#e0f2f1,stroke:#00695c,color:#000
    style NN fill:#e0f2f1,stroke:#00695c,color:#000
    style OO fill:#f1f8e9,stroke:#33691e,color:#000
    style PP fill:#f1f8e9,stroke:#33691e,color:#000
    style QQ fill:#c5e1a5,stroke:#33691e,color:#000
    style RR fill:#c8e6c9,stroke:#2e7d32,color:#000
    style SS fill:#ffcdd2,stroke:#b71c1c,color:#000
    style TT fill:#fff9c4,stroke:#f9a825,color:#000
    style UU fill:#fff9c4,stroke:#f9a825,color:#000
    style VV fill:#ffcdd2,stroke:#b71c1c,color:#000
    style WW fill:#c8e6c9,stroke:#2e7d32,color:#000
```

## Phase-by-Phase Flow Summary

| Phase | Process | Key Activities | Outcome |
|-------|---------|----------------|---------|
| **Phase 1** | Job Posting & Distribution | Create job post, validate fields, distribute across platforms | Job live on multiple channels |
| **Phase 2** | Candidate Sourcing & Searching | Manual search, automated sourcing, candidate pool management | Centralized candidate database |
| **Phase 3** | Resume Collection & Storage | Collect resumes, process pipeline, AI parsing & scoring | Structured candidate data with ATS scores |
| **Phase 4** | Automated Candidate Screening | Verify experience, CTC, notice period, communication assessment | Screening results with recommendations |
| **Phase 5** | Assessment Test | General, Position, Aptitude, Coding rounds with AI evaluation | Test scores and selection status |
| **Phase 6** | Document Collection & Verification | Collect and verify identity, education, experience documents | Verified candidate credentials |
| **Phase 7** | Interview Process Management | Multi-level interviews with structured feedback | Interview scores and recommendations |
| **Phase 8** | Final Decision & Notification | Aggregate all data, make final decision, notify candidates | Selected candidates proceed to offer, others receive rejection |

---

## PHASE 1: JOB POSTING & DISTRIBUTION

### 1.1 Job Post Creation Flow

**Objective**: Enable recruiters to create job posts and automatically distribute them across multiple channels. This feature streamlines the hiring process by allowing recruiters to define job requirements, descriptions, and desired candidate profiles once. The system then takes this information and intelligently publishes the job opening to various platforms, such as popular job boards, social media networks, and professional networking sites, maximizing visibility and reach to potential candidates. This automation saves time and effort for recruiters, ensuring wider exposure for each job opening without manual intervention.

**Process Flow**:
1. **Recruiter Login** → Access recruiter dashboard
2. **Create Job Post** → Fill out the job posting form with required fields
3. **Validation** → System validates all mandatory fields
4. **Job ID Generation** → System generates a unique job ID
5. **Job Storage** → Job details stored securely in the system database
6. **Distribution Trigger** → Automatic job distribution process starts

**Input Fields Required**:

| Field Name          | Type                 | Mandatory | Description                                           |
|---------------------|----------------------|-----------|-------------------------------------------------------|
| job_title           | Text                 | Yes       | Name of the job/position                              |
| skills_required      | Array/List of Text   | Yes       | Required technical or functional skills               |
| ctc_min             | Number               | Yes       | Minimum salary/CTC offered                            |
| ctc_max             | Number               | Yes       | Maximum salary/CTC offered                            |
| experience_min      | Number               | Yes       | Minimum years of experience                           |
| experience_max      | Number               | Yes       | Maximum years of experience                           |
| job_location        | Text                 | Yes       | City/State/Country of the job                         |
| employment_type     | Enum                 | Yes       | Full-time / Part-time / Contract / Internship         |
| job_description     | Textarea             | Yes       | Detailed description of the job responsibilities      |
| apply_link          | URL                  | Yes       | Link to the application form or platform              |
| company_name        | Text                 | Yes       | Name of the hiring company                            |
| company_description | Textarea             | No        | Brief about the company                               |
| contact_email       | Email                | Yes       | Recruiter contact email                               |
| contact_phone       | Text                 | No        | Recruiter contact phone number                        |
| job_id              | Auto-generated       | Yes       | Unique identifier for the job post                    |
| posting_date        | Date                 | Auto      | Date when the job is posted                           |
| expiry_date         | Date                 | Optional  | Date when the job posting expires                     |

**System Response**: Job is successfully created with a unique Job ID and distribution status.

### 1.2 Automatic Distribution Flow

**Objective**: Automatically post jobs to multiple social media platforms and job portals.

**Distribution Channels**:
- **Social Media Platforms**:
  - LinkedIn
  - X (Twitter)
  - Facebook
  - Instagram
- **Job Portals**:
  - Naukri
  - Indeed
  - LinkedIn Jobs

**Job Distribution Flow**:
1. **Analyze Job** → Identify key requirements, skills, location, and salary
2. **Select Platforms** → Choose suitable job boards based on job type
3. **Adapt Content** → Format the job post for each platform
4. **Post Automatically** → Publish jobs using APIs or approved third-party services
5. **Track Status** → Monitor posting success or failure on each platform
6. **Notify Recruiter** → Inform the recruiter about the distribution results

### 1.3 Social Media & Job Portal Integration

| Platform    | API                           | Auth      | Endpoints                                                                 | Documentation                    |
|-------------|-------------------------------|-----------|---------------------------------------------------------------------------|----------------------------------|
| LinkedIn    | LinkedIn Job Posting API      | OAuth 2.0 | POST: /jobPostings, PUT: /jobPostings/{id}, DELETE: /jobPostings/{id}   | LinkedIn API Docs                |
| Naukri      | Workable/Naukri Job Posting API | API Key   | Third-party ATS or approved API services                                 | Naukri Integration               |
| Indeed      | Indeed Job Sync API           | OAuth 2.0 | POST /jobs, PUT /jobs/{id}, DELETE /jobs/{id}                           | Indeed API Docs                  |
| Facebook    | Facebook Pages API             | OAuth 2.0 | POST /{page-id}/feed, POST /{post-id}, DELETE /{post-id}                 | Facebook API Docs                |
| Instagram   | Instagram Graph API            | OAuth 2.0 | POST /{ig-user-id}/media, POST/{ig-user-id}/media_publish                | Instagram Content Publishing     |
| X / Twitter | X API                         | OAuth 2.0 | POST /2/tweets, DELETE /2/tweets/{id}                                   | X Developer API                  |

### 1.4 Notification System

**Recruiter Notifications**:
- Job posting confirmation
- Distribution success/failure summary
- Candidate application alerts

**This Phase 1 document covers**:
- Job creation and validation
- Automatic posting and distribution logic
- Social media & job portal integration details
- Notifications for recruiters and candidates

---

## PHASE 2: CANDIDATE SOURCING & SEARCHING

### 2.1 Overview

**Objective**: Enable recruiters to efficiently source candidates, either manually through direct input or automatically via integrations with multiple external platforms, and consolidate all candidate information into a centralized, easily manageable pool. This ensures a comprehensive database for current and future hiring needs, streamlining the recruitment process and reducing redundant efforts.

**Key Activities**:
- Job search across external portals (LinkedIn, Naukri, Indeed, GitHub, etc.)
- Fetch relevant candidate/job data using APIs (or scraping where allowed)
- Filter candidates by experience, skills, location, and other parameters
- Store all potential profiles in a candidate pool for further processing

### 2.2 Candidate Sourcing Methods

#### A. Manual Candidate Search

**Objective**: Recruiters search for candidates directly using filters and view results in the system.

**Search Parameters & Filters**:

| Field Name          | Type               | Mandatory | Description                                                                 |
|---------------------|--------------------|-----------|-----------------------------------------------------------------------------|
| job_title           | Text               | Yes       | The title or designation of the role being searched (e.g., "Software Engineer", "HR Manager") |
| skills              | Array/List of Text | Optional  | Filter by one or multiple technical or functional skills (e.g., React, Java, SQL) |
| experience_min      | Number             | Optional  | Minimum years of relevant experience                                       |
| experience_max      | Number             | Optional  | Maximum years of relevant experience                                        |
| ctc_min             | Number             | Optional  | Minimum current CTC or expected CTC range                                  |
| ctc_max             | Number             | Optional  | Maximum current CTC or expected CTC range                                  |
| location            | Text               | Optional  | City, state, or country to filter candidates by geographical preference    |
| education_level     | Text               | Optional  | Filter candidates based on their education level (e.g., Bachelor's, Master's, Diploma) |
| employment_type     | Enum               | Optional  | Full-time, Part-time, Contract, Internship                                 |
| availability_status | Enum               | Optional  | Available, Serving Notice, Not Available                                   |
| source_platform     | Enum               | Optional  | Internal Database, LinkedIn, Naukri, Indeed, GitHub, Stack Overflow        |

**Process Flow**:
1. **Recruiter inputs search filters**
2. **System searches the candidate database**
3. **Matching candidates are displayed in a ranked list**
4. **Recruiter reviews profiles and selects relevant candidates**

### 2.3 Candidate Pool Management

**Objective**: Maintain a centralized database of all potential candidates for future processing.

**Candidate Information Stored**:

| Field Name              | Type           | Description                                                                    |
|-------------------------|----------------|--------------------------------------------------------------------------------|
| candidate_id            | Auto-generated | Unique identifier for each candidate record                                   |
| full_name               | Text           | Candidate's full name                                                         |
| email                   | Email          | Candidate's email address                                                      |
| phone_number            | Text           | Candidate's contact number                                                     |
| alternate_contact       | Text           | Alternate phone number (if provided)                                          |
| current_designation     | Text           | Current job title or designation                                              |
| current_company         | Text           | Current organization name                                                      |
| skills                  | Array/List     | Technical and functional skills of the candidate                              |
| total_experience        | Number         | Total years of professional experience                                        |
| relevant_experience     | Number         | Years of experience relevant to the applied job                               |
| current_ctc             | Number         | Candidate's current annual salary package (CTC)                               |
| expected_ctc            | Number         | Candidate's expected annual salary package (CTC)                              |
| notice_period           | Text / Number  | Notice period duration (in days or weeks)                                     |
| preferred_location      | Text           | Candidate's preferred work location(s)                                        |
| current_location        | Text           | Candidate's current city/state/country                                         |
| education               | Array/List     | Details of academic qualifications (degree, institution, year)                |
| certifications          | Array/List     | Certifications or additional qualifications                                    |
| projects                | Array/List     | Major projects handled by the candidate with technologies used                 |
| languages_known         | Array/List     | Languages spoken or written by the candidate                                  |
| resume_file_name        | Text           | Original filename of the uploaded resume                                      |
| resume_file_url         | URL            | Cloud storage link to access the candidate's resume file                      |
| resume_parsed_text      | Long Text      | Extracted plain text content from the resume for indexing/search              |
| resume_upload_date      | DateTime       | Date and time when the resume was uploaded                                    |
| source_platform         | Enum           | Source from which the candidate was imported (LinkedIn, Naukri, Indeed, etc.) |
| profile_url              | URL            | Profile link on the original source platform                                  |
| availability_status      | Enum           | Available, Serving Notice, Not Available                                      |
| application_status       | Enum           | New, Screened, Shortlisted, Interviewing, Selected, Rejected                  |
| screening_remarks        | Textarea       | Recruiter notes or remarks after screening                                    |
| ai_score                 | Number         | AI-calculated score based on resume-job match                                 |
| skills_match_percentage  | Number         | Percentage of skill match between resume and job post                         |
| education_match_score    | Number         | Relevance score based on education background                                 |
| location_match_score     | Number         | Score representing geographical fit for the job                              |
| created_at               | DateTime       | Timestamp when the candidate profile was created in the system                |
| updated_at               | DateTime       | Timestamp when the candidate profile was last updated                         |
| created_by               | Text           | Recruiter or system ID that created the candidate record                      |
| verified_by              | Text           | Recruiter who verified candidate documents or details                         |
| remarks                  | Textarea       | General notes or comments on the candidate                                    |

**Candidate Pool Operations**:
- Add new candidates manually
- Update existing candidate information
- Filter and sort candidates by skills, experience, location, CTC, and availability
- Track recruitment status of each candidate across all phases

### 2.4 Integration Notes

- **LinkedIn API** → OAuth 2.0 authentication, use GET /people to fetch candidate profiles
- **Naukri API** → API key authentication, fetch resumes via Workable integration
- **Indeed API** → OAuth 2.0, GET /jobs or resume API for candidate search
- **GitHub API** → Search developers by language, repository, and activity
- **Stack Overflow** → Jobs API or allowed scraping to gather developer profiles

**Note**: Always comply with API rate limits and platform terms of service.

### 2.5 Connecting to Social Media & Job Platforms (Live Candidate Search)

#### Authentication
Each platform requires a specific authentication method:
- **LinkedIn**: OAuth 2.0 → obtain an access token for the application
- **Naukri**: API key → provided by Naukri/Workable integration
- **Indeed**: OAuth 2.0 or API key depending on plan
- **GitHub**: Personal Access Token or OAuth App token
- **Stack Overflow / Others**: Usually public API or allowed scraping

#### Process
1. **Recruiter initiates search from the UI**
2. **Backend (Search Aggregation Service) injects stored credentials for each platform into the connector API request**

#### Platform-Specific Connectors
Each platform has a connector module in the backend, responsible for:
- Translating generic search filters into platform-specific queries
- Calling the platform API or permitted scraping endpoints
- Returning results in a raw format for normalization

#### Normalization
After raw results are fetched:
- Platform-specific fields are mapped to your Candidate Pool schema
- Example: LinkedIn positions.title → current_designation; GitHub languages → skills
- Salary/CTC converted to standard units; experience in years

#### Deduplication
- Checks duplicates across multiple platforms using email, phone, profile URL, or fuzzy matching
- Merges partial profiles, keeping source platform references

#### Indexing & Response
- Normalized & deduped candidate profiles are indexed in Elasticsearch/MongoDB
- Response sent back to recruiter UI with ranking, skill-match %, AI score, etc.

#### Optional Live Fetch vs Cache
- **live_fetch=true** → backend calls external connectors in real-time
- **live_fetch=false** → only queries internal candidate pool (faster, no external API usage)

#### Diagram – How Search Connects to Social Platforms
```
Step 1: Recruiter UI
Step 2: POST /api/candidates/search
Step 3: Search Aggregation Service / API Gateway
Step 4: Connectors Layer (parallel)
├─ LinkedIn API
├─ Naukri API
├─ Indeed API
├─ GitHub API
└─ Internal DB
Step 5: Normalization & Deduplication
Step 6: Candidate Pool DB + Search Index
Step 7: Response -> Recruiter UI
```

---

## PHASE 3: RESUME COLLECTION & STORAGE

### 3.1 Overview

**Objective**: Centralize candidate resumes from multiple sources, extract structured information, and calculate ATS/AI match scores with job descriptions for better hiring decisions.

**Goals**: 
- Streamline the hiring process and reduce time-to-hire
- Improve candidate quality and reduce recruitment timings

**Key Activities**:
- Collect resumes from multiple sources
- Extract structured candidate information
- Link resumes with job positions and job descriptions
- Calculate resume-to-job match scores (ATS score)
- Store resume data and scores in the database linked to candidate and job IDs

### 3.2 Resume Collection Sources

| Collection Method      | Description                                    |
|------------------------|------------------------------------------------|
| Direct Applications    | Candidates apply through job posting links     |
| Recruiter Upload       | Recruiters manually upload resumes into the system |
| Email Parsing          | System parses resumes received via email attachments |
| Third-party Referrals  | Resumes sourced from partner companies        |
| Social Media Downloads | Download resumes from LinkedIn or other platforms |
| Bulk Import            | Import multiple resumes from CSV or Excel files |

### 3.3 Resume Storage System

**Storage Steps**:
1. **File Upload** → Candidates or recruiters upload resume files
2. **File Validation** → System checks for valid file format and size
3. **Security Scanning** → Scan for malware or security threats
4. **Secure Storage** → Upload and store files in secure cloud storage
5. **Metadata Creation** → Create a record with:
   - Resume ID
   - Candidate ID
   - File name, type, size
   - Source platform
   - Upload date/time
   - Processing status
6. **Indexing** → Index resumes for search and retrieval

**Resume Information Stored (DB Fields)**:

| Field Name        | Type       | Description                                    |
|-------------------|------------|------------------------------------------------|
| resume_id         | Auto-generated | Unique ID for the resume                   |
| candidate_id      | Text       | Link to the candidate profile                 |
| file_name         | Text       | Original resume file name                      |
| file_type         | Text       | File type (PDF, DOC, DOCX)                    |
| file_size         | Number     | Size of the resume file                       |
| source_platform   | Enum       | Source (LinkedIn, Email, Upload, etc.)        |
| upload_date       | DateTime   | Timestamp when uploaded                       |
| parsing_status    | Enum       | Pending, Completed, Failed                     |
| structured_data   | JSON       | Extracted candidate information               |
| ats_score         | Number     | Resume-to-job match score                     |
| job_id            | Text       | Job position ID linked for scoring            |
| jd_text           | Long Text  | Job description used for scoring              |

### 3.4 Resume Processing Pipeline

**Step-by-Step Flow**:

1. **File Validation**
   - Verify correct format (PDF, DOC, DOCX)
   - Check file size limits

2. **Security Scanning**
   - Scan resume files for malware or threats

3. **Text Extraction**
   - Extract plain text content from resume files

4. **Structured Data Extraction (AI)**
   - Use AI/NLP to extract:
     - Skills
     - Work experience
     - Education
     - Certifications
     - Projects
     - Languages

5. **Job Description Linking**
   - Fetch the job position and JD for which the candidate applied

6. **ATS/AI Scoring**
   - Pass resume structured data + JD to AI (e.g., ChatGPT/NLP model)
   - Compute resume-to-job match score, including:
     - Skills match %
     - Experience match
     - Education match
     - Keywords match

7. **Data Validation**
   - Validate extracted candidate data and scoring results

8. **Database Storage**
   - Store structured resume data and ATS score separately
   - Link each resume to candidate ID and job ID
   - Save timestamps for upload, parsing, and scoring

### 3.5 Resume Scoring Weightage

| Component              | Weight (%) | Description                                           |
|------------------------|------------|-------------------------------------------------------|
| Skills Match           | 40%        | Match between candidate skills and JD required skills |
| Experience Match       | 25%        | Alignment of total and relevant work experience with JD requirements |
| Projects / Work Portfolio | 15%     | Relevance of projects handled and technologies used   |
| Education Match        | 5%         | Match of highest degree and relevant certifications  |
| Job Title / Designation | 10%       | Alignment of current/previous job title with applied role |
| Keywords / ATS Terms   | 5%         | Presence of JD-specific keywords in resume           |

---

## PHASE 4: AUTOMATED CANDIDATE SCREENING

### 4.1 Overview

**Objective**: Automatically validate candidate details before formal interviews, ensuring candidates meet basic requirements and are fit for the role.

**Key Activities**:
- Verify candidate experience, current role, and salary expectations
- Check notice period and location preferences
- Assess communication skills and interest level
- Update candidate status and recommend next steps automatically

### 4.2 Screening Checklist

| Screening Aspect      | Description                                                      |
|-----------------------|------------------------------------------------------------------|
| Experience Verification | Confirm candidate's work history and relevant roles             |
| Current Role          | Verify current position and responsibilities                     |
| CTC Verification      | Check current and expected salary                                |
| Notice Period         | Check candidate availability timeline                            |
| Location Preference   | Confirm preferred work location                                  |
| Communication Skills  | Assess basic language and communication through AI/NLP          |
| Interest Level        | Determine interest in the specific role through automated responses |

### 4.3 Automated Screening Process

| Step                      | Description                                                      |
|---------------------------|------------------------------------------------------------------|
| Candidate Assignment      | System automatically assigns candidate to screening pipeline    |
| Data Extraction           | Parse and extract structured information from resume and application |
| Automated Verification    | Validate experience, current role, CTC, notice period, and location against JD requirements |
| AI/NLP Assessment         | Analyze communication skills and interest level from candidate inputs |
| Score Calculation         | Compute screening score to determine pass/fail/pending status    |
| Status Update             | Update candidate profile in system with screening results and score |
| Next Step Recommendation  | System suggests: Shortlist, Review, or Reject based on score and checks |

### 4.4 Screening Results Stored

| Field Name                | Type     | Description                                           |
|---------------------------|----------|-------------------------------------------------------|
| screening_status          | Enum     | Passed / Failed / Pending                             |
| screening_score           | Number   | AI-calculated score for automated screening          |
| verification_details      | JSON     | Collected data: experience, CTC, notice period, location checks |
| communication_score       | Number   | Score for communication and interest evaluation      |
| next_step_recommendation  | Enum     | Shortlist / Review / Reject                          |
| automated_remarks         | Text     | Notes or observations from automated screening       |
| screening_completion_date | DateTime | Timestamp when screening was completed               |

---

## PHASE 5: QWIKHIRE ASSESSMENT TEST

### 5.1 Overview

**Objective**: Assign an AI-driven assessment to candidates based on their Job Description (JD) and determine selection status automatically.

**Key Points**:
- Test assigned automatically using candidate's JD
- AI evaluates responses
- Four rounds available: General, Position, Aptitude (optional), Coding (optional)
- Candidate outcome: Selected or Not Selected after test completion

### 5.2 Test Rounds

| Round Type    | Description                                    | Optional? |
|---------------|------------------------------------------------|-----------|
| General Round | Behavioral, communication, and basic understanding of role | No        |
| Position Round | Job-specific functional/technical knowledge   | No        |
| Aptitude Round | Logical reasoning and problem-solving         | Yes       |
| Coding Round  | Programming and technical problem-solving     | Yes       |

---

## PHASE 6: DOCUMENT COLLECTION & VERIFICATION

### 6.1 Overview

**Objective**: Collect and verify candidate credentials to ensure authenticity before final hiring.

**Key Activities**:
- Collect identity, education, experience, salary, address, and other supporting documents
- Verify the authenticity of all submitted documents
- Ensure all documents are accurate before final hiring decisions

### 6.2 Required Documents

| Document Type         | Description                    |
|-----------------------|--------------------------------|
| Identity Proof        | Aadhaar, Passport, Driving License |
| Education Certificates | Degree certificates, mark sheets |
| Experience Letters    | Previous employment letters    |
| Salary Slips          | Last 3 months payslips         |
| Address Proof         | Utility bills, bank statements |
| Additional Documents  | Certifications, awards         |

### 6.3 Document Collection Method

| Method           | Description                           |
|------------------|---------------------------------------|
| Email Submission | Candidate sends documents via email attachments |

---

## PHASE 7: INTERVIEW PROCESS MANAGEMENT

### 7.1 Overview

**Objective**: Conduct structured interviews to assess candidates' technical, functional, managerial, and cultural fit before final selection.

**Key Activities**:
- Multi-level interviews based on job requirements
- Schedule and manage interviews efficiently
- Collect structured feedback and evaluation for each candidate

### 7.2 Interview Levels

| Level            | Purpose                                                      |
|------------------|--------------------------------------------------------------|
| Technical Round  | Assess technical skills and problem-solving ability          |
| Functional Round | Evaluate domain-specific knowledge and job-related expertise |
| Managerial Round | Assess leadership, management skills, and decision-making   |
| HR Round         | Evaluate cultural fit, behavior, and communication skills    |
| Client Round     | Final client evaluation (if applicable)                     |

### 7.3 Interview Scheduling & Management

| Step                  | Description                                                      |
|-----------------------|------------------------------------------------------------------|
| Interviewer Assignment | Assign interviewers for each round                               |
| Calendar Integration  | Sync interviews with interviewer calendars                      |
| Time Slot Selection   | Choose available time slots for each round                      |
| Candidate Notification | Send interview invitations to candidates                        |
| Reminder System       | Automated reminders before scheduled interviews                 |
| Rescheduling          | Handle candidate or interviewer rescheduling requests            |

### 7.4 Interview Tracking

| Field                    | Description                                                      |
|--------------------------|------------------------------------------------------------------|
| Candidate ID & Job ID    | Unique identifiers for tracking                                  |
| Current Interview Level  | Round currently in progress                                      |
| Interview Round Details  | Type of interview, assigned interviewer                          |
| Scheduled Date & Time    | Interview timing details                                         |
| Interview Status         | Completed / Scheduled / Cancelled                                |
| Interview Score & Feedback | Scores and comments recorded                                    |
| Pass/Fail Result         | Outcome of each interview round                                  |

### 7.5 Interview Feedback System

| Step              | Description                                                      |
|-------------------|------------------------------------------------------------------|
| Structured Forms  | Use standardized forms for feedback                             |
| Rating System     | Numerical rating for different evaluation criteria               |
| Comments          | Detailed written feedback from interviewer                       |
| Recommendations   | Hire / No Hire suggestions                                       |
| Next Steps        | Suggestions for improvement or follow-up actions                 |

---

## PHASE 8: FINAL DECISION & CANDIDATE NOTIFICATION

### 8.1 Overview

**Objective**: Ensure all candidate assessments, interviews, and documents are complete, collect any missing documents, determine final selection status, and notify candidates.

**Key Activities**:
- Identify and collect missing documents from candidates
- Aggregate all reports (resume, screening, assessments, interviews, documents)
- Determine final status: Selected or Not Selected
- Send automated notifications to candidates about the outcome

### 8.2 Missing Document Collection

| Step                      | Description                                                      |
|---------------------------|------------------------------------------------------------------|
| Check Document Completion | System verifies which required documents are missing            |
| Request Missing Documents | Send email/SMS to candidate requesting pending documents        |
| Receive & Verify Documents | Candidate submits missing documents via email; system verifies authenticity |

### 8.3 Final Evaluation Process

| Step                  | Description                                                      |
|-----------------------|------------------------------------------------------------------|
| Aggregate Reports     | Collect candidate data from: • AI Resume Score • Screening results • Assessment Test scores • Interview feedback • Document verification |
| Final Status Decision | Determine candidate status as Selected or Not Selected          |

### 8.4 Candidate Notification

| Type                | Description                                                      |
|---------------------|------------------------------------------------------------------|
| Selected Candidates  | Send congratulatory email/SMS with next steps (offer or joining instructions) |
| Not Selected Candidates | Send polite rejection email with optional feedback             |

---

## SYSTEM ARCHITECTURE & INTEGRATION FLOW

### Technology Stack

| Layer         | Technology                    |
|---------------|-------------------------------|
| Frontend      | React.js, TailwindCSS, Redux  |
| Backend       | Java Spring Boot              |
| Database      | MySQL, MongoDB                |
| AI/NLP        | ChatGPT                       |
| Job Portals   | LinkedIn API, Naukri API, Indeed API |
| Social Media  | LinkedIn API, Facebook Graph API, Twitter API |
| Notifications | Zepto Mail                    |
| Authentication | JWT                          |

### Data Flow Architecture

```
Job Posting → Distribution → Candidate Sourcing → Resume Collection → 
AI Parsing → Scoring → Screening → Assessment → Document Verification → 
Interview Rounds → Final Shortlisting → Offer Management → Onboarding
```

### Integration Points

1. **External APIs** → Job portals, social media platforms
2. **AI Services** → Resume parsing, candidate scoring
3. **Storage Services** → File storage, database management
4. **Communication Services** → Email, SMS, push notifications
5. **Calendar Services** → Interview scheduling
6. **Payment Services** → Billing and subscription management

---
