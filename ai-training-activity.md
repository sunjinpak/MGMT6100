---
layout: default
title: "AI Training from Email Patterns"
---

[← Back to Index](index.html)

# AI-Powered Employee Training: From Email Patterns to Onboarding Guide

## Activity Overview

**Course Connection:** Ch 8 - Training Human Resources (CLO 6)
> CLO 6: Design training and development programs that enhance employee capabilities and support organizational learning objectives.

## The Problem

Every organization has employees who are irreplaceable, not because of their job title, but because of what they actually do. These are the people who have been in their role for years, who know every process inside and out, who have built relationships across the company, and who carry institutional knowledge that no one else has. Their official job description might say something generic like "coordinates HR activities," but in reality, they are the glue holding entire functions together.

Then one day, they leave. Maybe they resign, retire, get promoted, or transfer. And suddenly, the organization faces a crisis. No one fully understands what that person did. The job description is outdated or vague. The processes that person managed are undocumented. The relationships they maintained start to fall apart. And the new hire stepping into that role has no roadmap for how to succeed.

This is not a rare situation. It happens constantly, across every industry. And traditional approaches to solving it are slow and incomplete. You could interview the departing employee, but they often cannot articulate everything they do because so much of it has become automatic. You could ask their coworkers, but each person only sees one piece of the puzzle. You could observe them for a week, but that captures only a snapshot.

**What if there was a faster way?**

Modern organizations generate massive amounts of digital communication data. Every email an employee sends and receives is a record of what they actually do, who they work with, what decisions they make, and what problems they solve. With AI, we can now analyze these communication patterns at scale to reconstruct a detailed picture of a role, even after the person who held it is gone.

In this activity, you will experience this approach firsthand. You will use AI to analyze a set of employee emails, reverse-engineer a detailed job description, map the role's relationship network, and build a structured training guide for the next person stepping into that position.

**Time:** 75-90 minutes (can be split across two class sessions)
**Team Size:** 3-4 members
**Tools Needed:** Access to ChatGPT, Claude, Gemini, or any generative AI tool

## Learning Objectives

By the end of this activity, students will be able to:
1. Analyze unstructured workplace communication to identify core job responsibilities
2. Apply AI tools to extract patterns from employee behavior data
3. Map professional relationship networks using AI analysis of communication patterns
4. Design a structured onboarding training plan based on role analysis
5. Evaluate the strengths and limitations of AI-generated training content

## The Scenario

You are part of an HR consulting team hired by **Apex Solutions**, a mid-sized professional services firm (approximately 350 employees). The company's HR Coordinator, **Jordan Lee**, has just resigned after 4 years in the role. Jordan was the "go-to person" who handled everything from benefits questions to onboarding logistics to employee relations issues.

Jordan had been with Apex since the HR department was only two people. Over 4 years, the role expanded far beyond its original scope. Jordan took on new responsibilities as the company grew from 200 to 350 employees, opened a second office in Austin, and added new compliance requirements. But none of this was ever reflected in the job description, and Jordan never had a reason to document what had become second nature.

Now Jordan is gone, and the organization is scrambling.

**The problem:** Jordan's job description is a vague, one-paragraph summary from when the position was first created: *"The HR Coordinator supports the Human Resources department with various administrative tasks and employee relations activities."* It doesn't reflect what Jordan actually did. No one person at Apex can describe the full scope of the role. The HR Director knows the strategic pieces, the Payroll Manager knows the benefits side, the IT Manager knows the onboarding coordination, but no one has the complete picture.

**The opportunity:** The IT department has pulled 30 emails from Jordan's last two months on the job. These emails are a window into what Jordan actually did day to day. Your team will use AI to analyze these emails, construct an accurate job description, map Jordan's professional network, and develop a training guide so the next HR Coordinator can hit the ground running.

## Jordan Lee's Email Archive (30 Emails)

> **Contact Directory**
> Internal: Sarah Chen (Payroll), Tom Briggs (Facilities), Rachel Kim (Sales Mgr), Derek Huang (IT), Marcus Webb (VP Operations), Karen Walsh (HR Director), Angela Rivera (Engineering Mgr), Ashley Park (Austin Office Mgr)
> Employees: Lisa Tran, Sandra Morales, Carlos Medina, Priya Nair, Lin Zhang, David Okafor, Elena Martinez
> External: Amy Patel (HealthFirst Insurance), Nina Torres (TalentBridge Recruiting), James Porter (General Counsel), Ben Taylor (LearnPro Solutions LMS)

### Email 1
**From:** Jordan Lee
**To:** Sarah Chen (Payroll Manager)
**Subject:** Benefits enrollment discrepancy - Martinez
**Date:** Mon, Jan 6, 10:14 AM

Sarah, I just got off the phone with Elena Martinez from the Austin office. She says her dental coverage was dropped during open enrollment even though she submitted her form on time. I pulled her file and she did submit by the deadline. Can you check on your end whether payroll processed it? I told her I'd have an answer by Wednesday. Let me know if you need the form copy.

### Email 2
**From:** Tom Briggs (Facilities Manager)
**To:** Jordan Lee
**Subject:** New hire workspace setup
**Date:** Mon, Jan 6, 2:45 PM

Jordan, we have three new hires starting on the 13th. Can you send me their names, departments, and any special equipment requests? I need at least 5 business days to get workstations ready. Also, do any of them need parking passes?

### Email 3
**From:** Jordan Lee
**To:** Tom Briggs (Facilities Manager)
**Subject:** RE: New hire workspace setup
**Date:** Tue, Jan 7, 8:30 AM

Tom, here are the details:
1. Priya Nair, Marketing, needs dual monitors and a standing desk converter
2. David Okafor, Finance, standard setup
3. Lin Zhang, Engineering, needs an ergonomic keyboard and extra monitor

All three need parking passes. I'll send their signed offer letters to security for badge access today. Can you confirm once workstations are ready so I can include it in their welcome packets?

### Email 4
**From:** Rachel Kim (Department Manager, Sales)
**To:** Jordan Lee
**Subject:** Concern about team member
**Date:** Tue, Jan 7, 11:20 AM

Jordan, I need to talk to you about a situation with one of my team members. He's been consistently late for the past three weeks and it's affecting team morale. I've spoken with him informally but nothing has changed. What are my options here? I want to handle this properly before it escalates.

### Email 5
**From:** Jordan Lee
**To:** Rachel Kim (Department Manager, Sales)
**Subject:** RE: Concern about team member
**Date:** Tue, Jan 7, 3:05 PM

Rachel, thanks for reaching out before this got bigger. Here's what I'd recommend:

First, document the specific instances with dates and times. I've attached our Attendance Documentation Template. Next, schedule a formal one-on-one and use the template to frame the conversation around expectations versus actual performance. Make sure you note that this is a verbal warning, which is Step 1 of our progressive discipline process.

If you'd like, I can sit in on that meeting as an HR representative. I find it helps to have a neutral party present. Let me know what day works and I'll block my calendar.

I've also flagged this in our employee relations tracker so we have a record if it continues.

### Email 6
**From:** Jordan Lee
**To:** All Staff
**Subject:** Reminder - Q1 Compliance Training Due Jan 31
**Date:** Wed, Jan 8, 9:00 AM

Hi everyone,

This is a reminder that all employees must complete the Q1 compliance training modules by January 31. The modules are available in our LMS portal under "Required Training."

This quarter's modules include:
- Workplace Harassment Prevention (45 min)
- Data Privacy and Security (30 min)
- Emergency Evacuation Procedures (15 min)

If you completed these during onboarding in the last 60 days, you are exempt. Please reach out to me directly if you are having trouble accessing the LMS or need accommodations for the training.

Completion rates by department will be shared with department managers on February 3.

### Email 7
**From:** Jordan Lee
**To:** Marcus Webb (VP of Operations)
**Subject:** Exit interview summary - December departures
**Date:** Wed, Jan 8, 2:30 PM

Marcus, here is the summary from the four exit interviews I conducted in December.

Common themes:
- Two employees cited lack of growth opportunities as their primary reason for leaving
- One mentioned compensation was below market rate for their role
- Three out of four said their direct managers were supportive, but felt disconnected from senior leadership
- All four said onboarding was thorough but ongoing professional development was lacking

I've included my recommendations in the attached report. The biggest takeaway for me is the professional development gap. I'd like to discuss whether we should propose a mentorship program or tuition reimbursement pilot. Are you available for a 30-minute meeting next week?

### Email 8
**From:** Lisa Tran (New Hire, Marketing)
**To:** Jordan Lee
**Subject:** First week question
**Date:** Thu, Jan 9, 10:45 AM

Hi Jordan, I'm starting next Monday and wanted to ask whether I should bring anything specific on my first day. Also, is there a dress code? My offer letter mentioned "business casual" but I wasn't sure how strict that is. Thanks for all the helpful info you sent in the welcome packet!

### Email 9
**From:** Jordan Lee
**To:** Lisa Tran (New Hire, Marketing)
**Subject:** RE: First week question
**Date:** Thu, Jan 9, 11:30 AM

Hi Lisa, welcome aboard! Here's what to expect on your first day:

Please bring a valid photo ID and your completed I-9 documents (the list of acceptable documents was in your welcome packet). Everything else will be provided.

For dress code, business casual here is pretty relaxed. Think slacks or chinos and a blouse or collared shirt. Jeans are fine on Fridays. No need to stress about it.

Your first day schedule includes an HR orientation from 9-11, a tour of the office, lunch with your team, and then IT setup in the afternoon. I'll meet you at the front desk at 8:45.

Looking forward to meeting you!

### Email 10
**From:** Jordan Lee
**To:** Amy Patel (Benefits Vendor, HealthFirst Insurance)
**To:** Sarah Chen (Payroll Manager)
**Subject:** 2025 Benefits Renewal - Rate Comparison
**Date:** Fri, Jan 10, 9:15 AM

Amy, thank you for sending over the renewal quotes. I've reviewed the three plan options and have some concerns about Option B. The premium increase of 12% is significant, and I don't think leadership will approve it without a clear justification for the added coverage.

Can you prepare a side-by-side comparison of Options A and C, including out-of-pocket maximums, prescription coverage tiers, and the mental health benefits expansion? I need to present this to our CFO by January 20.

Sarah, can you pull the current enrollment numbers by plan tier? I want to show the projected cost impact for each option.

### Email 11
**From:** Derek Huang (IT Manager)
**To:** Jordan Lee
**Subject:** System access for new hires
**Date:** Mon, Jan 13, 8:00 AM

Jordan, the three new hires are here but I only received access request forms for two of them. Can you send Lin Zhang's form ASAP? Also, can we set up a recurring monthly meeting to go over upcoming hires so we're not doing this last minute every time?

### Email 12
**From:** Jordan Lee
**To:** Derek Huang (IT Manager)
**Subject:** RE: System access for new hires
**Date:** Mon, Jan 13, 8:25 AM

Derek, that's my mistake. I must have missed Lin's form in the batch. Sending it now.

And yes, a recurring monthly meeting is a great idea. How about the first Tuesday of each month at 10 AM? I'll send a calendar invite. I've actually been thinking about building a shared checklist in our project management tool so both HR and IT can track onboarding tasks in real time. Would your team be open to piloting that?

### Email 13
**From:** Sandra Morales (Employee, Customer Support)
**To:** Jordan Lee
**Subject:** FMLA question
**Date:** Tue, Jan 14, 1:30 PM

Jordan, I need to take some time off to care for my mother who is having surgery next month. Someone told me I might qualify for FMLA leave. I have no idea how this works. Can you explain the process and what paperwork I need to fill out? I'm worried about whether my job will be protected.

### Email 14
**From:** Jordan Lee
**To:** Sandra Morales (Employee, Customer Support)
**Subject:** RE: FMLA question
**Date:** Tue, Jan 14, 3:00 PM

Sandra, I'm glad you reached out. Based on your employment history, you should qualify for FMLA. Here's a quick overview:

FMLA provides up to 12 weeks of unpaid, job-protected leave per year for qualifying family medical reasons, including caring for a parent with a serious health condition.

Here's what you need to do:
1. Complete the FMLA Request Form (attached)
2. Have your mother's doctor complete the Medical Certification Form (also attached)
3. Return both forms to me at least 30 days before the leave starts, if possible

Your job and benefits are protected during FMLA leave. You'll continue on our health plan under the same terms.

I'd recommend we schedule a 20-minute meeting so I can walk you through the details and answer any questions. Would Thursday at 2 PM work?

### Email 15
**From:** Jordan Lee
**To:** Hiring Managers Distribution List
**Subject:** Updated interview scorecard template
**Date:** Wed, Jan 15, 10:00 AM

Hi all,

Based on feedback from the last hiring cycle, I've updated our interview scorecard template. Key changes include:
- Clearer behavioral competency definitions with example responses at each rating level
- A separate section for culture-fit assessment (replacing the old "general impression" category)
- A structured note-taking section to reduce bias in evaluations

Please start using this version for all interviews going forward. I'll be hosting a 30-minute training session on January 22 for anyone who wants a walkthrough. Calendar invite coming soon.

The old template should no longer be used. If you have candidates currently in the pipeline, please switch to the new version for remaining interviews.

### Email 16
**From:** Marcus Webb (VP of Operations)
**To:** Jordan Lee
**Subject:** Headcount planning for Q2
**Date:** Thu, Jan 16, 4:00 PM

Jordan, we need to start Q2 headcount planning. Can you pull together the current org chart, any approved but unfilled positions, and turnover data from the last 6 months? I'd also like your input on which departments are likely to request additional hires based on what you're hearing from managers.

Leadership meeting is February 5 and I want to have a draft plan by January 30.

### Email 17
**From:** Jordan Lee
**To:** Marcus Webb (VP of Operations)
**Subject:** RE: Headcount planning for Q2
**Date:** Fri, Jan 17, 9:30 AM

Marcus, I'll have the data package ready by January 28 so you have time to review before the leadership meeting.

From my conversations with department managers, here's what I'm anticipating:
- Engineering will likely request 2-3 additional developers (they've mentioned workload concerns in our last two check-ins)
- Customer Support needs at least 1 more person. Sandra Morales is going on FMLA leave next month, and the team is already stretched thin
- Sales has expressed interest in a new SDR role but hasn't formalized the request yet

I'll cross-reference this with budget allocations and last year's hiring timeline to give you a realistic picture. One thing to flag is that our average time-to-fill has increased from 34 to 47 days, mainly because of slower hiring manager response times during the interview stage. I have some ideas for streamlining this that I'd like to share at the meeting.

### Email 18
**From:** Jordan Lee
**To:** New Hire Cohort (January 2025)
**Subject:** 30-Day Check-In Survey
**Date:** Mon, Jan 20, 9:00 AM

Hi everyone,

You've been with Apex for about a month now, and I'd love to hear how things are going. Please take 5 minutes to complete this anonymous check-in survey. Your feedback helps us improve the onboarding experience for future hires.

The survey covers:
- Whether your first-week orientation prepared you for your role
- Quality of your workspace and technology setup
- Access to the resources and training you need
- Relationship with your manager and team

Survey link: [internal link]
Deadline: January 27

Your responses are confidential and go directly to HR. If there's something urgent you'd rather discuss in person, my door is always open.

### Email 19
**From:** Jordan Lee
**To:** Rachel Kim (Department Manager, Sales)
**Subject:** Follow-up on attendance issue
**Date:** Wed, Jan 22, 11:00 AM

Rachel, just checking in on the attendance situation we discussed on January 7. Were you able to have the formal conversation using the documentation template? I want to make sure we're tracking this properly in case we need to move to Step 2 of the progressive discipline process.

Also, I noticed that this employee hasn't completed the Q1 compliance training yet. Can you remind him that the deadline is January 31? If there's a reason he can't complete it on time, have him reach out to me directly so we can arrange an alternative schedule.

### Email 20
**From:** Nina Torres (External Recruiter, TalentBridge Agency)
**To:** Jordan Lee
**Subject:** Candidates for Senior Analyst role
**Date:** Thu, Jan 23, 3:30 PM

Jordan, I've sourced five candidates for the Senior Analyst role. Resumes are attached. Two of them are currently employed and would need a minimum 3-week notice period. One is local, and the other four would require relocation support.

Can you review the resumes and let me know which ones you'd like to move forward with? I'd also appreciate it if you could confirm whether Apex offers relocation assistance and what the approved salary range is for this role. That will help me set expectations with the candidates.

### Email 21
**From:** Jordan Lee
**To:** Karen Walsh (HR Director)
**Subject:** Sensitive situation - Sales department
**Date:** Fri, Jan 24, 9:00 AM

Karen, I want to loop you in on something before it escalates. The attendance issue I've been working on with Rachel Kim in Sales is more complicated than it first appeared. The employee in question confided in me yesterday that he's been dealing with a family crisis, but he doesn't want his manager to know the details.

I'm caught between protecting his privacy and making sure Rachel has enough information to manage her team. I told him I'd keep his situation confidential but encouraged him to share what he's comfortable with during his next meeting with Rachel.

Can we discuss this at our Thursday one-on-one? I want to make sure I'm handling the confidentiality piece correctly, especially if this moves to a formal written warning.

### Email 22
**From:** James Porter (General Counsel)
**To:** Jordan Lee
**Subject:** RE: Updated handbook language - remote work policy
**Date:** Fri, Jan 24, 2:15 PM

Jordan, I've reviewed the draft remote work policy language you sent. Two concerns:

1. The eligibility criteria need to specify that remote work is a privilege, not an entitlement. This protects us if we need to revoke it for performance reasons.
2. The section on equipment reimbursement should reference the state-specific requirements. California and Texas have different rules, and since we have offices in both states, we need separate language for each.

I've marked up the document with tracked changes and attached it. Let's finalize this before the February all-hands meeting. Also, can you send me the latest version of the employee acknowledgment form? I want to make sure the arbitration clause is still current.

### Email 23
**From:** Angela Rivera (Department Manager, Engineering)
**To:** Jordan Lee
**Subject:** Promotion recommendation for Dev Lead
**Date:** Mon, Jan 27, 10:30 AM

Jordan, I'd like to formally recommend Wei Chen for promotion from Senior Developer to Dev Lead. He's been informally leading the backend team for six months, and his performance reviews have been consistently exceptional.

Can you walk me through the promotion process? I know there's a committee review involved but I'm not sure about the timeline or what documentation I need to prepare. I'd also like to understand how the compensation adjustment works since this would move him into a new pay band.

### Email 24
**From:** Jordan Lee
**To:** Angela Rivera (Department Manager, Engineering)
**Subject:** RE: Promotion recommendation for Wei Chen
**Date:** Mon, Jan 27, 2:00 PM

Angela, great to hear about Wei. Here's how the promotion process works:

1. Complete the Promotion Recommendation Form (attached). You'll need to include specific performance examples, peer feedback, and how the role aligns with department goals
2. I'll pull Wei's compensation data and do a market comparison to determine the appropriate salary adjustment for the new pay band
3. The Talent Review Committee (you, me, Marcus, and Karen) meets the second week of each month. I'll add Wei to the February agenda
4. If approved, we typically target the promotion to take effect at the beginning of the following month

One thing to consider is that Engineering already has two Dev Leads. You may want to prepare a brief justification for the headcount if anyone on the committee asks why a third is needed.

I'll also need Wei's most recent 360-degree feedback results. Can you check whether those are in the system or if we need to run a new cycle?

### Email 25
**From:** Carlos Medina (Employee, Finance)
**To:** Jordan Lee
**Subject:** Workspace accommodation request
**Date:** Tue, Jan 28, 8:45 AM

Jordan, I was recently diagnosed with a condition that makes it difficult to sit for long periods. My doctor recommended a sit-stand desk and the ability to take short breaks every hour. I have the medical documentation if needed.

I'm not sure what the process is for requesting an accommodation. I haven't told my manager yet because I'm not sure how much I'm required to share. Can you help me figure this out?

### Email 26
**From:** Jordan Lee
**To:** Carlos Medina (Employee, Finance)
**Subject:** RE: Workspace accommodation request
**Date:** Tue, Jan 28, 10:15 AM

Carlos, thank you for reaching out. You're doing exactly the right thing by coming to HR first. Here's how the accommodation process works:

1. You don't need to disclose your specific diagnosis to your manager. You only need to share that you have an approved accommodation
2. Please send me the medical documentation and I'll start the interactive process. I'll send you our ADA Accommodation Request Form today
3. For the sit-stand desk, I can coordinate with Tom in Facilities to get that ordered. These usually arrive within a week
4. The hourly breaks are a reasonable accommodation that I can approve quickly. I'll send a memo to your manager stating that you have an approved accommodation for periodic breaks, without any medical details

Let's schedule a meeting this week so I can walk you through your rights and answer questions. Would Wednesday at 3 PM work?

### Email 27
**From:** Jordan Lee
**To:** Department Managers Distribution List
**Subject:** Mid-year performance review timeline
**Date:** Wed, Jan 29, 9:00 AM

Hi all,

We're kicking off mid-year performance reviews on February 10. Here's the timeline:

- Feb 3-7: Employees complete self-evaluations in the performance management system
- Feb 10-21: Managers conduct one-on-one review meetings
- Feb 28: All reviews finalized and submitted in the system

A few reminders:
- Use the updated competency framework (v3) that was distributed in December
- Each review must include at least two specific development goals for the second half of the year
- If you have any employees on a Performance Improvement Plan, please contact me before conducting their review so we can coordinate messaging

I'll be holding office hours on Feb 4 and 5 from 2-4 PM for anyone who wants to discuss difficult reviews or calibration questions. Sign-up sheet is on my door.

### Email 28
**From:** Ashley Park (Office Manager, Austin Office)
**To:** Jordan Lee
**Subject:** Austin office HR support
**Date:** Wed, Jan 29, 3:30 PM

Jordan, we're growing fast down here and I'm struggling to handle HR-related questions from employees. Last week alone I had three people ask me about benefits changes, two ask about PTO policies, and one person wanted to file a complaint about their manager.

I've been forwarding everything to you, but the time zone difference and email delays are creating frustration. Is there any way we could set up weekly virtual office hours specifically for Austin employees? Or could I be trained on the basics so I can handle the routine stuff?

Also, Elena Martinez (the one with the dental coverage issue from January) wanted me to tell you that it's been resolved. She really appreciated your help.

### Email 29
**From:** Jordan Lee
**To:** Ashley Park (Office Manager, Austin Office)
**CC:** Karen Walsh (HR Director)
**Subject:** RE: Austin office HR support
**Date:** Thu, Jan 30, 9:30 AM

Ashley, this is really valuable feedback. You're right that we need a better solution as Austin grows.

Here's what I'm proposing:
1. I'll start weekly virtual office hours for Austin, Tuesdays from 2-3 PM CST. I'll send a calendar invite to all Austin employees
2. I'm putting together an HR Quick Reference Guide that covers the top 20 questions you're getting (benefits, PTO, basic policy questions). You should be able to answer most routine inquiries with that
3. For complaints or sensitive issues, please continue routing those directly to me. Those need HR handling from the start

Karen, I'm copying you because this ties into the conversation we've been having about whether Austin needs a dedicated HR presence once headcount reaches 50. We're at 38 now and based on Marcus's Q2 hiring projections, we could hit 50 by mid-year.

Glad to hear Elena's issue is resolved. Thanks for the update.

### Email 30
**From:** Ben Taylor (Account Manager, LearnPro Solutions)
**To:** Jordan Lee
**Subject:** New compliance modules available
**Date:** Thu, Jan 30, 2:00 PM

Jordan, wanted to let you know that we've released updated versions of three modules in your LMS subscription:

1. Workplace Harassment Prevention (now includes bystander intervention scenarios)
2. Data Privacy and Security (updated for 2025 state privacy law changes)
3. NEW: Unconscious Bias in Hiring (45-minute module with interactive case studies)

The first two are free updates under your current contract. The Unconscious Bias module is an add-on at $3 per employee per year.

Given your conversation last month about wanting to reduce bias in your hiring process (I noticed you updated your interview scorecards), the new module might be a good fit. Want me to set up a demo for your team?

Your contract renewal is coming up in March. I'll send the renewal proposal next week with pricing for the add-on included as an option.

## Activity Instructions

### Part 1: Email Analysis (15 minutes)

**Task:** Read through all 30 emails carefully. As a team, use AI to analyze the email set.

**Steps:**
1. Copy and paste all 30 emails into your AI tool
2. Write a prompt asking the AI to identify patterns in the emails. Consider asking the AI to analyze:
   - What are the core job responsibilities this person performs?
   - Who does this person interact with, and what is the nature of each relationship?
   - What recurring tasks or processes does this person manage?
   - What knowledge or skills does this person demonstrate?
   - What decisions does this person make independently versus escalate?
   - What tools, templates, or systems does this person use or reference?
3. Review the AI output critically. Does it capture everything? Did it miss any patterns? Are any conclusions inaccurate?

**Deliverable:** A team-reviewed list of key responsibilities, relationships, and competencies extracted from the emails.

### Part 2: Relationship Network Map (15 minutes)

**Task:** Use AI to map Jordan's professional network and visualize who this role connects to across the organization.

**Steps:**
1. Prompt the AI to analyze the 30 emails and create a relationship map. Your prompt should ask the AI to identify:
   - Every person Jordan communicated with
   - The direction of communication (who initiated?)
   - The nature of each relationship (reporting, advisory, service, vendor, cross-functional peer)
   - Frequency of contact (one-time vs. recurring)
   - The type of interaction (information sharing, decision-making, problem-solving, coordination, escalation)
2. Ask the AI to categorize each contact into one of these relationship types:
   - **Upward** (people Jordan reports to or needs approval from)
   - **Lateral** (peers and cross-functional partners)
   - **Downward/Service** (employees Jordan supports or advises)
   - **External** (vendors, recruiters, legal counsel)
3. Ask the AI to generate a visual network diagram using text-based format (e.g., ASCII art, Mermaid diagram syntax, or a structured table). The diagram should show:
   - Jordan at the center
   - Lines connecting to each contact, labeled with the relationship type
   - Thicker or double lines for high-frequency contacts
   - Clusters for related contacts (e.g., all vendor relationships grouped together)
4. As a team, evaluate the AI-generated network map:
   - Did the AI correctly identify all contacts?
   - Are the relationship classifications accurate?
   - Who would be the most critical contacts for a new hire to build relationships with first, and why?
   - Are there any "hidden" connections the emails suggest but don't explicitly show?

**Deliverable:** A visual network map with a brief written analysis (half page) identifying the 5 most critical relationships for the role and explaining why they matter for onboarding.

### Part 3: Job Description Generation (15 minutes)

**Task:** Use AI to generate a formal, detailed job description for the HR Coordinator role based on your analysis.

**Steps:**
1. Craft a prompt that asks AI to create a job description using the email analysis
2. The job description should include:
   - Job title and summary
   - Essential duties and responsibilities (categorized by functional area)
   - Required qualifications (education, experience, certifications)
   - Required knowledge, skills, and abilities (KSAs)
   - Key internal and external relationships
   - Tools and systems used
   - Working conditions and physical requirements
3. Compare your AI-generated job description with Jordan's original vague description: *"The HR Coordinator supports the Human Resources department with various administrative tasks and employee relations activities."*
4. Refine the AI output based on your team's expertise

**Deliverable:** A complete, polished job description (1-2 pages).

### Part 4: Onboarding Training Guide (20 minutes)

**Task:** Transform your job description into a structured 2-week onboarding training plan for the new HR Coordinator.

**Steps:**
1. Prompt the AI to convert the job description into a phased training plan:
   - **Day 1-2:** Orientation, systems access, and introductions (what does the new hire need on day one?)
   - **Day 3-5:** Core process training (which recurring tasks need to be mastered first?)
   - **Week 2:** Guided practice with increasing independence (shadowing key processes, handling real tasks with supervision)
2. For each phase, include:
   - Specific learning objectives
   - Training methods (job shadowing, e-learning, hands-on practice, mentoring)
   - Key people the new hire should meet and learn from
   - Success metrics (how do we know the training worked?)
3. Identify at least 3 things the AI-generated training plan got wrong or missed, and correct them

**Deliverable:** A 2-week onboarding training guide (1-2 pages).

## Discussion Questions

1. **"Companies should be allowed to analyze employee emails without consent to build training programs for replacement hires."** Do you agree or disagree? Where is the line between organizational need and employee privacy?

2. **"AI-generated job descriptions are more accurate than ones written by managers or HR professionals."** Defend or challenge this claim. What can AI capture that humans miss, and what can humans capture that AI misses?

3. **"If a single employee's departure can cripple a department, that is a leadership failure, not a training problem."** Is this a fair statement? Whose responsibility is it to prevent this kind of knowledge loss?

4. **"Organizations should monitor all employee digital communication in real time, not just after someone leaves, so they always have up-to-date role data."** Would you implement this policy? What would the consequences be for organizational culture and trust?

5. **"A well-designed AI training program can fully prepare a new hire to replace a long-tenured veteran within two weeks."** Is this realistic or dangerously overconfident? What can training accomplish, and what can only experience provide?

6. **"An experienced employee's real value comes from relationships, not skills. No training program can replicate that."** If this is true, should organizations even invest in onboarding training, or should they focus entirely on giving new hires time to build relationships?

## Grading Rubric

| Criterion | Excellent (10) | Good (7-8) | Needs Improvement (4-6) | Insufficient (0-3) |
|-----------|---------------|------------|------------------------|-------------------|
| **Email Analysis** | Identifies 8+ distinct responsibilities with supporting evidence from specific emails | Identifies 5-7 responsibilities with some evidence | Identifies 3-4 responsibilities with limited evidence | Fewer than 3 responsibilities or no evidence cited |
| **AI Prompt Quality** | Prompts are specific, structured, and produce detailed outputs. Evidence of iterative prompt refinement | Prompts produce useful outputs with minor gaps | Prompts are vague or generic, producing shallow results | No clear prompting strategy. Copy-paste without thought |
| **Network Map** | Identifies all contacts with accurate relationship classifications. Visual map is clear and insightful. Written analysis identifies 5 critical relationships with strong justification | Most contacts identified with reasonable classifications. Map is readable. Identifies 3-4 critical relationships | Some contacts missing or misclassified. Map is unclear. Fewer than 3 critical relationships identified | Map is incomplete or missing. No meaningful analysis of relationships |
| **Job Description** | Comprehensive, well-organized, includes all required sections, clearly derived from email evidence | Includes most required sections with reasonable detail | Missing sections or contains generic content not tied to emails | Incomplete or clearly copied from a generic template |
| **Training Guide** | Realistic 2-week plan with specific objectives, methods, and metrics for each phase. Identifies 3+ AI errors | Covers all phases with reasonable detail. Identifies 1-2 AI errors | Phases are present but lack specific objectives or methods | Plan is vague, unrealistic, or missing multiple phases |
| **Critical Thinking** | Thoughtful critique of AI output. Identifies subtle gaps, biases, or missing context. Strong discussion participation | Some critique of AI output. Participates in discussion | Minimal critique. Accepts AI output without question | No evidence of critical evaluation |

**Total: 60 points**
